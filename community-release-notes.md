# Release notes for Community quality patches

For information about patching, refer to [Developer Documentation](https://devdocs.magento.com/guides/v2.4/comp-mgr/patching.html).

## v1.0

-  **MDVA-37478** _(for Magento `>=2.3.0 <=2.3.7`)_-Fixes the issue where Magento throws an error when creating a partial invoice for orders placed with the "Payment on Account" payment method through REST API.
-  **MDVA-37362** _(for Magento `>=2.3.4 <=2.4.2-p1`)_-Fixes the issue where configurable product option values and variant attribute values were empty in GraphQL response.
-  **MDVA-37288** _(for Magento `2.4.2`)_-Fixes the issue where wrong tier prices were returned after GraphQL request.
-  **MDVA-37225** _(for Magento `>=2.4.1 <=2.4.2-p1`)_-Fixes the issue where the upload process is stuck during quick order creation when there is an integer value in imported SKUs.
-  **MDVA-37224** _(for Magento `>=2.3.3 <=2.4.2-p1`)_-Fixes the issue where customers cannot pay for negotiable quote with PayFlow Pro with another product in the cart.
-  **MDVA-36286** _(for Magento `>=2.3.6 <=2.4.2-p1`)_-Fixes the issue where Page Builder products widget preview breaks if the same SKU has a different position in subcategories.
-  **MDVA-30186** _(for Magento `>=2.3.4 <=2.3.5-p2, >=2.4.0 <=2.4.0-p1, >=2.4.2 <=2.4.2-p1`)_-Fixes the issue where attribute options are sorted by option value instead of attribute item count, in GraphQL response.
