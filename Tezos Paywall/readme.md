This WordPress plugin requires a user to pay 1 Tezos in order to view a page. It does this by adding a shortcode to the page that checks if the user has made the required payment using the temple_wallet_payment_received() function from the Temple Wallet plugin.

To use this plugin, you can add the shortcode [tezos_paywall wallet_address="[WALLET ADDRESS]"] to any page or post that you want to restrict access to. Replace [WALLET ADDRESS] with the address of the wallet that will receive the payment.

For example, if you want to restrict access to a page and have the payment sent to wallet address tz1abcdefghijklmnopqrstuvwxyz, you can use the shortcode [tezos_paywall wallet_address="tz1abcdefghijklmnopqrstuvwxyz].

You can also customize the amount of the payment and the message that is displayed to users who have not made the payment by using the amount and message attributes. For example, [tezos_paywall wallet_address="tz1abcdefghijklmnopqrstuvwxyz" amount="2" message="Sorry, you need to pay 2 Tezos to view this page."]

If the user has not made the required payment, the plugin will display the message provided in the shortcode and a payment button that allows the user to make the payment using the Temple wallet. If the user has made the required payment, the plugin will do nothing and the user will be able to view the page as normal.

This plugin requires the Temple Wallet plugin to be installed and active on your WordPress website in order to function properly. The Temple Wallet plugin provides the necessary functions and features for interacting with Tezos wallets and making payments.

Without the Temple Wallet plugin installed and active, the tezos_paywall plugin will not be able to check for payment or display the payment button, and the shortcode will not work as intended.

To use this plugin, you will need to first install and activate the Temple Wallet plugin on your WordPress website. Then, you can install and activate the tezos_paywall plugin and use the shortcode to restrict access to pages based on payment using Tezos.
