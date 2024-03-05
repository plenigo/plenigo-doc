# Changelog API

## API.240305-MINOR - 2024-03-05
### NEW
* Add possibility to search for a specific voucher code
* Enhance subscription entity documentation by adding missing fields

## API.240226-MINOR - 2024-02-26
### NEW
* Importer now supports addToExistingChain flag for external managed offers

## API.240223-MINOR - 2024-02-23
### NEW
* To handle automatic renewal of api access tokens a new request endpoint is provided: /settings/apiAccessTokens/requestRenewedToken

## API.3.2406.0 - 2024-02-08
### NEW
* Address validation status has a new type: OVERRIDDEN

## API.3.2405.0 - 2024-01-31
### NEW
* Added possibility to select identity check type for age verification rules
### FIXES
* Fix HTTP status code for session limit reached during verifiy login
* Fix HTTP status code for session limit reached during reset password

## API.3.2402.0 - 2024-01-17
### FIXES
* Fix problem with regular cancellation date selection list ignoring cancellation period

## API.3.2401.0 - 2024-01-10
### NEW
* Add possibility to add deliveries to an issue based subscription
* Add possibility to set a status for a delivery date

## API.3.2351.0 - 2023-12-20
### NEW
* Enhanced order import for WBZ imports

## API.3.2350.0 - 2023-12-12
### NEW
* Enhanced order import for issue based imports

## API.3.2349.0 - 2023-12-06
### NEW
* Add new filters to invoice endpoint
* Add processing blocked flag to customer
  
## API.3.2348.0 - 2023-11-28
### NEW
* Add possibility to disscociate app store purchase
### CHANGES
* Marking endpoints as async in doc

## API.3.2347.0 - 2023-11-23
### NEW
* Added credit card issuer
* Enable filtering of customers by marks

## API.3.2345.0 - 2023-11-07
### NEW
* Added WBZ addresses

## API.3.2345.0 - 2023-10-31
### NEW
* Added customer marks

## API.3.2343.0 - 2023-10-24
### NEW
* Add possibility to delete a stripe customer
* Add delivery lists for shared offers
* Added shipping costs
* Added more subscription types

## API.3.2341.0 - 2023-10-13
### NEW
* Added shared offer endpoints
* Added precursor and successor reason details
* Added VAT number validation

## API.3.2340.0 - 2023-10-04
### NEW
* Add import logic for issue based subscriptions

## API.3.2339.0 - 2023-09-27
### NEW
* Add cross client delivery lists
* Add cross client IVW reports

## API.3.2337.0 - 2023-09-12
### NEW
* Add additional fields regarding issue based properties to subscriptions

## API.3.2336.0 - 2023-09-05
### NEW
* Voucher endpoint is now supporting the promise logic - so generated vouchers create a callback

## API.3.2335.0 - 2023-08-29
### NEW
* Add new fields for hints to offers and shopping carts
  
## API.3.2334.0 - 2023-08-22
### NEW
* Add new credit wallet endpoint

## API.3.2333.0 - 2023-08-15
### NEW
* Add cross client endpoints

## API.3.2331.0 - 2023-08-05
### NEW
* Add subscriptionStartDate to prepare checkout

## API.3.2329.0 - 2023-07-25
### NEW
* Add GDPR request

## API.3.2328.0 - 2023-07-18
### NEW
* Add subscription type CROSS_CLIENT_SUBSCRIPTION_TIME_BASED

## API.3.2327.0 - 2023-07-04
### NEW
* Add force payment method to prepare checkout

## API.3.2326.0 - 2023-06-27
### NEW
* Add address required flags to checkout addresses
### CHANGES
* Add null values to API doc
  
## API.3.2325.0 - 2023-06-20
### NEW
* Add possibility to allow checkout only for specific countries
* Add a new endpoint to add an existing Stripe customer to the plenigo system
* Add new IVW report type
* Add a new endpoints for retrieving text modules

## API.3.2323.0 - 2023-06-06
### NEW
* Add new endpoint for iterating customers additional data

## API.3.2321.0 - 2023-05-25
### NEW
* Add invalid fields to payment methods

## API.3.2317.0 - 2023-04-25
### NEW
* Add new fields to offer for company connections
 
## API.3.2316.0 - 2023-04-18
### FIXES
* Fixed slow caching refresh rates in IVW endpoints

## API.3.2314.0 - 2023-04-04
### NEW
* Add referenceStartDate to imports

## API.3.2313.0 - 2023-03-28
### NEW
* Add purchase order indicator to imports

## API.3.2312.0 - 2023-03-21
### NEW
* Add pagination to vouchers

## API.3.2311.0 - 2023-03-14
### NEW
* Add new filters to refunds

## API.3.2310.0 - 2023-03-07
### NEW
* Add language parameter to Google SSO provider
* Add retry functionality to callbacks
### FIXES
* added missing HTTP error codes to doc

## API.3.2309.0 - 2023-02-28
### NEW
* Enable password change by user update
* Add status IGNORED to refunds - in case a merchant doesn't want to handle the refund

## API.3.2308.0 - 2023-02-22
### NEW
* Add PostFinance accounts endpoints
* Add Twint accounts endpoints
* Add Refunds endpoints
* Add Google SSO provider

## API.3.2307.0 - 2023-02-15
### NEW
* Add new payment actions for PAYPAL_PAYOUT and PAYPAL_TRANSACTION_STATUS.

## API.3.2306.0 - 2023-02-07
### NEW
* Add possibility to to set purchase flag for import endpoint
* Add possibility to set set supressMail flag for import endpoint
### FIXES
* Fixed status parameter name in API doc for tracking data update

## API.3.2305.0 - 2023-01-31
### CHANGES
* Improve X-Rechnung handling for companies with special characters in company name

## API.3.2304.0 - 2023-01-24
### NEW
* Add emergency mode status
* Add flag indicating if SSO functionality is disabled
### CHANGES
* Improve Google app purchase handling for uploading of already expired purchases

## API.3.2303.0 - 2023-01-17
### CHANGES
* Bugfixing

## API.3.2302.0 - 2023-01-10
### CHANGES
* Add payerDeliveryAddressId to order import

## API.3.2301.0 - 2023-01-03
### NEW
* Bugfixing

## API.3.2252.0 - 2022-12-28
### NEW
* Add useTermQuery parameter to subscription cancellation dates
* Add possibility to search for corporate account ids

## API.3.2251.0 - 2022-12-22
### NEW
* Add new payment actions to transactions

## API.3.2250.0 - 2022-12-15
### NEW
* Add new mail template types

## API.3.2248.0 - 2022-11-29
### NEW
* Add bonus ids to import

## API.3.2246.0 - 2022-11-17
### NEW
* Add change date to app store order
* Add change date to app store subscription
* Change handling of empty app receipts
* Multiple app receipts are returning multiple tokens
### FIXES
* Fixed typos in API documentation

## API.3.2244.0 - 2022-11-03
### NEW
* Add payment method endpoints for PayPal accounts
* Add send mail flag to corporate accounts user endpoint
* Add payment method endpoints for iDeal accounts
* Add wallet endpoints for uploaded and used credits
### FIXES
* Fixed incorrect error codes - HTTP codes 412 are now correctly returned as 400 HTTP codes and fixed in documentation

## API.3.2242.0 - 2022-10-20
### NEW
* Add beginningBefore parameter for backwards pagination
* Add fixedStartDate setting to offer
* Add issuesInPast and issuesInFuture settings to offer

## API.3.2241.0 - 2022-10-11
### NEW
* Remove accounting record endpoints from API documentation because they are deprecated

## API.3.2240.0 - 2022-10-04
### NEW
* Add additional API responses to app store additions
* Add new email template PAYMENT_METHOD_CHANGED
* Add new showNetPrices flag to checkout preparation

## API.3.2238.0 - 2022-09-15
### NEW
* Add possibility to add future address sets to an address for address changes in the future 

## API.3.2237.0 - 2022-09-15
### NEW
* Add possibility to add future address sets to an address for address changes in the future 

## API.3.2233.0 - 2022-08-18
### CHANGES
* Internal changes

## API.3.2232.0 - 2022-08-09
### CHANGES
* Internal changes

## API.3.2231.0 - 2022-08-02
### NEW
* Add possibility to overwrite product id during voucher checkout
* Add new mail template RECURRING_PAYMENT_TRY_FAILED
 
## API.3.2230.0 - 2022-07-26
### FIXES
* Unified customer id validation

## API.3.2229.0 - 2022-07-19
### NEW
* Add endpoint creating wallets
* Add endpoint for uploading credits to a wallet
* Add possibility to search for an email at the customers search endpoint
### FIXES
* Fix setting of external system id for existing customers

## API.3.2228.0 - 2022-07-12
### NEW
* Add endpoints for sort tree leafs

## API.3.2227.0 - 2022-07-05
### NEW
* Add endpoints for requesting SFTP logs

## API.3.2226.0 - 2022-06-28
### NEW
* Add associate and dissociate methods for Apple App Store purchases
* Add associate and dissociate methods for Google Playstore purchase

## API.3.2225.0 - 2022-06-21
### NEW
* Added payment method details to subscriptions
* Added payment method details to orders
### FIXES
* Removed not existing subscription status from API doc

## API.3.2224.0 - 2022-06-14
### FIXES
* Fixes to API doc regarding spelling and typos

## API.3.2223.0 - 2022-06-07
### NEW
* Add new mail template types
* Add additional data selections management

## API.3.2222.0 - 2022-05-31
### NEW
* Add paymentChangedToBilling flag to invoices
* Add checkout address settings to checkout preparation
* Add gift option to checkout preparation
* Add gift info to order
### CHANGES
* Fix docuemntation error in misuse rule duration

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
