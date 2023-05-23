# kkiapay-magento

Payment gateway integration in magento 2 plateforme
# Installation & Configuration
## Step 1: Setup kkiapay-magento module

1. Add this repository into `src/app/code/` of your project

2. Update public api key from `KkiapayPaymentGateway/view/frontend/web/js/view/payment/method-renderer` at `beforePlaceOrder` function
change attributs `key` and `snadbox` with the correct one.

## Step 2: Install & activate

Run `bin/magento setup:upgrade`

