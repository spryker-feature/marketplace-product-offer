# Spryker Feature: Marketplace Product Offer

Merchant Offer is a new entity that allows a Merchant to sell the Product on the Marketplace. If the product already exists in the system and Merchant wants to sell it, s/he creates a Merchant Offer for this product. Merchant Offer is based on the concrete product and might contain such details as price, stock, status, etc.

## Installation

```
composer require spryker-feature/marketplace-product-offer
```

## Recommended feature dependencies
- [spryker-feature/marketplace-merchant](https://github.com/spryker-feature/marketplace-merchant)
- [spryker-feature/product](https://github.com/spryker-feature/product)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [MerchantProductOffersRestApi ^0.6.1](https://github.com/spryker/merchant-product-offers-rest-api) (Glue)
- [MerchantProductOfferStorageExtension ^0.2.0](https://github.com/spryker/merchant-product-offer-storage-extension) (Extension)
- [ProductOfferExtension ^0.1.0](https://github.com/spryker/product-offer-extension) (Extension)
- [ProductOfferGuiExtension ^0.1.0](https://github.com/spryker/product-offer-gui-extension) (Extension)
