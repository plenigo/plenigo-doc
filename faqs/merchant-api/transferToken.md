# Merchant-Backend: Login via transferToken

The plenigo Merchant-Backend can be fully integrated into the infrastructure of a company. If there is a central user provider, SSO-System or similar, one is able to log in silently into plenigo backend.
## Preparation
Create an Api token for each user in the user administration of contract company
![image](https://user-images.githubusercontent.com/3322840/123052976-b1ecab00-d403-11eb-8250-999b24a4777a.png)

Copy Api token into your SSO system
![image](https://user-images.githubusercontent.com/3322840/123053507-40f9c300-d404-11eb-8687-d9b60cba37f6.png)

## Use Merchant-API
Now, you can use [Merchant-API](https://merchant-api.plenigo-stage.com/) with this token. Simply add header `X-plenigo-merchant-api-session: {apiToken}` to access API endpoints.

## Log in into plenigo merchant backend
To log in user silently you have to follow these simple steps.

### Create a transfer token
- First you have to [create transfer token](https://merchant-api.plenigo-stage.com/#tag/User-Login/paths/~1processes~1merchantUser~1transferToken~1create/post). This should be done on the fly, transfer token will be removed after 30 minutes.
- with this transferToken you can silently login via [https://backend.plenigo-stage.com/login?transferToken={transfertoken}](https://backend.plenigo-stage.com/login?transferToken={transfertoken})
