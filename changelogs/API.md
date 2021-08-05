# Changelog API

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
