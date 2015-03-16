API Changelog
=============

This is a public record of the BillForward API changelog

API Changelog
=============

This is a public record of the BillForward API changelog

### 1.2015.075

-   Improved receipts for Stripe ACH


>   Released to sandbox (2015/03/12 13:00 +12:00)

>   Released to production (2015/03/14 12:00 +12:00)

### 1.2015.068

-   Bug where two payment methods could be marked as default for the same account
-   No longer allow deleted payment methods to be default
-   Bug handling coupons in the final invoice generated when a subscription expires


>   Released to sandbox (2015/03/09 13:00 +12:00)

>   Released to production (2015/03/09 17:17 +12:00)

### 1.2015.062

-   Unpaid invoices may be returned to the 'Pending' state
-   Invoices may now be marked as 'Paid' without taking any payment


>   Released to sandbox (2015/03/03 13:00 +00:00)

>   Released to production (2015/03/04 17:17 +00:00)


### 1.2015.027

-   Add 'companyName' to profiles
-   Introduced new simplified coupon endpoints to the API
-   Introduced default payment methods
-   Introduced default tax
-   Simplified payment method API endpoints
-   Simplified tax API endpoints
-   General API improvements
-   Add semantic meaning to ids, i.e. ACC-B48AE...


>   Released to sandbox (2015/02/09 16:00 +00:00)

>   Released to production (2015/02/12 14:37 +00:00)


### 1.2015.014

-   General performance improvements
-   Logging improvements for the Braintree Payment Gateway
-   Improved search


>   Released to sandbox (2015/01/14 17:54 +00:00)

>   Released to production (2015/01/22 12:30 +00:00)


### 1.2014.296 

-   Simplification of Refund and Coupon API - [docs](https://app-sandbox.billforward.net/#/api/method/refunds)
-   Bug when generating multiple Stripe refunds
-   Bug in setup components fixed
-   Bug in handling of Stripe ACH webhooks


>   Released to: sandbox (2014/12/16 18:12 +00:00)

>   Released to: production (2014/12/17 12:30 +00:00)<200b>
