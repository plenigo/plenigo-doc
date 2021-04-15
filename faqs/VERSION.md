# Version Schema

plenigo API versions consist of four digits:

`X.X.X-X`

| Version | Name  | Description                                                     | Expiration time<sup>1</sup> |
| ------- |:-----:| --------------------------------------------------------------- | :-------------------------: |
| X       | main  | new API design                                                  | 12 MONTH                    | 
| 0.X     | major | removal of fields or methods - can break things                 | 6 MONTH                     |
| 0.0.X   | minor | additional methods or fields added - fully backwards compatible | -                           |
| 0.0.0-X | doc   | errors or changes in API documentation                          | -                           |

1) Time after a new version is release when the old version will be deprecated, and an upgrade will be forced to all users.