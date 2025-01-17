# Prestashop plugin for Paylike

**END OF MAINTENANCE**

**Prestashop 1.6.x is no longer receiving updates so for improved security and maintenance we encourage you to use 1.7.x. You can find the 1.7 extension here: https://github.com/paylike/plugin-prestashop-1.7**

This plugin is *not* developed or maintained by Paylike but kindly made
available by the community.

Released under the MIT license: https://opensource.org/licenses/MIT

You can also find information about the plugin here: https://paylike.io/plugins/prestashop16

## Supported Prestashop versions

* The plugin has been tested with most versions of Prestashop at every iteration. We recommend using the latest version of Prestashop, but if that is not possible for some reason, test the plugin with your Prestashop version and it would probably function properly. 
* Prestashop version last tested on: *1.6.1.24*

## Installation

Once you have installed Prestashop, follow these simple steps:

1. Signup at [paylike.io](https://paylike.io) (it’s free)
1. Create a live account
1. Create an app key for your CS-Cart website
1. Zip the paylikepayment folder (or use the zip provided).
2. Log in as administrator and upload the zip you just created under modules/add a new module (plus icon in the top right corner).
3. You will be redirected to a list that contains the Paylike plugin. Click the green button that says install, and then in the confirmation popup, click proceed with the installation.  
4. You will be redirected to the settings screen where you need to  add the Public and App key that you can find in your Paylike account.

## Updating settings

Under the extension settings, you can:
 * Update the payment method text in the payment gateways list
 * Update the payment method description in the payment gateways list
 * Update the credit card logos that you want to show (you can change which one you accept under the paylike account).
 * Update the title that shows up in the payment popup 
 * Update the popup description, choose whether you want to show the popup  (the cart contents will show up instead)
 * Add test/live keys
 * Set payment mode (test/live)
 * Change the capture type (Instant/Manual via Paylike Tool)
 
## Limitations
 
 * In order to use the Paylike module you'll need to set "Number of decimals" option to match the paylike supported decimals. Since this is a global setting that affects all currencies you cannot use at the same time currencies with different decimals. 
 Change this option from: Admin -> Preferences -> General

 * Paylike doesn't provide support for customizable decimals display. In order to display the correct values durring the payment process you'll need to set "Decimals" option to value "True" for the "Edit" panel of the currencies used in your store.
 Change this option from: Admin -> Localization -> Currencies