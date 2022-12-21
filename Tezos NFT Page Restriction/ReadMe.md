This WordPress plugin prevents a user from viewing a page unless they have a specific Tezos NFT in their wallet. It does this by adding a shortcode to the page that checks the user's wallet for the required NFT using the temple_wallet_has_nft() function from the Temple Wallet plugin.

To use this plugin, you can add the shortcode [tezos_nft_restriction nft_id="[NFT ID]"] to any page or post that you want to restrict access to. Replace [NFT ID] with the ID of the NFT that is required to view the page.

For example, if you want to restrict access to a page to users who have NFT ID 12345, you can use the shortcode [tezos_nft_restriction nft_id="12345"].

You can also customize the message that is displayed to users who do not have the required NFT by using the message attribute. For example, [tezos_nft_restriction nft_id="12345" message="Sorry, you need to own NFT 12345 to view this page."]

If the user does not have the required NFT in their wallet, the plugin will display the message provided in the shortcode and prevent the user from accessing the page. If the user does have the required NFT, the plugin will do nothing and the user will be able to view the page as normal.

This WordPress plugin requires the Temple Wallet plugin to be installed and active on your WordPress website in order to function properly. The Temple Wallet plugin provides the necessary functions and features for interacting with Tezos wallets and NFTs.

Without the Temple Wallet plugin installed and active, the tezos_nft_restriction plugin will not be able to check the user's wallet for the required NFT, and the shortcode will not work as intended.

To use this plugin, you will need to first install and activate the Temple Wallet plugin on your WordPress website. Then, you can install and activate the tezos_nft_restriction plugin and use the shortcode to restrict access to pages based on the user's possession of a specific Tezos NFT.
