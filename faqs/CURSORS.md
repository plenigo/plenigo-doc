#Paging / Cursor Usage

Sometimes people get confused and are not used working with cursors for pagination. 
On this page we will explain by an example how pagination with cursors is working.

All search methods are providing two parameters:

|Parameter Name |Description                                                                                                              |
| ------------- | ----------------------------------------------------------------------------------------------------------------------- |
| startingAfter | startinAfter is an object ID that defines your place in the list                                                        |
| size          | amount of elements to return - if no size is provided or the size is not within range it will be automatically set to 5 |

On your first request you don't set the startingAfter parameter at all. The result will look something like the example below. We assume
the default size of 5 elements.

```json
{
  "items": [
    {
      "entityId": 10000,
      "title": "First element"
    },
    {
      "entityId": 10001,
      "title": "Second element"
    },
    {
      "entityId": 10002,
      "title": "Third element"
    },
    {
      "entityId": 10003,
      "title": "Fourth element"
    },
    {
      "entityId": 10004,
      "title": "Fifth element"
    }
  ]
}
```

We received 5 elements, so we can assume that there are additional pages. If there had been less than 5 elements we would know that we reached the end of the list.

The entity list is sorted by the entity id, and we now have to use the entity id of the last element as startingAfter parameter. Our URL would look like this

`https://api....?startingAfter=10004`

This will result in the following list:

```json
{
  "items": [
    {
      "entityId": 10005,
      "title": "Sixth element"
    },
    {
      "entityId": 10006,
      "title": "Seventh element"
    }
  ]
}
```

Now we didn't receive 5 elements, so we know we are at the end of the list and don't have to continue.