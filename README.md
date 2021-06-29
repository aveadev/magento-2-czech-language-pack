## Magento 2 Czech Language Pack

**Install Czech pack**:

``` php
composer require aveadev/magento-2-czech-language-pack:dev-master
php bin/magento setup:static-content:deploy cs_CZ
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```
