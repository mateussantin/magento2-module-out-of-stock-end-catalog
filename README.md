# Magento 2 Products out of stock at the end of the catalog
This module positions products out of stock last in the catalog listing.

### Requirements
- Magento 2

## Introduction to installation:

### Enable Extension

```
php bin/magento module:enable MateusSantin_OutOfStockEndCatalog
php bin/magento setup:upgrade
php bin/magento cache:clean
php bin/magento setup:static-content:deploy
```
