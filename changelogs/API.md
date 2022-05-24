# Changelog API

## API.3.2221.0 - 2022-05-24
### NEW
* Add customer cancellation reasons endpoint
* Add customer opt ins endpoint
* Add customer terms endpoint
* Add AmazonPay endpoint
* Add age rules endpoint
* Add app store offers endpoint
* Add credit wallets endpoint
* Add event lists endpoint
* Add IVW rules endpoint
* Add relation rules endpoint

## API.3.2220.0 - 2022-05-18
### NEW
* Add pause subscription
* Add delivery breaks
* Add Datatrans as PSP
### CHANGES
* Improvements to import API
* Add new mail templates

## API.3.2219.0 - 2022-05-10
### CHANGES
* Add new payment providers

## API.3.2218.0 - 2022-05-03
### NEW
* Added stopOnFail flag to age rules endpoint
* Added ageVerificationPinEnabled flag to customers endpoint
### FIXES
* Fixed API doc parameters

## API.3.2217.0 - 2022-04-26
### NEW
* Added opt-in endpoints to control and retrieve opt-ints
* Added additional product type SINGLE_PRODUCT_CREDIT_BASED

## API.3.2216.0 - 2022-04-21
### NEW
* Added bonuses to prepareCheckout call
* Added bonuses to products
### CHANGES
* Possibility to remove addresses and payment methods from inactive subscriptions

## API.3.2215.0 - 2022-04-12
### NEW
* Change version number schema of API
### FIXES
* Fixed rule error texts in checkout

## 3.0.22-0 - 2022-04-06
### NEW
* Add new callback types
* Add new mail template types
* Add new subscription types
* Add voucher purchase logic to orders
### FIXES
* Add undocumented properties to subscription, product and order documentation
* Additional data selection validation documentation was incorrect

## 3.0.21-0 - 2022-03-22
### NEW
* Add welcome mail to customer creation
* Add voucher sales to product

## 3.0.20-0 - 2022-03-15
### NEW
* Add welcome mail as mail template type
* Add product type to offers products

## 3.0.19-0 - 2022-03-08
### NEW
* Add bonus endpoints
* Add mail sending flag to undo subscription cancellation endpoint

## 3.0.18-0 - 2022-02-25
### NEW
* Add status flag to invoice
* Add endpoint to cancel subscription at a specific time
* Add endpoint to request possible cancellation dates
* Add more possibilites for name requirements during login and registration
### FIXES
* Add missing async warning to voucher creation doc

## 3.0.17-0 - 2022-02-01
### NEW
* Added custom accounting fields to ledgers
* Enhance maximum voucher size
### CHANGES
* Remove possibility to cancel subscription items of a subscription via API because of too many accidentially usages
### FIXES
* Removed undocumented and incorrect filled plenigo step id from subscription that is sporadically sent out. Only the documented plenigo step id at the subscription item is valid.
* Enhance documenation examples
* Added mutliple missing fields in documentation
* Fix incorrect download association in documenation

## 3.0.16-0 - 2022-01-13
### NEW
* Added new invoice status endpoints
* Added new invoice status flag to invoices
* Added purchase order indicator endpoint for subscriptions
* Added analytics endpoint for subscription cancellation reasons
* Added additional wallet endpoints to cutomers

## 3.0.15-0 - 2022-01-03
### NEW
* Added wallets endpoints
* Added invoice payment failed endpoint
* Added force deletion flag for customer

## 3.0.14-0 - 2021-12-08
### NEW
* Added possibility to handle different checkout designs
### FIXES
* Fix delivery list dates documentation

## 3.0.13-0 - 2021-11-14
### NEW
* Added shopping cart endpoints
* Added new product tag types
* Added new cross selling access start time
### FIXES
* Fix IVW result documentation
* Added Amazon Pay to all payment method enums

## 3.0.12-0 - 2021-10-28
### NEW
* Added subscription delivery dates endpoints
* Added IVW endpoints

## 3.0.11-0 - 2021-10-25
### NEW
* Added order import endpoints
* Added parameter to override address validation

## 3.0.10-0 - 2021-09-25
### NEW
* Add cancellation reason unqiue id to subscription
* Added period start and end date to invoice item
### FIXES
* Fix incorrect url for registration with login identifier
* Remove incorrectly added fields from subscription items documentation

## 3.0.9-0 - 2021-08-30
### NEW
* Add analog invoice endpoint to subscriptions
* Add suppress invoice sending enpoint to subscriptions

## 3.0.8-0 - 2021-08-20
### NEW
* Added login identifier to registration endpoint
### FIXES
* Cost center size
* Spelling errors

## 3.0.7-0 - 2021-08-05
### NEW
* Added download endpoints
* Added additional callback types for app stores
* Added suppress refund parameter to invoice cancellation
* Added short description to cost center
* Added additional hasOrders field to app store purchases
### FIXES
* Fix documentation for app store purchases
* Fix corporate account URLs

## 3.0.6-0 - 2021-06-29
### NEW
* Added endpoint for foreign orders
* PurchaseStart-Call gets two additional fields: startWithVoucherInput and hideVoucherInput
* Added IVW rules to products
* Removed unused status code for invoice cancellation
* Added custom data field to vouchers
* Add cancellation reason to subscriptions
### FIXES
* Fix requried fields for ledgers
* Fix incorrect status code descriptions for customer session request
* Fix corporate account URLs

## 3.0.5-0 - 2021-05-17
### NEW
* Added global additional data to access rights
* Added allow multiple purchases flag to checkout preparation
### FIXES
* Fix documentation for title property length in ledger

## 3.0.4-0 - 2021-05-03
### NEW
* Added possiblity to make bulk requests against order data

## 3.0.3-0 - 2021-04-26
### NEW
* Added status history for customers (only for future status changes)
* Addes status history for subscriptions (only for future status changes)

## 3.0.2-0 - 2021-04-16
### CHANGES
* The app store order item now contains a "accessRightUniqueId" field

## 3.0.1-0 - 2021-04-15
### NEW
 * There are new API endpoints below the customers category to retrieve the failed and successful log in logs for cutomers
### CHANGES
 * The customer entity now contains a "registrationDate" field
