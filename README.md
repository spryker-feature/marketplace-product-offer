# Spryker Feature: Marketplace Product Offer

Merchant Offer is a new entity that allows a Merchant to sell the Product on the Marketplace. If the product already exists in the system and Merchant wants to sell it, s/he creates a Merchant Offer for this product. Merchant Offer is based on the concrete product and might contain such details as price, stock, status, etc.

[Learn more](https://docs.spryker.com/docs/pbc/all/offer-management/202307.0/marketplace/marketplace-product-offer-feature-overview.html)

## Installation

```
composer require spryker-feature/marketplace-product-offer
```

## Recommended feature dependencies
- [spryker-feature/marketplace-merchant](https://github.com/spryker-feature/marketplace-merchant)
- [spryker-feature/product](https://github.com/spryker-feature/product)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [MerchantProductOffersRestApi ^2.1.0](https://github.com/spryker/merchant-product-offers-rest-api) (Legacy Glue)
- [MerchantProductOfferStorageExtension ^1.1.0](https://github.com/spryker/merchant-product-offer-storage-extension) (Extension)
- [Shop.MerchantProductOfferWidgetExtension ^1.0.0](https://github.com/spryker-shop/merchant-product-offer-widget-extension) (Extension)
- [ProductOfferExtension ^1.0.0](https://github.com/spryker/product-offer-extension) (Extension)
- [ProductOfferGuiExtension ^1.0.0](https://github.com/spryker/product-offer-gui-extension) (Extension)
- [ProductOffersRestApi ^1.1.0](https://github.com/spryker/product-offers-rest-api) (Legacy Glue)
- [ProductOfferStorageExtension ^1.1.0](https://github.com/spryker/product-offer-storage-extension) (Extension)
