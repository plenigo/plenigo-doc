# Changelog API

## 3.0.15-0 - 2021-01-03
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
