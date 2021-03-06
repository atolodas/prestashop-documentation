Class PackCore
=====================





* Class name: PackCore
* Parent class: [Product](class.ProductCore.md)
* Source: [classes/Pack.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L27)


Contents
--------


### Properties

* [$cacheIsPack](#property-$cacheIsPack)
* [$cacheIsPacked](#property-$cacheIsPacked)
* [$cachePackItems](#property-$cachePackItems)
* [$_cacheFeatures](#property-$_cacheFeatures)
* [$_cart_quantity](#property-$_cart_quantity)
* [$_frontFeaturesCache](#property-$_frontFeaturesCache)
* [$_incat](#property-$_incat)
* [$_prices](#property-$_prices)
* [$_pricesLevel2](#property-$_pricesLevel2)
* [$_taxCalculationMethod](#property-$_taxCalculationMethod)
* [$_tax_rules_group](#property-$_tax_rules_group)
* [$active](#property-$active)
* [$additional_shipping_cost](#property-$additional_shipping_cost)
* [$advanced_stock_management](#property-$advanced_stock_management)
* [$available_date](#property-$available_date)
* [$available_for_order](#property-$available_for_order)
* [$available_later](#property-$available_later)
* [$available_now](#property-$available_now)
* [$cacheStock](#property-$cacheStock)
* [$cache_default_attribute](#property-$cache_default_attribute)
* [$cache_has_attachments](#property-$cache_has_attachments)
* [$cache_is_pack](#property-$cache_is_pack)
* [$category](#property-$category)
* [$condition](#property-$condition)
* [$customizable](#property-$customizable)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$depends_on_stock](#property-$depends_on_stock)
* [$depth](#property-$depth)
* [$description](#property-$description)
* [$description_short](#property-$description_short)
* [$ean13](#property-$ean13)
* [$ecotax](#property-$ecotax)
* [$height](#property-$height)
* [$id_category_default](#property-$id_category_default)
* [$id_color_default](#property-$id_color_default)
* [$id_manufacturer](#property-$id_manufacturer)
* [$id_product_redirected](#property-$id_product_redirected)
* [$id_shop_default](#property-$id_shop_default)
* [$id_supplier](#property-$id_supplier)
* [$id_tax_rules_group](#property-$id_tax_rules_group)
* [$indexed](#property-$indexed)
* [$isFullyLoaded](#property-$isFullyLoaded)
* [$is_virtual](#property-$is_virtual)
* [$link_rewrite](#property-$link_rewrite)
* [$location](#property-$location)
* [$manufacturer_name](#property-$manufacturer_name)
* [$meta_description](#property-$meta_description)
* [$meta_keywords](#property-$meta_keywords)
* [$meta_title](#property-$meta_title)
* [$minimal_quantity](#property-$minimal_quantity)
* [$name](#property-$name)
* [$new](#property-$new)
* [$on_sale](#property-$on_sale)
* [$online_only](#property-$online_only)
* [$out_of_stock](#property-$out_of_stock)
* [$price](#property-$price)
* [$producPropertiesCache](#property-$producPropertiesCache)
* [$quantity](#property-$quantity)
* [$quantity_discount](#property-$quantity_discount)
* [$redirect_type](#property-$redirect_type)
* [$reference](#property-$reference)
* [$show_price](#property-$show_price)
* [$supplier_name](#property-$supplier_name)
* [$supplier_reference](#property-$supplier_reference)
* [$tags](#property-$tags)
* [$tax_name](#property-$tax_name)
* [$tax_rate](#property-$tax_rate)
* [$text_fields](#property-$text_fields)
* [$unit_price](#property-$unit_price)
* [$unit_price_ratio](#property-$unit_price_ratio)
* [$unity](#property-$unity)
* [$upc](#property-$upc)
* [$uploadable_files](#property-$uploadable_files)
* [$visibility](#property-$visibility)
* [$webserviceParameters](#property-$webserviceParameters)
* [$weight](#property-$weight)
* [$wholesale_price](#property-$wholesale_price)
* [$width](#property-$width)
* [$db](#property-$db)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$get_shop_from_context](#property-$get_shop_from_context)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$id_shop_list](#property-$id_shop_list)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$update_fields](#property-$update_fields)

### Methods

* [__construct](#method-__construct)
* [_checkLabelField](#method-_checkLabelField)
* [_createLabel](#method-_createLabel)
* [_deleteOldLabels](#method-_deleteOldLabels)
* [_getAttributeImageAssociations](#method-_getAttributeImageAssociations)
* [_getCustomizationFieldsNLabels](#method-_getCustomizationFieldsNLabels)
* [_getProductIdByDate](#method-_getProductIdByDate)
* [add](#method-add)
* [addAttribute](#method-addAttribute)
* [addAttributeCombinaison](#method-addAttributeCombinaison)
* [addAttributeCombinationMultiple](#method-addAttributeCombinationMultiple)
* [addCombinationEntity](#method-addCombinationEntity)
* [addCustomizationPrice](#method-addCustomizationPrice)
* [addFeatureProductImport](#method-addFeatureProductImport)
* [addFeaturesCustomToDB](#method-addFeaturesCustomToDB)
* [addFeaturesToDB](#method-addFeaturesToDB)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [addItem](#method-addItem)
* [addProductAttribute](#method-addProductAttribute)
* [addProductAttributeMultiple](#method-addProductAttributeMultiple)
* [addStockMvt](#method-addStockMvt)
* [addSupplierReference](#method-addSupplierReference)
* [addToCategories](#method-addToCategories)
* [addWs](#method-addWs)
* [associateTo](#method-associateTo)
* [cacheFrontFeatures](#method-cacheFrontFeatures)
* [cacheProductsFeatures](#method-cacheProductsFeatures)
* [changeAccessories](#method-changeAccessories)
* [checkAccess](#method-checkAccess)
* [checkDefaultAttributes](#method-checkDefaultAttributes)
* [checkQty](#method-checkQty)
* [cleanPositions](#method-cleanPositions)
* [clearCache](#method-clearCache)
* [convertAndFormatPrice](#method-convertAndFormatPrice)
* [convertPrice](#method-convertPrice)
* [convertPriceWithCurrency](#method-convertPriceWithCurrency)
* [createLabels](#method-createLabels)
* [defineProductImage](#method-defineProductImage)
* [delete](#method-delete)
* [deleteAccessories](#method-deleteAccessories)
* [deleteAttachments](#method-deleteAttachments)
* [deleteAttributeCombinaison](#method-deleteAttributeCombinaison)
* [deleteAttributeCombination](#method-deleteAttributeCombination)
* [deleteAttributesImpacts](#method-deleteAttributesImpacts)
* [deleteCartProducts](#method-deleteCartProducts)
* [deleteCategories](#method-deleteCategories)
* [deleteCategory](#method-deleteCategory)
* [deleteCustomization](#method-deleteCustomization)
* [deleteDefaultAttributes](#method-deleteDefaultAttributes)
* [deleteDownload](#method-deleteDownload)
* [deleteFeatures](#method-deleteFeatures)
* [deleteFromAccessories](#method-deleteFromAccessories)
* [deleteFromCartRules](#method-deleteFromCartRules)
* [deleteFromSupplier](#method-deleteFromSupplier)
* [deleteImage](#method-deleteImage)
* [deleteImages](#method-deleteImages)
* [deleteItems](#method-deleteItems)
* [deletePack](#method-deletePack)
* [deleteProductAttributes](#method-deleteProductAttributes)
* [deleteProductFeatures](#method-deleteProductFeatures)
* [deleteProductSale](#method-deleteProductSale)
* [deleteSceneProducts](#method-deleteSceneProducts)
* [deleteSearchIndexes](#method-deleteSearchIndexes)
* [deleteSelection](#method-deleteSelection)
* [deleteTags](#method-deleteTags)
* [displayFieldName](#method-displayFieldName)
* [displayWtPrice](#method-displayWtPrice)
* [displayWtPriceWithCurrency](#method-displayWtPriceWithCurrency)
* [duplicate](#method-duplicate)
* [duplicateAccessories](#method-duplicateAccessories)
* [duplicateAttachments](#method-duplicateAttachments)
* [duplicateAttributes](#method-duplicateAttributes)
* [duplicateCustomizationFields](#method-duplicateCustomizationFields)
* [duplicateDownload](#method-duplicateDownload)
* [duplicateFeatures](#method-duplicateFeatures)
* [duplicateObject](#method-duplicateObject)
* [duplicateShops](#method-duplicateShops)
* [duplicateSpecificPrices](#method-duplicateSpecificPrices)
* [duplicateTags](#method-duplicateTags)
* [existsInDatabase](#method-existsInDatabase)
* [existsRefInDatabase](#method-existsRefInDatabase)
* [flushPriceCache](#method-flushPriceCache)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [generateMultipleCombinations](#method-generateMultipleCombinations)
* [getAccessories](#method-getAccessories)
* [getAccessoriesLight](#method-getAccessoriesLight)
* [getAccessoryById](#method-getAccessoryById)
* [getAllCustomizedDatas](#method-getAllCustomizedDatas)
* [getAnchor](#method-getAnchor)
* [getAssociatedShops](#method-getAssociatedShops)
* [getAttachments](#method-getAttachments)
* [getAttachmentsStatic](#method-getAttachmentsStatic)
* [getAttributeCombinaisons](#method-getAttributeCombinaisons)
* [getAttributeCombinations](#method-getAttributeCombinations)
* [getAttributeCombinationsById](#method-getAttributeCombinationsById)
* [getAttributesGroups](#method-getAttributesGroups)
* [getAttributesInformationsByProduct](#method-getAttributesInformationsByProduct)
* [getAttributesParams](#method-getAttributesParams)
* [getAttributesResume](#method-getAttributesResume)
* [getCarriers](#method-getCarriers)
* [getCategories](#method-getCategories)
* [getCombinationImages](#method-getCombinationImages)
* [getCover](#method-getCover)
* [getCoverWs](#method-getCoverWs)
* [getCustomizationFieldIds](#method-getCustomizationFieldIds)
* [getCustomizationFields](#method-getCustomizationFields)
* [getDefaultAttribute](#method-getDefaultAttribute)
* [getDefaultCategory](#method-getDefaultCategory)
* [getDefaultIdProductAttribute](#method-getDefaultIdProductAttribute)
* [getDefinition](#method-getDefinition)
* [getFeatures](#method-getFeatures)
* [getFeaturesStatic](#method-getFeaturesStatic)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getFrontFeatures](#method-getFrontFeatures)
* [getFrontFeaturesStatic](#method-getFrontFeaturesStatic)
* [getIdByEan13](#method-getIdByEan13)
* [getIdProductAttributeMostExpensive](#method-getIdProductAttributeMostExpensive)
* [getIdTaxRulesGroup](#method-getIdTaxRulesGroup)
* [getIdTaxRulesGroupByIdProduct](#method-getIdTaxRulesGroupByIdProduct)
* [getIdTaxRulesGroupMostUsed](#method-getIdTaxRulesGroupMostUsed)
* [getImages](#method-getImages)
* [getItemTable](#method-getItemTable)
* [getItems](#method-getItems)
* [getLink](#method-getLink)
* [getNewProducts](#method-getNewProducts)
* [getNoPackPrice](#method-getNoPackPrice)
* [getPacksTable](#method-getPacksTable)
* [getParentCategories](#method-getParentCategories)
* [getPrice](#method-getPrice)
* [getPriceStatic](#method-getPriceStatic)
* [getPriceWithoutReduct](#method-getPriceWithoutReduct)
* [getPricesDrop](#method-getPricesDrop)
* [getProductAttributePrice](#method-getProductAttributePrice)
* [getProductAttributesIds](#method-getProductAttributesIds)
* [getProductCategories](#method-getProductCategories)
* [getProductCategoriesFull](#method-getProductCategoriesFull)
* [getProductName](#method-getProductName)
* [getProductProperties](#method-getProductProperties)
* [getProducts](#method-getProducts)
* [getProductsProperties](#method-getProductsProperties)
* [getPublicPrice](#method-getPublicPrice)
* [getQuantity](#method-getQuantity)
* [getRandomSpecial](#method-getRandomSpecial)
* [getRealQuantity](#method-getRealQuantity)
* [getRequiredCustomizableFields](#method-getRequiredCustomizableFields)
* [getShopsByProduct](#method-getShopsByProduct)
* [getSimpleProducts](#method-getSimpleProducts)
* [getStockMvts](#method-getStockMvts)
* [getTags](#method-getTags)
* [getTaxCalculationMethod](#method-getTaxCalculationMethod)
* [getTaxesInformations](#method-getTaxesInformations)
* [getTaxesRate](#method-getTaxesRate)
* [getTranslationsFields](#method-getTranslationsFields)
* [getType](#method-getType)
* [getUrlRewriteInformations](#method-getUrlRewriteInformations)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWsAccessories](#method-getWsAccessories)
* [getWsCategories](#method-getWsCategories)
* [getWsCombinations](#method-getWsCombinations)
* [getWsDefaultCombination](#method-getWsDefaultCombination)
* [getWsImages](#method-getWsImages)
* [getWsManufacturerName](#method-getWsManufacturerName)
* [getWsPositionInCategory](#method-getWsPositionInCategory)
* [getWsProductBundle](#method-getWsProductBundle)
* [getWsProductFeatures](#method-getWsProductFeatures)
* [getWsProductOptionValues](#method-getWsProductOptionValues)
* [getWsStockAvailables](#method-getWsStockAvailables)
* [getWsTags](#method-getWsTags)
* [getWsType](#method-getWsType)
* [hasAllRequiredCustomizableFields](#method-hasAllRequiredCustomizableFields)
* [hasAttributes](#method-hasAttributes)
* [hasAttributesInOtherShops](#method-hasAttributesInOtherShops)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [idIsOnCategoryId](#method-idIsOnCategoryId)
* [initPricesComputation](#method-initPricesComputation)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isAvailableWhenOutOfStock](#method-isAvailableWhenOutOfStock)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isDiscounted](#method-isDiscounted)
* [isFeatureActive](#method-isFeatureActive)
* [isInStock](#method-isInStock)
* [isLangMultishop](#method-isLangMultishop)
* [isMultishop](#method-isMultishop)
* [isNew](#method-isNew)
* [isPack](#method-isPack)
* [isPacked](#method-isPacked)
* [loadStockData](#method-loadStockData)
* [makeTranslationFields](#method-makeTranslationFields)
* [noPackPrice](#method-noPackPrice)
* [priceCalculation](#method-priceCalculation)
* [productAttributeExists](#method-productAttributeExists)
* [reinjectQuantities](#method-reinjectQuantities)
* [resetEcoTax](#method-resetEcoTax)
* [save](#method-save)
* [searchByName](#method-searchByName)
* [setAdvancedStockManagement](#method-setAdvancedStockManagement)
* [setAvailableDate](#method-setAvailableDate)
* [setCarriers](#method-setCarriers)
* [setCoverWs](#method-setCoverWs)
* [setDefaultAttribute](#method-setDefaultAttribute)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [setGroupReduction](#method-setGroupReduction)
* [setWsAccessories](#method-setWsAccessories)
* [setWsCategories](#method-setWsCategories)
* [setWsCombinations](#method-setWsCombinations)
* [setWsDefaultCombination](#method-setWsDefaultCombination)
* [setWsProductFeatures](#method-setWsProductFeatures)
* [sqlStock](#method-sqlStock)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateAttribute](#method-updateAttribute)
* [updateCacheAttachment](#method-updateCacheAttachment)
* [updateCategories](#method-updateCategories)
* [updateDefaultAttribute](#method-updateDefaultAttribute)
* [updateIsVirtual](#method-updateIsVirtual)
* [updateLabels](#method-updateLabels)
* [updateMultishopTable](#method-updateMultishopTable)
* [updatePosition](#method-updatePosition)
* [updateProductAttribute](#method-updateProductAttribute)
* [updateQuantity](#method-updateQuantity)
* [updateQuantityProductWithAttributeQuantity](#method-updateQuantityProductWithAttributeQuantity)
* [updateWs](#method-updateWs)
* [useAdvancedStockManagement](#method-useAdvancedStockManagement)
* [usesAdvancedStockManagement](#method-usesAdvancedStockManagement)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)




Properties
----------


### <a name="property-$cacheIsPack"></a>$cacheIsPack

```php
protected mixed $cacheIsPack = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L30).


### <a name="property-$cacheIsPacked"></a>$cacheIsPacked

```php
protected mixed $cacheIsPacked = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L31).


### <a name="property-$cachePackItems"></a>$cachePackItems

```php
protected mixed $cachePackItems = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L29).


### <a name="property-$_cacheFeatures"></a>$_cacheFeatures

```php
protected mixed $_cacheFeatures = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L234).


### <a name="property-$_cart_quantity"></a>$_cart_quantity

```php
protected mixed $_cart_quantity = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L232).


### <a name="property-$_frontFeaturesCache"></a>$_frontFeaturesCache

```php
protected mixed $_frontFeaturesCache = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L235).


### <a name="property-$_incat"></a>$_incat

```php
protected mixed $_incat = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L231).


### <a name="property-$_prices"></a>$_prices

```php
protected mixed $_prices = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L229).


### <a name="property-$_pricesLevel2"></a>$_pricesLevel2

```php
protected mixed $_pricesLevel2 = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L230).


### <a name="property-$_taxCalculationMethod"></a>$_taxCalculationMethod

```php
public mixed $_taxCalculationMethod = null
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L228).


### <a name="property-$_tax_rules_group"></a>$_tax_rules_group

```php
protected mixed $_tax_rules_group = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L233).


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L165).


### <a name="property-$additional_shipping_cost"></a>$additional_shipping_cost

```php
public float $additional_shipping_cost
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L87).


### <a name="property-$advanced_stock_management"></a>$advanced_stock_management

```php
public boolean $advanced_stock_management
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L212).


### <a name="property-$available_date"></a>$available_date

```php
public string $available_date = '0000-00-00'
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L177).


### <a name="property-$available_for_order"></a>$available_for_order

```php
public boolean $available_for_order = true
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L174).


### <a name="property-$available_later"></a>$available_later

```php
public string $available_later
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L81).


### <a name="property-$available_now"></a>$available_now

```php
public string $available_now
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L78).


### <a name="property-$cacheStock"></a>$cacheStock

```php
protected array $cacheStock = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L239).


### <a name="property-$cache_default_attribute"></a>$cache_default_attribute

```php
public mixed $cache_default_attribute
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L221).


### <a name="property-$cache_has_attachments"></a>$cache_has_attachments

```php
public mixed $cache_has_attachments
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L219).


### <a name="property-$cache_is_pack"></a>$cache_is_pack

```php
public mixed $cache_is_pack
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L218).


### <a name="property-$category"></a>$category

```php
public string $category
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L226).


### <a name="property-$condition"></a>$condition

```php
public \enum $condition
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L180).


### <a name="property-$customizable"></a>$customizable

```php
public boolean $customizable
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L153).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L192).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L195).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'product', 'primary' => 'id_product', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_shop_default' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_manufacturer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'location' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 64), 'width' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'height' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'depth' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'quantity_discount' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13', 'size' => 13), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc', 'size' => 12), 'cache_is_pack' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'cache_has_attachments' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_virtual' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'id_category_default' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'id_tax_rules_group' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'on_sale' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'online_only' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'ecotax' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'minimal_quantity' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice', 'required' => true), 'wholesale_price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'unity' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isString'), 'unit_price_ratio' => array('type' => self::TYPE_FLOAT, 'shop' => true), 'additional_shipping_cost' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'customizable' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'text_fields' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'uploadable_files' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'active' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'redirect_type' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isString'), 'id_product_redirected' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'available_for_order' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'available_date' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDateFormat'), 'condition' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isGenericName', 'values' => array('new', 'used', 'refurbished'), 'default' => 'new'), 'show_price' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'indexed' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'visibility' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isProductVisibility', 'values' => array('both', 'catalog', 'search', 'none'), 'default' => 'both'), 'cache_default_attribute' => array('type' => self::TYPE_INT, 'shop' => true), 'advanced_stock_management' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDateFormat'), 'date_upd' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDateFormat'), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 128), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCatalogName', 'required' => true, 'size' => 128), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isString'), 'description_short' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isString'), 'available_now' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'available_later' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'IsGenericName', 'size' => 255)), 'associations' => array('manufacturer' => array('type' => self::HAS_ONE), 'supplier' => array('type' => self::HAS_ONE), 'default_category' => array('type' => self::HAS_ONE, 'field' => 'id_category_default', 'object' => 'Category'), 'tax_rules_group' => array('type' => self::HAS_ONE), 'categories' => array('type' => self::HAS_MANY, 'field' => 'id_category', 'object' => 'Category', 'association' => 'category_product'), 'stock_availables' => array('type' => self::HAS_MANY, 'field' => 'id_stock_available', 'object' => 'StockAvailable', 'association' => 'stock_availables')))
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L241).


### <a name="property-$depends_on_stock"></a>$depends_on_stock

```php
public mixed $depends_on_stock
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L214).


### <a name="property-$depth"></a>$depth

```php
public string $depth
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L126).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L66).


### <a name="property-$description_short"></a>$description_short

```php
public string $description_short
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L69).


### <a name="property-$ean13"></a>$ean13

```php
public string $ean13
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L132).


### <a name="property-$ecotax"></a>$ecotax

```php
public float $ecotax
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L108).


### <a name="property-$height"></a>$height

```php
public string $height
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L123).


### <a name="property-$id_category_default"></a>$id_category_default

```php
public integer $id_category_default
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L51).


### <a name="property-$id_color_default"></a>$id_color_default

```php
public mixed $id_color_default
```

We keep this variable for retrocompatibility for themes



* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L206).


### <a name="property-$id_manufacturer"></a>$id_manufacturer

```php
public integer $id_manufacturer
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L45).


### <a name="property-$id_product_redirected"></a>$id_product_redirected

```php
public boolean $id_product_redirected
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L171).


### <a name="property-$id_shop_default"></a>$id_shop_default

```php
public integer $id_shop_default
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L54).


### <a name="property-$id_supplier"></a>$id_supplier

```php
public integer $id_supplier
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L48).


### <a name="property-$id_tax_rules_group"></a>$id_tax_rules_group

```php
public mixed $id_tax_rules_group = 1
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L200).


### <a name="property-$indexed"></a>$indexed

```php
public boolean $indexed
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L186).


### <a name="property-$isFullyLoaded"></a>$isFullyLoaded

```php
public mixed $isFullyLoaded = false
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L216).


### <a name="property-$is_virtual"></a>$is_virtual

```php
public mixed $is_virtual
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L220).


### <a name="property-$link_rewrite"></a>$link_rewrite

```php
public string $link_rewrite
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L138).


### <a name="property-$location"></a>$location

```php
public string $location
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L117).


### <a name="property-$manufacturer_name"></a>$manufacturer_name

```php
public string $manufacturer_name
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L57).


### <a name="property-$meta_description"></a>$meta_description

```php
public string $meta_description
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L141).


### <a name="property-$meta_keywords"></a>$meta_keywords

```php
public string $meta_keywords
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L144).


### <a name="property-$meta_title"></a>$meta_title

```php
public string $meta_title
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L147).


### <a name="property-$minimal_quantity"></a>$minimal_quantity

```php
public integer $minimal_quantity = 1
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L75).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L63).


### <a name="property-$new"></a>$new

```php
public boolean $new = null
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L156).


### <a name="property-$on_sale"></a>$on_sale

```php
public boolean $on_sale = false
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L93).


### <a name="property-$online_only"></a>$online_only

```php
public boolean $online_only = false
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L96).


### <a name="property-$out_of_stock"></a>$out_of_stock

```php
public mixed $out_of_stock
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L213).


### <a name="property-$price"></a>$price

```php
public float $price
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L84).


### <a name="property-$producPropertiesCache"></a>$producPropertiesCache

```php
protected mixed $producPropertiesCache = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L236).


### <a name="property-$quantity"></a>$quantity

```php
public integer $quantity
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L72).


### <a name="property-$quantity_discount"></a>$quantity_discount

```php
public boolean $quantity_discount
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L150).


### <a name="property-$redirect_type"></a>$redirect_type

```php
public boolean $redirect_type = ''
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L168).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L111).


### <a name="property-$show_price"></a>$show_price

```php
public boolean $show_price = true
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L183).


### <a name="property-$supplier_name"></a>$supplier_name

```php
public string $supplier_name
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L60).


### <a name="property-$supplier_reference"></a>$supplier_reference

```php
public string $supplier_reference
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L114).


### <a name="property-$tags"></a>$tags

```php
public mixed $tags
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L198).


### <a name="property-$tax_name"></a>$tax_name

```php
public string $tax_name
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L39).


### <a name="property-$tax_rate"></a>$tax_rate

```php
public string $tax_rate
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L42).


### <a name="property-$text_fields"></a>$text_fields

```php
public integer $text_fields
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L162).


### <a name="property-$unit_price"></a>$unit_price

```php
public float $unit_price
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L102).


### <a name="property-$unit_price_ratio"></a>$unit_price_ratio

```php
public float $unit_price_ratio
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L105).


### <a name="property-$unity"></a>$unity

```php
public string $unity = null
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L99).


### <a name="property-$upc"></a>$upc

```php
public string $upc
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L135).


### <a name="property-$uploadable_files"></a>$uploadable_files

```php
public integer $uploadable_files
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L159).


### <a name="property-$visibility"></a>$visibility

```php
public string $visibility
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L189).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectMethods' => array('add' => 'addWs', 'update' => 'updateWs'), 'objectNodeNames' => 'products', 'fields' => array('id_manufacturer' => array('xlink_resource' => 'manufacturers'), 'id_supplier' => array('xlink_resource' => 'suppliers'), 'id_category_default' => array('xlink_resource' => 'categories'), 'new' => array(), 'cache_default_attribute' => array(), 'id_default_image' => array('getter' => 'getCoverWs', 'setter' => 'setCoverWs', 'xlink_resource' => array('resourceName' => 'images', 'subResourceName' => 'products')), 'id_default_combination' => array('getter' => 'getWsDefaultCombination', 'setter' => 'setWsDefaultCombination', 'xlink_resource' => array('resourceName' => 'combinations')), 'id_tax_rules_group' => array('xlink_resource' => array('resourceName' => 'tax_rules_group')), 'position_in_category' => array('getter' => 'getWsPositionInCategory', 'setter' => false), 'manufacturer_name' => array('getter' => 'getWsManufacturerName', 'setter' => false), 'quantity' => array('getter' => false, 'setter' => false), 'type' => array('getter' => 'getWsType', 'setter' => false)), 'associations' => array('categories' => array('resource' => 'category', 'fields' => array('id' => array('required' => true))), 'images' => array('resource' => 'image', 'fields' => array('id' => array())), 'combinations' => array('resource' => 'combinations', 'fields' => array('id' => array('required' => true))), 'product_option_values' => array('resource' => 'product_options_values', 'fields' => array('id' => array('required' => true))), 'product_features' => array('resource' => 'product_feature', 'fields' => array('id' => array('required' => true), 'id_feature_value' => array('required' => true, 'xlink_resource' => 'product_feature_values'))), 'tags' => array('resource' => 'tag', 'fields' => array('id' => array('required' => true))), 'stock_availables' => array('resource' => 'stock_available', 'fields' => array('id' => array('required' => true), 'id_product_attribute' => array('required' => true)), 'setter' => false), 'accessories' => array('resource' => 'product', 'fields' => array('id' => array('required' => true, 'xlink_resource' => 'product'))), 'product_bundle' => array('resource' => 'products', 'fields' => array('id' => array('required' => true), 'quantity' => array()))))
```





* Visibility: **protected**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L315).


### <a name="property-$weight"></a>$weight

```php
public string $weight
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L129).


### <a name="property-$wholesale_price"></a>$wholesale_price

```php
public float $wholesale_price
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L90).


### <a name="property-$width"></a>$width

```php
public string $width
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L120).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L140).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L130).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L80).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L65).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L95).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L85).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L100).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L90).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L105).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L63).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L54).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L57).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L59).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L61).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L75).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L116).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L119).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L70).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L110).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L135).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ProductCore::__construct($id_product, $full, $id_lang, $id_shop, \Context $context)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 442](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L442)


#### Arguments
* $id_product **mixed**
* $full **mixed**
* $id_lang **mixed**
* $id_shop **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-_checkLabelField"></a>_checkLabelField

```php
mixed ProductCore::_checkLabelField($field, $value)
```





* Visibility: **protected**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3984](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3984)


#### Arguments
* $field **mixed**
* $value **mixed**



### <a name="method-_createLabel"></a>_createLabel

```php
mixed ProductCore::_createLabel($languages, $type)
```





* Visibility: **protected**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4065](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4065)


#### Arguments
* $languages **mixed**
* $type **mixed**



### <a name="method-_deleteOldLabels"></a>_deleteOldLabels

```php
mixed ProductCore::_deleteOldLabels()
```





* Visibility: **protected**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3994](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3994)




### <a name="method-_getAttributeImageAssociations"></a>_getAttributeImageAssociations

```php
array ProductCore::_getAttributeImageAssociations(integer $id_product_attribute)
```

Get product attribute image associations



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3386](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3386)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-_getCustomizationFieldsNLabels"></a>_getCustomizationFieldsNLabels

```php
mixed ProductCore::_getCustomizationFieldsNLabels($product_id)
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3542](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3542)


#### Arguments
* $product_id **mixed**



### <a name="method-_getProductIdByDate"></a>_getProductIdByDate

```php
mixed ProductCore::_getProductIdByDate($beginning, $ending, \Context $context, $with_combination)
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2068](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2068)


#### Arguments
* $beginning **mixed**
* $ending **mixed**
* $context **[Context](class.ContextCore.md)**
* $with_combination **mixed**



### <a name="method-add"></a>add

```php
mixed ProductCore::add($autodate, $null_values)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 490](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L490)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addAttribute"></a>addAttribute

```php
mixed ProductCore::addAttribute(float $price, float $weight, $unit_impact, float $ecotax, integer $id_images, string $reference, string $ean13, boolean $default, string $location, $upc, integer $minimal_quantity, array $id_shop_list)
```

Add a product attribute



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1421](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1421)


#### Arguments
* $price **float** - Additional price
* $weight **float** - Additional weight
* $unit_impact **mixed**
* $ecotax **float** - Additional ecotax
* $id_images **integer** - Image ids
* $reference **string** - Reference
* $ean13 **string** - Ean-13 barcode
* $default **boolean** - Is default attribute for product
* $location **string** - Location
* $upc **mixed**
* $minimal_quantity **integer** - Minimal quantity to add to cart
* $id_shop_list **array**



### <a name="method-addAttributeCombinaison"></a>addAttributeCombinaison

```php
array ProductCore::addAttributeCombinaison(integer $id_product_attribute, array $attributes)
```

Add a product attributes combinaison



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1652](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1652)


#### Arguments
* $id_product_attribute **integer** - Product attribute id
* $attributes **array** - Attributes to forge combinaison



### <a name="method-addAttributeCombinationMultiple"></a>addAttributeCombinationMultiple

```php
mixed ProductCore::addAttributeCombinationMultiple($id_attributes, $combinations)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1664](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1664)


#### Arguments
* $id_attributes **mixed**
* $combinations **mixed**



### <a name="method-addCombinationEntity"></a>addCombinationEntity

```php
mixed ProductCore::addCombinationEntity($wholesale_price, $price, $weight, $unit_impact, $ecotax, integer $quantity, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity, array $id_shop_list)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1192](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1192)


#### Arguments
* $wholesale_price **mixed**
* $price **mixed**
* $weight **mixed**
* $unit_impact **mixed**
* $ecotax **mixed**
* $quantity **integer** - DEPRECATED
* $id_images **mixed**
* $reference **mixed**
* $id_supplier **mixed**
* $ean13 **mixed**
* $default **mixed**
* $location **mixed**
* $upc **mixed**
* $minimal_quantity **mixed**
* $id_shop_list **array**



### <a name="method-addCustomizationPrice"></a>addCustomizationPrice

```php
mixed ProductCore::addCustomizationPrice($products, $customized_datas)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3927](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3927)


#### Arguments
* $products **mixed**
* $customized_datas **mixed**



### <a name="method-addFeatureProductImport"></a>addFeatureProductImport

```php
mixed ProductCore::addFeatureProductImport($id_product, $id_feature, $id_feature_value)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3192](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3192)


#### Arguments
* $id_product **mixed**
* $id_feature **mixed**
* $id_feature_value **mixed**



### <a name="method-addFeaturesCustomToDB"></a>addFeaturesCustomToDB

```php
mixed ProductCore::addFeaturesCustomToDB($id_value, $lang, $cust)
```

Add new feature to product



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3171](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3171)


#### Arguments
* $id_value **mixed**
* $lang **mixed**
* $cust **mixed**



### <a name="method-addFeaturesToDB"></a>addFeaturesToDB

```php
mixed ProductCore::addFeaturesToDB($id_feature, $id_value, $cust)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3177](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3177)


#### Arguments
* $id_feature **mixed**
* $id_value **mixed**
* $cust **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1146](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1146)


#### Arguments
* $fields **mixed**



### <a name="method-addItem"></a>addItem

```php
boolean PackCore::addItem(integer $id_product, integer $id_item, integer $qty)
```

Add an item to the pack



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L211)


#### Arguments
* $id_product **integer**
* $id_item **integer**
* $qty **integer**



### <a name="method-addProductAttribute"></a>addProductAttribute

```php
mixed ProductCore::addProductAttribute($price, $weight, $unit_impact, $ecotax, $quantity, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity)
```

addProductAttribute is deprecated

The quantity params now set StockAvailable for the current shop with the specified quantity
The supplier_reference params now set the supplier reference of the default supplier of the product if possible

* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1130](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1130)


#### Arguments
* $price **mixed**
* $weight **mixed**
* $unit_impact **mixed**
* $ecotax **mixed**
* $quantity **mixed**
* $id_images **mixed**
* $reference **mixed**
* $id_supplier **mixed**
* $ean13 **mixed**
* $default **mixed**
* $location **mixed**
* $upc **mixed**
* $minimal_quantity **mixed**



### <a name="method-addProductAttributeMultiple"></a>addProductAttributeMultiple

```php
mixed ProductCore::addProductAttributeMultiple($attributes, $set_default)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1210](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1210)


#### Arguments
* $attributes **mixed**
* $set_default **mixed**



### <a name="method-addStockMvt"></a>addStockMvt

```php
boolean ProductCore::addStockMvt(integer $quantity, integer $id_reason, integer $id_product_attribute, integer $id_order, integer $id_employee)
```

Add a stock movement for current product

Since 1.5, this method only permit to add/remove available quantities of the current product in the current shop

* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4273](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4273)


#### Arguments
* $quantity **integer**
* $id_reason **integer** - 
useless

* $id_product_attribute **integer**
* $id_order **integer** - 
useless

* $id_employee **integer** - 
useless




### <a name="method-addSupplierReference"></a>addSupplierReference

```php
mixed ProductCore::addSupplierReference(integer $id_supplier, integer $id_product_attribute, string $supplier_reference, float $price, integer $id_currency)
```

Sets Supplier Reference



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1309](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1309)


#### Arguments
* $id_supplier **integer**
* $id_product_attribute **integer**
* $supplier_reference **string**
* $price **float**
* $id_currency **integer**



### <a name="method-addToCategories"></a>addToCategories

```php
boolean ProductCore::addToCategories(mixed $categories)
```

addToCategories add this product to the category/ies if not exists.



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 806](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L806)


#### Arguments
* $categories **mixed** - id_category or array of id_category



### <a name="method-addWs"></a>addWs

```php
mixed ProductCore::addWs($autodate, $null_values)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5006](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5006)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1193](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1193)


#### Arguments
* $id_shops **integer|array**



### <a name="method-cacheFrontFeatures"></a>cacheFrontFeatures

```php
mixed ProductCore::cacheFrontFeatures($product_ids, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3248](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3248)


#### Arguments
* $product_ids **mixed**
* $id_lang **mixed**



### <a name="method-cacheProductsFeatures"></a>cacheProductsFeatures

```php
mixed ProductCore::cacheProductsFeatures($product_ids)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3224](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3224)


#### Arguments
* $product_ids **mixed**



### <a name="method-changeAccessories"></a>changeAccessories

```php
mixed ProductCore::changeAccessories(array $accessories_id)
```

Link accessories with product



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3159](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3159)


#### Arguments
* $accessories_id **array** - Accessories ids



### <a name="method-checkAccess"></a>checkAccess

```php
mixed ProductCore::checkAccess($id_customer)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4238](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4238)


#### Arguments
* $id_customer **mixed**



### <a name="method-checkDefaultAttributes"></a>checkDefaultAttributes

```php
mixed ProductCore::checkDefaultAttributes()
```

Check if there is no default attribute and create it if not



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2985](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2985)




### <a name="method-checkQty"></a>checkQty

```php
boolean ProductCore::checkQty(integer $qty)
```

Check product availability



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2966](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2966)


#### Arguments
* $qty **integer** - Quantity desired



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed ProductCore::cleanPositions($id_category)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 580](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L580)


#### Arguments
* $id_category **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1160](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1160)


#### Arguments
* $all **mixed**



### <a name="method-convertAndFormatPrice"></a>convertAndFormatPrice

```php
mixed ProductCore::convertAndFormatPrice($price, $currency, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2737](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2737)


#### Arguments
* $price **mixed**
* $currency **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-convertPrice"></a>convertPrice

```php
string ProductCore::convertPrice(array $params, $smarty)
```

Display price with right format and currency



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2832](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2832)


#### Arguments
* $params **array** - Params
* $smarty **mixed** - Smarty object



### <a name="method-convertPriceWithCurrency"></a>convertPriceWithCurrency

```php
\Ambigous ProductCore::convertPriceWithCurrency(array $params, object $smarty)
```

Convert price with currency



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2844](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2844)


#### Arguments
* $params **array**
* $smarty **object** - DEPRECATED



### <a name="method-createLabels"></a>createLabels

```php
mixed ProductCore::createLabels($uploadable_files, $text_fields)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4091](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4091)


#### Arguments
* $uploadable_files **mixed**
* $text_fields **mixed**



### <a name="method-defineProductImage"></a>defineProductImage

```php
mixed ProductCore::defineProductImage($row, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3652](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3652)


#### Arguments
* $row **mixed**
* $id_lang **mixed**



### <a name="method-delete"></a>delete

```php
mixed ProductCore::delete()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 718](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L718)




### <a name="method-deleteAccessories"></a>deleteAccessories

```php
mixed ProductCore::deleteAccessories()
```

Delete product accessories



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3062](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3062)




### <a name="method-deleteAttachments"></a>deleteAttachments

```php
array ProductCore::deleteAttachments()
```

Delete product attachments



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1548](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1548)




### <a name="method-deleteAttributeCombinaison"></a>deleteAttributeCombinaison

```php
mixed ProductCore::deleteAttributeCombinaison(integer $id_product_attribute)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5192](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5192)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-deleteAttributeCombination"></a>deleteAttributeCombination

```php
array ProductCore::deleteAttributeCombination(integer $id_product_attribute)
```

Delete a product attributes combination



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1686](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1686)


#### Arguments
* $id_product_attribute **integer** - Product attribute id



### <a name="method-deleteAttributesImpacts"></a>deleteAttributesImpacts

```php
\Deletion ProductCore::deleteAttributesImpacts()
```

Delete product attributes impacts



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1510](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1510)




### <a name="method-deleteCartProducts"></a>deleteCartProducts

```php
array ProductCore::deleteCartProducts()
```

Delete product from cart



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 946](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L946)




### <a name="method-deleteCategories"></a>deleteCategories

```php
array ProductCore::deleteCategories(boolean $clean_positions)
```

Delete all association to category where product is indexed



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 913](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L913)


#### Arguments
* $clean_positions **boolean** - clean category positions after deletion



### <a name="method-deleteCategory"></a>deleteCategory

```php
boolean ProductCore::deleteCategory(mixed $id_category, mixed $clean_positions)
```

deleteCategory delete this product from the category $id_category



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L890)


#### Arguments
* $id_category **mixed**
* $clean_positions **mixed**



### <a name="method-deleteCustomization"></a>deleteCustomization

```php
array ProductCore::deleteCustomization()
```

Delete product customizations



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1565](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1565)




### <a name="method-deleteDefaultAttributes"></a>deleteDefaultAttributes

```php
mixed ProductCore::deleteDefaultAttributes()
```

Del all default attributes for product



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1246](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1246)




### <a name="method-deleteDownload"></a>deleteDownload

```php
boolean ProductCore::deleteDownload()
```

Remove all downloadable files for product and its attributes



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5166](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5166)




### <a name="method-deleteFeatures"></a>deleteFeatures

```php
mixed ProductCore::deleteFeatures()
```

Delete features



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1710](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1710)




### <a name="method-deleteFromAccessories"></a>deleteFromAccessories

```php
mixed ProductCore::deleteFromAccessories()
```

Delete product from other products accessories



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3072](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3072)




### <a name="method-deleteFromCartRules"></a>deleteFromCartRules

```php
mixed ProductCore::deleteFromCartRules()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 789](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L789)




### <a name="method-deleteFromSupplier"></a>deleteFromSupplier

```php
mixed ProductCore::deleteFromSupplier()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 795](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L795)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage($force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1319](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1319)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteImages"></a>deleteImages

```php
boolean ProductCore::deleteImages()
```

Delete product images from database



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 956](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L956)




### <a name="method-deleteItems"></a>deleteItems

```php
mixed PackCore::deleteItems($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L196)


#### Arguments
* $id_product **mixed**



### <a name="method-deletePack"></a>deletePack

```php
array ProductCore::deletePack()
```

Delete product pack details



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1586](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1586)




### <a name="method-deleteProductAttributes"></a>deleteProductAttributes

```php
array ProductCore::deleteProductAttributes()
```

Delete product attributes



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1492](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1492)




### <a name="method-deleteProductFeatures"></a>deleteProductFeatures

```php
array ProductCore::deleteProductFeatures()
```

Delete product features



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1523](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1523)




### <a name="method-deleteProductSale"></a>deleteProductSale

```php
array ProductCore::deleteProductSale()
```

Delete product sales



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1600](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1600)




### <a name="method-deleteSceneProducts"></a>deleteSceneProducts

```php
array ProductCore::deleteSceneProducts()
```

Delete product in its scenes



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1613](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1613)




### <a name="method-deleteSearchIndexes"></a>deleteSearchIndexes

```php
array ProductCore::deleteSearchIndexes()
```

Delete product indexed words



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1626](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1626)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed ProductCore::deleteSelection($products)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 771](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L771)


#### Arguments
* $products **mixed**



### <a name="method-deleteTags"></a>deleteTags

```php
array ProductCore::deleteTags()
```

Delete products tags entries



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 935](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L935)




### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L939)


#### Arguments
* $field **mixed**
* $class **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-displayWtPrice"></a>displayWtPrice

```php
mixed ProductCore::displayWtPrice($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2849](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2849)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-displayWtPriceWithCurrency"></a>displayWtPriceWithCurrency

```php
\Ambigous ProductCore::displayWtPriceWithCurrency(array $params, $smarty)
```

Display WT price with currency



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2861](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2861)


#### Arguments
* $params **array**
* $smarty **mixed**



### <a name="method-duplicate"></a>duplicate

```php
mixed PackCore::duplicate($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L218)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-duplicateAccessories"></a>duplicateAccessories

```php
mixed ProductCore::duplicateAccessories($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3398](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3398)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-duplicateAttachments"></a>duplicateAttachments

```php
mixed ProductCore::duplicateAttachments($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3465](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3465)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-duplicateAttributes"></a>duplicateAttributes

```php
mixed ProductCore::duplicateAttributes(integer $id_product_old, integer $id_product_new)
```

Duplicate attributes when duplicating a product



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3338](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3338)


#### Arguments
* $id_product_old **integer** - Old product id
* $id_product_new **integer** - New product id



### <a name="method-duplicateCustomizationFields"></a>duplicateCustomizationFields

```php
mixed ProductCore::duplicateCustomizationFields($old_product_id, $product_id)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3586](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3586)


#### Arguments
* $old_product_id **mixed**
* $product_id **mixed**



### <a name="method-duplicateDownload"></a>duplicateDownload

```php
mixed ProductCore::duplicateDownload($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3432](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3432)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-duplicateFeatures"></a>duplicateFeatures

```php
mixed ProductCore::duplicateFeatures(integer $id_product_old, $id_product_new)
```

Duplicate features when duplicating a product



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3495](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3495)


#### Arguments
* $id_product_old **integer** - Old product id
* $id_product_new **mixed**



### <a name="method-duplicateObject"></a>duplicateObject

```php
\new ObjectModelCore::duplicateObject()
```

Duplicate current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 528](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L528)




### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1237](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1237)


#### Arguments
* $id **mixed**



### <a name="method-duplicateSpecificPrices"></a>duplicateSpecificPrices

```php
mixed ProductCore::duplicateSpecificPrices($old_product_id, $product_id)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3575](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3575)


#### Arguments
* $old_product_id **mixed**
* $product_id **mixed**



### <a name="method-duplicateTags"></a>duplicateTags

```php
mixed ProductCore::duplicateTags($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3416](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3416)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1356](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1356)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-existsRefInDatabase"></a>existsRefInDatabase

```php
boolean ProductCore::existsRefInDatabase($reference)
```

Checks if reference exists



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4699](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4699)


#### Arguments
* $reference **mixed**



### <a name="method-flushPriceCache"></a>flushPriceCache

```php
mixed ProductCore::flushPriceCache()
```

This method allows to flush price cache



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5069](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5069)




### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L335)


#### Arguments
* $type **integer** - FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L381)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-generateMultipleCombinations"></a>generateMultipleCombinations

```php
mixed ProductCore::generateMultipleCombinations($combinations, $attributes)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1149](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1149)


#### Arguments
* $combinations **mixed**
* $attributes **mixed**



### <a name="method-getAccessories"></a>getAccessories

```php
array ProductCore::getAccessories(integer $id_lang, $active, \Context $context)
```

Get product accessories



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3108](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3108)


#### Arguments
* $id_lang **integer** - Language id
* $active **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getAccessoriesLight"></a>getAccessoriesLight

```php
array ProductCore::getAccessoriesLight(integer $id_lang, integer $id_product, \Context $context)
```

Get product accessories (only names)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3084](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3084)


#### Arguments
* $id_lang **integer** - Language id
* $id_product **integer** - Product id
* $context **[Context](class.ContextCore.md)**



### <a name="method-getAccessoryById"></a>getAccessoryById

```php
mixed ProductCore::getAccessoryById($accessory_id)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3149](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3149)


#### Arguments
* $accessory_id **mixed**



### <a name="method-getAllCustomizedDatas"></a>getAllCustomizedDatas

```php
mixed ProductCore::getAllCustomizedDatas($id_cart, $id_lang, $only_in_cart)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3883](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3883)


#### Arguments
* $id_cart **mixed**
* $id_lang **mixed**
* $only_in_cart **mixed**



### <a name="method-getAnchor"></a>getAnchor

```php
string ProductCore::getAnchor(integer $id_product_attribute)
```

Get the combination url anchor of the product



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4947](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4947)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Get the list of associated id_shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1222](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1222)




### <a name="method-getAttachments"></a>getAttachments

```php
mixed ProductCore::getAttachments($id_lang)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3874](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3874)


#### Arguments
* $id_lang **mixed**



### <a name="method-getAttachmentsStatic"></a>getAttachmentsStatic

```php
mixed ProductCore::getAttachmentsStatic($id_lang, $id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3864](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3864)


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**



### <a name="method-getAttributeCombinaisons"></a>getAttributeCombinaisons

```php
mixed ProductCore::getAttributeCombinaisons(integer $id_lang)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5181](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5181)


#### Arguments
* $id_lang **integer**



### <a name="method-getAttributeCombinations"></a>getAttributeCombinations

```php
array ProductCore::getAttributeCombinations(integer $id_lang)
```

Get all available product attributes combinations



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1799](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1799)


#### Arguments
* $id_lang **integer** - Language id



### <a name="method-getAttributeCombinationsById"></a>getAttributeCombinationsById

```php
array ProductCore::getAttributeCombinationsById(integer $id_product_attribute, integer $id_lang)
```

Get product attribute combination by id_product_attribute



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1843](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1843)


#### Arguments
* $id_product_attribute **integer**
* $id_lang **integer** - Language id



### <a name="method-getAttributesGroups"></a>getAttributesGroups

```php
array ProductCore::getAttributesGroups(integer $id_lang)
```

Get all available attribute groups



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3031](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3031)


#### Arguments
* $id_lang **integer** - Language id



### <a name="method-getAttributesInformationsByProduct"></a>getAttributesInformationsByProduct

```php
mixed ProductCore::getAttributesInformationsByProduct(integer $id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4840](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4840)


#### Arguments
* $id_product **integer**



### <a name="method-getAttributesParams"></a>getAttributesParams

```php
array ProductCore::getAttributesParams(integer $id_product, $id_product_attribute)
```

Get label by lang and value by lang too



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4732](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4732)


#### Arguments
* $id_product **integer**
* $id_product_attribute **mixed**



### <a name="method-getAttributesResume"></a>getAttributesResume

```php
array ProductCore::getAttributesResume(integer $id_lang, $attribute_value_separator, $attribute_separator)
```

Get all available product attributes resume



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1744](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1744)


#### Arguments
* $id_lang **integer** - Language id
* $attribute_value_separator **mixed**
* $attribute_separator **mixed**



### <a name="method-getCarriers"></a>getCarriers

```php
mixed ProductCore::getCarriers()
```

Gets carriers assigned to the product



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2341](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2341)




### <a name="method-getCategories"></a>getCategories

```php
array ProductCore::getCategories()
```

getCategories return an array of categories which this product belongs to



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2333](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2333)




### <a name="method-getCombinationImages"></a>getCombinationImages

```php
mixed ProductCore::getCombinationImages($id_lang)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1880](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1880)


#### Arguments
* $id_lang **mixed**



### <a name="method-getCover"></a>getCover

```php
array ProductCore::getCover($id_product, \Context $context)
```

Get product cover image



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2401](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2401)


#### Arguments
* $id_product **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getCoverWs"></a>getCoverWs

```php
integer ProductCore::getCoverWs()
```

Webservice getter : get virtual field id_default_image in category



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4621](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4621)




### <a name="method-getCustomizationFieldIds"></a>getCustomizationFieldIds

```php
mixed ProductCore::getCustomizationFieldIds()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4164](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4164)




### <a name="method-getCustomizationFields"></a>getCustomizationFields

```php
mixed ProductCore::getCustomizationFields($id_lang)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4141](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4141)


#### Arguments
* $id_lang **mixed**



### <a name="method-getDefaultAttribute"></a>getDefaultAttribute

```php
integer ProductCore::getDefaultAttribute($id_product, $minimum_quantity)
```

Get the default attribute for a product



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 605](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L605)


#### Arguments
* $id_product **mixed**
* $minimum_quantity **mixed**



### <a name="method-getDefaultCategory"></a>getDefaultCategory

```php
mixed ProductCore::getDefaultCategory()
```

get the default category according to the shop



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5138](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5138)




### <a name="method-getDefaultIdProductAttribute"></a>getDefaultIdProductAttribute

```php
mixed ProductCore::getDefaultIdProductAttribute()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2804](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2804)




### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1462](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1462)


#### Arguments
* $class **string** - Name of object
* $field **string** - Name of field if we want the definition of one field only



### <a name="method-getFeatures"></a>getFeatures

```php
array ProductCore::getFeatures()
```

Select all features for the object



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3206](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3206)




### <a name="method-getFeaturesStatic"></a>getFeaturesStatic

```php
mixed ProductCore::getFeaturesStatic($id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3211](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3211)


#### Arguments
* $id_product **mixed**



### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang($field_name, null $id_lang)
```

Return the field value for the specified language if the field is multilang, else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1569](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1569)


#### Arguments
* $field_name **mixed**
* $id_lang **null**



### <a name="method-getFields"></a>getFields

```php
array ObjectModelCore::getFields()
```

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval.

..)

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L263)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L300)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1138](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1138)


#### Arguments
* $all **mixed**



### <a name="method-getFieldsShop"></a>getFieldsShop

```php
array ProductCore::getFieldsShop()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L481)




### <a name="method-getFrontFeatures"></a>getFrontFeatures

```php
mixed ProductCore::getFrontFeatures($id_lang)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3859](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3859)


#### Arguments
* $id_lang **mixed**



### <a name="method-getFrontFeaturesStatic"></a>getFrontFeaturesStatic

```php
mixed ProductCore::getFrontFeaturesStatic($id_lang, $id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3840](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3840)


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**



### <a name="method-getIdByEan13"></a>getIdByEan13

```php
integer ProductCore::getIdByEan13(string $ean13)
```

For a given ean13 reference, returns the corresponding id



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5249](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5249)


#### Arguments
* $ean13 **string**



### <a name="method-getIdProductAttributeMostExpensive"></a>getIdProductAttributeMostExpensive

```php
mixed ProductCore::getIdProductAttributeMostExpensive()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2789](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2789)




### <a name="method-getIdTaxRulesGroup"></a>getIdTaxRulesGroup

```php
mixed ProductCore::getIdTaxRulesGroup()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4338](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4338)




### <a name="method-getIdTaxRulesGroupByIdProduct"></a>getIdTaxRulesGroupByIdProduct

```php
mixed ProductCore::getIdTaxRulesGroupByIdProduct($id_product, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4343](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4343)


#### Arguments
* $id_product **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getIdTaxRulesGroupMostUsed"></a>getIdTaxRulesGroupMostUsed

```php
mixed ProductCore::getIdTaxRulesGroupMostUsed()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5226](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5226)




### <a name="method-getImages"></a>getImages

```php
array ProductCore::getImages(integer $id_lang, \Context $context)
```

Get product images and legends



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2382](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2382)


#### Arguments
* $id_lang **integer** - Language id for multilingual legends
* $context **[Context](class.ContextCore.md)**



### <a name="method-getItemTable"></a>getItemTable

```php
mixed PackCore::getItemTable($id_product, $id_lang, $full)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L122)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**
* $full **mixed**



### <a name="method-getItems"></a>getItems

```php
mixed PackCore::getItems($id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L86)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-getLink"></a>getLink

```php
mixed ProductCore::getLink(\Context $context)
```

Get the link of the product page of this product



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3630](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3630)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-getNewProducts"></a>getNewProducts

```php
array ProductCore::getNewProducts(integer $id_lang, $page_number, $nb_products, $count, $order_by, $order_way, \Context $context)
```

Get new products



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1943](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1943)


#### Arguments
* $id_lang **integer** - Language id
* $page_number **mixed**
* $nb_products **mixed**
* $count **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getNoPackPrice"></a>getNoPackPrice

```php
mixed ProductCore::getNoPackPrice()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4233](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4233)




### <a name="method-getPacksTable"></a>getPacksTable

```php
mixed PackCore::getPacksTable($id_product, $id_lang, $full, $limit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L158)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**
* $full **mixed**
* $limit **mixed**



### <a name="method-getParentCategories"></a>getParentCategories

```php
array ProductCore::getParentCategories(integer $id_lang)
```

Get list of parent categories



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5082](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5082)


#### Arguments
* $id_lang **integer**



### <a name="method-getPrice"></a>getPrice

```php
float ProductCore::getPrice(boolean $tax, integer $id_product_attribute, integer $decimals, integer $divisor, $only_reduc, $usereduc, $quantity)
```

Get product price
Same as static function getPriceStatic, no need to specify product id



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2775](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2775)


#### Arguments
* $tax **boolean** - With taxes or not (optional)
* $id_product_attribute **integer** - Product attribute id (optional)
* $decimals **integer** - Number of decimals (optional)
* $divisor **integer** - Util when paying many time without fees (optional)
* $only_reduc **mixed**
* $usereduc **mixed**
* $quantity **mixed**



### <a name="method-getPriceStatic"></a>getPriceStatic

```php
float ProductCore::getPriceStatic(integer $id_product, boolean $usetax, integer $id_product_attribute, integer $decimals, integer $divisor, boolean $only_reduc, boolean $usereduc, integer $quantity, $force_associated_tax, integer $id_customer, integer $id_cart, integer $id_address, $specific_price_output, boolean $with_ecotax, $use_group_reduction, \Context $context, $use_customer_price)
```

Get product price



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2435](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2435)


#### Arguments
* $id_product **integer** - Product id
* $usetax **boolean** - With taxes or not (optional)
* $id_product_attribute **integer** - Product attribute id (optional).
If set to false, do not apply the combination price impact. NULL does apply the default combination price impact.
* $decimals **integer** - Number of decimals (optional)
* $divisor **integer** - Useful when paying many time without fees (optional)
* $only_reduc **boolean** - Returns only the reduction amount
* $usereduc **boolean** - Set if the returned amount will include reduction
* $quantity **integer** - Required for quantity discount application (default value: 1)
* $force_associated_tax **mixed**
* $id_customer **integer** - Customer ID (for customer group reduction)
* $id_cart **integer** - Cart ID. Required when the cookie is not accessible (e.g., inside a payment module, a cron task...)
* $id_address **integer** - Customer address ID. Required for price (tax included) calculation regarding the guest localization
* $specific_price_output **mixed**
* $with_ecotax **boolean** - insert ecotax in price output.
* $use_group_reduction **mixed**
* $context **[Context](class.ContextCore.md)**
* $use_customer_price **mixed**



### <a name="method-getPriceWithoutReduct"></a>getPriceWithoutReduct

```php
mixed ProductCore::getPriceWithoutReduct($notax, $id_product_attribute)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2820](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2820)


#### Arguments
* $notax **mixed**
* $id_product_attribute **mixed**



### <a name="method-getPricesDrop"></a>getPricesDrop

```php
array ProductCore::getPricesDrop(integer $id_lang, $page_number, $nb_products, boolean $count, $order_by, $order_way, $beginning, $ending, \Context $context)
```

Get prices drop



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2180](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2180)


#### Arguments
* $id_lang **integer** - Language id
* $page_number **mixed**
* $nb_products **mixed**
* $count **boolean** - Only in order to get total number (optional)
* $order_by **mixed**
* $order_way **mixed**
* $beginning **mixed**
* $ending **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getProductAttributePrice"></a>getProductAttributePrice

```php
mixed ProductCore::getProductAttributePrice($id_product_attribute)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 977](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L977)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-getProductAttributesIds"></a>getProductAttributesIds

```php
array ProductCore::getProductAttributesIds(integer $id_product, $shop_only)
```

Get all product attributes ids



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4716](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4716)


#### Arguments
* $id_product **integer** - the id of the product
* $shop_only **mixed**



### <a name="method-getProductCategories"></a>getProductCategories

```php
array ProductCore::getProductCategories($id_product)
```

getProductCategories return an array of categories which this product belongs to



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2291](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2291)


#### Arguments
* $id_product **mixed**



### <a name="method-getProductCategoriesFull"></a>getProductCategoriesFull

```php
mixed ProductCore::getProductCategoriesFull($id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2307](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2307)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-getProductName"></a>getProductName

```php
string ProductCore::getProductName(integer $id_product, integer $id_product_attribute, integer $id_lang)
```

Gets the name of a given product, in the given lang



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4969](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4969)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $id_lang **integer** - Optional



### <a name="method-getProductProperties"></a>getProductProperties

```php
mixed ProductCore::getProductProperties($id_lang, $row, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3661](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3661)


#### Arguments
* $id_lang **mixed**
* $row **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getProducts"></a>getProducts

```php
array ProductCore::getProducts(integer $id_lang, integer $start, integer $limit, string $order_by, string $order_way, $id_category, $only_active, \Context $context)
```

Get all available products



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 992](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L992)


#### Arguments
* $id_lang **integer** - Language id
* $start **integer** - Start number
* $limit **integer** - Number of products to return
* $order_by **string** - Field for ordering
* $order_way **string** - Way for ordering (ASC or DESC)
* $id_category **mixed**
* $only_active **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getProductsProperties"></a>getProductsProperties

```php
mixed ProductCore::getProductsProperties($id_lang, $query_result)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3822](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3822)


#### Arguments
* $id_lang **mixed**
* $query_result **mixed**



### <a name="method-getPublicPrice"></a>getPublicPrice

```php
mixed ProductCore::getPublicPrice($tax, $id_product_attribute, $decimals, $divisor, $only_reduc, $usereduc, $quantity)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2781](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2781)


#### Arguments
* $tax **mixed**
* $id_product_attribute **mixed**
* $decimals **mixed**
* $divisor **mixed**
* $only_reduc **mixed**
* $usereduc **mixed**
* $quantity **mixed**



### <a name="method-getQuantity"></a>getQuantity

```php
integer ProductCore::getQuantity(integer $id_product, integer $id_product_attribute, $cache_is_pack)
```

Get available product quantities



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2873](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2873)


#### Arguments
* $id_product **integer** - Product id
* $id_product_attribute **integer** - Product attribute id (optional)
* $cache_is_pack **mixed**



### <a name="method-getRandomSpecial"></a>getRandomSpecial

```php
array ProductCore::getRandomSpecial(integer $id_lang, $beginning, $ending, \Context $context)
```

Get a random special



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2095](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2095)


#### Arguments
* $id_lang **integer** - Language id
* $beginning **mixed**
* $ending **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getRealQuantity"></a>getRealQuantity

```php
integer ProductCore::getRealQuantity(integer $id_product, integer $id_product_attribute, integer $id_warehouse, integer $id_shop)
```

For a given product, returns its real quantity



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5032](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5032)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_warehouse **integer**
* $id_shop **integer**



### <a name="method-getRequiredCustomizableFields"></a>getRequiredCustomizableFields

```php
mixed ProductCore::getRequiredCustomizableFields()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4174](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4174)




### <a name="method-getShopsByProduct"></a>getShopsByProduct

```php
mixed ProductCore::getShopsByProduct($id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5153](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5153)


#### Arguments
* $id_product **mixed**



### <a name="method-getSimpleProducts"></a>getSimpleProducts

```php
mixed ProductCore::getSimpleProducts($id_lang, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1040](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1040)


#### Arguments
* $id_lang **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getStockMvts"></a>getStockMvts

```php
mixed ProductCore::getStockMvts($id_lang)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4293](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4293)


#### Arguments
* $id_lang **mixed**



### <a name="method-getTags"></a>getTags

```php
mixed ProductCore::getTags($id_lang)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3637](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3637)


#### Arguments
* $id_lang **mixed**



### <a name="method-getTaxCalculationMethod"></a>getTaxCalculationMethod

```php
mixed ProductCore::getTaxCalculationMethod($id_customer)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 526](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L526)


#### Arguments
* $id_customer **mixed**



### <a name="method-getTaxesInformations"></a>getTaxesInformations

```php
mixed ProductCore::getTaxesInformations($row, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3802](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3802)


#### Arguments
* $row **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getTaxesRate"></a>getTaxesRate

```php
\the ProductCore::getTaxesRate(\Address $address)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4361](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4361)


#### Arguments
* $address **[Address](class.AddressCore.md)**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 769](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L769)


#### Arguments
* $fields_array **mixed**



### <a name="method-getType"></a>getType

```php
integer ProductCore::getType()
```

Get the product type (simple, virtual, pack)



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5204](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5204)




### <a name="method-getUrlRewriteInformations"></a>getUrlRewriteInformations

```php
mixed ProductCore::getUrlRewriteInformations($id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4324](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4324)


#### Arguments
* $id_product **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $class)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L148)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1080](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1080)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
mixed ObjectModelCore::getWebserviceParameters($ws_params_attribute_name)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1006](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1006)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-getWsAccessories"></a>getWsAccessories

```php
array ProductCore::getWsAccessories()
```

Webservice getter : get product accessories ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4481](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4481)




### <a name="method-getWsCategories"></a>getWsCategories

```php
array ProductCore::getWsCategories()
```

Webservice getter : get category ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4436](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4436)




### <a name="method-getWsCombinations"></a>getWsCombinations

```php
array ProductCore::getWsCombinations()
```

Webservice getter : get combination ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4514](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4514)




### <a name="method-getWsDefaultCombination"></a>getWsDefaultCombination

```php
integer ProductCore::getWsDefaultCombination()
```

Webservice getter : get virtual field default combination



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4415](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4415)




### <a name="method-getWsImages"></a>getWsImages

```php
array ProductCore::getWsImages()
```

Webservice getter : get image ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4649](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4649)




### <a name="method-getWsManufacturerName"></a>getWsManufacturerName

```php
mixed ProductCore::getWsManufacturerName()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4675](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4675)




### <a name="method-getWsPositionInCategory"></a>getWsPositionInCategory

```php
integer ProductCore::getWsPositionInCategory()
```

Webservice getter : get virtual field position in category



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4605](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4605)




### <a name="method-getWsProductBundle"></a>getWsProductBundle

```php
mixed ProductCore::getWsProductBundle()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5275](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5275)




### <a name="method-getWsProductFeatures"></a>getWsProductFeatures

```php
array ProductCore::getWsProductFeatures()
```

Webservice getter : get product features association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4377](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4377)




### <a name="method-getWsProductOptionValues"></a>getWsProductOptionValues

```php
array ProductCore::getWsProductOptionValues()
```

Webservice getter : get product option ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4590](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4590)




### <a name="method-getWsStockAvailables"></a>getWsStockAvailables

```php
mixed ProductCore::getWsStockAvailables()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4659](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4659)




### <a name="method-getWsTags"></a>getWsTags

```php
mixed ProductCore::getWsTags()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4666](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4666)




### <a name="method-getWsType"></a>getWsType

```php
mixed ProductCore::getWsType()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5265](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5265)




### <a name="method-hasAllRequiredCustomizableFields"></a>hasAllRequiredCustomizableFields

```php
mixed ProductCore::hasAllRequiredCustomizableFields(\Context $context)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4186](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4186)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-hasAttributes"></a>hasAttributes

```php
integer ProductCore::hasAttributes()
```

Check if product has attributes combinations



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1923](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1923)




### <a name="method-hasAttributesInOtherShops"></a>hasAttributesInOtherShops

```php
mixed ProductCore::hasAttributesInOtherShops()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5216](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5216)




### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Check if there is more than one entries in associated shop table for current entity



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1262](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1262)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1394](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1394)


#### Arguments
* $data **array**
* $id_lang **integer**



### <a name="method-hydrateCollection"></a>hydrateCollection

```php
array ObjectModelCore::hydrateCollection(string $class, array $datas, integer $id_lang)
```

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1413](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1413)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-idIsOnCategoryId"></a>idIsOnCategoryId

```php
boolean ProductCore::idIsOnCategoryId(integer $id_product, array $categories)
```

Checks if the product is in at least one of the submited categories



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4214](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4214)


#### Arguments
* $id_product **integer**
* $categories **array** - array of category arrays



### <a name="method-initPricesComputation"></a>initPricesComputation

```php
mixed ProductCore::initPricesComputation($id_customer)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 513](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L513)


#### Arguments
* $id_customer **mixed**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1175](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1175)


#### Arguments
* $id_shop **integer**



### <a name="method-isAvailableWhenOutOfStock"></a>isAvailableWhenOutOfStock

```php
mixed ProductCore::isAvailableWhenOutOfStock($out_of_stock)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2953](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2953)


#### Arguments
* $out_of_stock **mixed**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string $table, boolean $has_active_column)
```

This method is allow to know if a entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1374](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1374)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isDiscounted"></a>isDiscounted

```php
mixed ProductCore::isDiscounted($id_product, $quantity, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2746](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2746)


#### Arguments
* $id_product **mixed**
* $quantity **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean PackCore::isFeatureActive()
```

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L232)




### <a name="method-isInStock"></a>isInStock

```php
mixed PackCore::isInStock($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L106)


#### Arguments
* $id_product **mixed**



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1274](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1274)




### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1269](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1269)




### <a name="method-isNew"></a>isNew

```php
mixed ProductCore::isNew()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1059](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1059)




### <a name="method-isPack"></a>isPack

```php
boolean PackCore::isPack($id_product)
```

Is product a pack?



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L40)


#### Arguments
* $id_product **mixed**



### <a name="method-isPacked"></a>isPacked

```php
boolean PackCore::isPacked($id_product)
```

Is product in a pack?



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L63)


#### Arguments
* $id_product **mixed**



### <a name="method-loadStockData"></a>loadStockData

```php
mixed ProductCore::loadStockData()
```

Fill the variables used for stock management



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5100](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5100)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L785)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-noPackPrice"></a>noPackPrice

```php
mixed PackCore::noPackPrice($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L76)


#### Arguments
* $id_product **mixed**



### <a name="method-priceCalculation"></a>priceCalculation

```php
float ProductCore::priceCalculation(integer $id_shop, integer $id_product, integer $id_product_attribute, integer $id_country, integer $id_state, $zipcode, integer $id_currency, integer $id_group, integer $quantity, boolean $use_tax, integer $decimals, boolean $only_reduc, boolean $use_reduc, boolean $with_ecotax, $specific_price, $use_group_reduction, $id_customer, $use_customer_price, $id_cart, $real_quantity)
```

Price calculation / Get product price



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2567](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2567)


#### Arguments
* $id_shop **integer** - Shop id
* $id_product **integer** - Product id
* $id_product_attribute **integer** - Product attribute id
* $id_country **integer** - Country id
* $id_state **integer** - State id
* $zipcode **mixed**
* $id_currency **integer** - Currency id
* $id_group **integer** - Group id
* $quantity **integer** - Quantity Required for Specific prices : quantity discount application
* $use_tax **boolean** - with (1) or without (0) tax
* $decimals **integer** - Number of decimals returned
* $only_reduc **boolean** - Returns only the reduction amount
* $use_reduc **boolean** - Set if the returned amount will include reduction
* $with_ecotax **boolean** - insert ecotax in price output.
* $specific_price **mixed**
* $use_group_reduction **mixed**
* $id_customer **mixed**
* $use_customer_price **mixed**
* $id_cart **mixed**
* $real_quantity **mixed**



### <a name="method-productAttributeExists"></a>productAttributeExists

```php
mixed ProductCore::productAttributeExists($attributes_list, $current_product_attribute, \Context $context, $all_shops, $return_id)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1077](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1077)


#### Arguments
* $attributes_list **mixed**
* $current_product_attribute **mixed**
* $context **[Context](class.ContextCore.md)**
* $all_shops **mixed**
* $return_id **mixed**



### <a name="method-reinjectQuantities"></a>reinjectQuantities

```php
mixed ProductCore::reinjectQuantities()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2946](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2946)




### <a name="method-resetEcoTax"></a>resetEcoTax

```php
mixed ProductCore::resetEcoTax()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4680](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4680)




### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L425)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-searchByName"></a>searchByName

```php
array ProductCore::searchByName(integer $id_lang, string $query, \Context $context)
```

Admin panel product search



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3285](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L3285)


#### Arguments
* $id_lang **integer** - Language id
* $query **string** - Search query
* $context **[Context](class.ContextCore.md)**



### <a name="method-setAdvancedStockManagement"></a>setAdvancedStockManagement

```php
mixed ProductCore::setAdvancedStockManagement($value)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5122](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5122)


#### Arguments
* $value **mixed**



### <a name="method-setAvailableDate"></a>setAvailableDate

```php
mixed ProductCore::setAvailableDate($available_date)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 660](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L660)


#### Arguments
* $available_date **mixed**



### <a name="method-setCarriers"></a>setCarriers

```php
mixed ProductCore::setCarriers($carrier_list)
```

Sets carriers assigned to the product



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2355](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2355)


#### Arguments
* $carrier_list **mixed**



### <a name="method-setCoverWs"></a>setCoverWs

```php
boolean ProductCore::setCoverWs($id_image)
```

Webservice setter : set virtual field id_default_image in category



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4632](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4632)


#### Arguments
* $id_image **mixed**



### <a name="method-setDefaultAttribute"></a>setDefaultAttribute

```php
mixed ProductCore::setDefaultAttribute($id_product_attribute)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1253](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1253)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1500](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1500)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1595](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1595)


#### Arguments
* $fields **array**



### <a name="method-setGroupReduction"></a>setGroupReduction

```php
mixed ProductCore::setGroupReduction()
```

Set Group reduction if needed



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4690](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4690)




### <a name="method-setWsAccessories"></a>setWsAccessories

```php
mixed ProductCore::setWsAccessories($accessories)
```

Webservice setter : set product accessories ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4499](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4499)


#### Arguments
* $accessories **mixed** - product ids



### <a name="method-setWsCategories"></a>setWsCategories

```php
mixed ProductCore::setWsCategories($category_ids)
```

Webservice setter : set category ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4453](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4453)


#### Arguments
* $category_ids **mixed** - category ids



### <a name="method-setWsCombinations"></a>setWsCombinations

```php
mixed ProductCore::setWsCombinations($combinations)
```

Webservice setter : set combination ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4531](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4531)


#### Arguments
* $combinations **mixed** - combination ids



### <a name="method-setWsDefaultCombination"></a>setWsDefaultCombination

```php
mixed ProductCore::setWsDefaultCombination($id_combination)
```

Webservice setter : set virtual field default combination



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4425](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4425)


#### Arguments
* $id_combination **mixed** - id default combination



### <a name="method-setWsProductFeatures"></a>setWsProductFeatures

```php
boolean ProductCore::setWsProductFeatures($product_features)
```

Webservice setter : set product features association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4402](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4402)


#### Arguments
* $product_features **mixed**



### <a name="method-sqlStock"></a>sqlStock

```php
string ProductCore::sqlStock($product_alias, $product_attribute, $inner_join, \Shop $shop)
```

Create JOIN query with 'stock_available' table



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2895](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2895)


#### Arguments
* $product_alias **mixed**
* $product_attribute **mixed**
* $inner_join **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-toggleStatus"></a>toggleStatus

```php
mixed ProductCore::toggleStatus()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 699](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L699)




### <a name="method-update"></a>update

```php
mixed ProductCore::update($null_values)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 505](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L505)


#### Arguments
* $null_values **mixed**



### <a name="method-updateAttribute"></a>updateAttribute

```php
array ProductCore::updateAttribute(integer $id_product_attribute, float $wholesale_price, float $price, float $weight, float $unit, float $ecotax, $id_images, string $reference, string $ean13, integer $default, $location, string $upc, string $minimal_quantity, $available_date, $update_all_fields, array $id_shop_list)
```

Update a product attribute



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1358](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1358)


#### Arguments
* $id_product_attribute **integer** - Product attribute id
* $wholesale_price **float** - Wholesale price
* $price **float** - Additional price
* $weight **float** - Additional weight
* $unit **float**
* $ecotax **float** - Additional ecotax
* $id_images **mixed**
* $reference **string** - Reference
* $ean13 **string** - Ean-13 barcode
* $default **integer** - Default On
* $location **mixed**
* $upc **string** - Upc barcode
* $minimal_quantity **string** - Minimal quantity
* $available_date **mixed**
* $update_all_fields **mixed**
* $id_shop_list **array**



### <a name="method-updateCacheAttachment"></a>updateCacheAttachment

```php
mixed ProductCore::updateCacheAttachment($id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1530](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1530)


#### Arguments
* $id_product **mixed**



### <a name="method-updateCategories"></a>updateCategories

```php
array ProductCore::updateCategories($categories, boolean $keeping_current_pos)
```

Update categories to index product into



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 856](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L856)


#### Arguments
* $categories **mixed**
* $keeping_current_pos **boolean** - (deprecated, no more used)



### <a name="method-updateDefaultAttribute"></a>updateDefaultAttribute

```php
mixed ProductCore::updateDefaultAttribute($id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1266](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1266)


#### Arguments
* $id_product **mixed**



### <a name="method-updateIsVirtual"></a>updateIsVirtual

```php
mixed ProductCore::updateIsVirtual($id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 670](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L670)


#### Arguments
* $id_product **mixed**



### <a name="method-updateLabels"></a>updateLabels

```php
mixed ProductCore::updateLabels()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4107](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L4107)




### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Update a table and splits the common datas and the shop datas



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1289](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1289)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - Only executed for common table



### <a name="method-updatePosition"></a>updatePosition

```php
mixed ProductCore::updatePosition(boolean $way, integer $position)
```

Move a product inside its category



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 540](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L540)


#### Arguments
* $way **boolean** - Up (1)  or Down (0)
* $position **integer** - return boolean Update result



### <a name="method-updateProductAttribute"></a>updateProductAttribute

```php
mixed ProductCore::updateProductAttribute($id_product_attribute, $wholesale_price, $price, $weight, $unit, $ecotax, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity, $available_date)
```

Update a product attribute



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1286](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1286)


#### Arguments
* $id_product_attribute **mixed**
* $wholesale_price **mixed**
* $price **mixed**
* $weight **mixed**
* $unit **mixed**
* $ecotax **mixed**
* $id_images **mixed**
* $reference **mixed**
* $id_supplier **mixed**
* $ean13 **mixed**
* $default **mixed**
* $location **mixed**
* $upc **mixed**
* $minimal_quantity **mixed**
* $available_date **mixed**



### <a name="method-updateQuantity"></a>updateQuantity

```php
mixed ProductCore::updateQuantity()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2929](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L2929)




### <a name="method-updateQuantityProductWithAttributeQuantity"></a>updateQuantityProductWithAttributeQuantity

```php
mixed ProductCore::updateQuantityProductWithAttributeQuantity()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1473](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L1473)




### <a name="method-updateWs"></a>updateWs

```php
mixed ProductCore::updateWs($null_values)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5014](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5014)


#### Arguments
* $null_values **mixed**



### <a name="method-useAdvancedStockManagement"></a>useAdvancedStockManagement

```php
mixed ProductCore::useAdvancedStockManagement()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5113](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L5113)




### <a name="method-usesAdvancedStockManagement"></a>usesAdvancedStockManagement

```php
boolean PackCore::usesAdvancedStockManagement(integer $id_product)
```

For a given pack, tells if it has at least one product using the advanced stock management



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Pack.php#L259)


#### Arguments
* $id_product **integer** - id_pack



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 954](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L954)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 960](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L960)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
mixed ProductCore::validateField($field, $value, $id_lang)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 693](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L693)


#### Arguments
* $field **mixed**
* $value **mixed**
* $id_lang **mixed**



### <a name="method-validateFields"></a>validateFields

```php
boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 823](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L823)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
mixed ProductCore::validateFieldsLang($die, $error_return)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 680](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/Product.php#L680)


#### Arguments
* $die **mixed**
* $error_return **mixed**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
mixed ObjectModelCore::validateFieldsRequiredDatabase($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/ObjectModel.php#L1116)


#### Arguments
* $htmlentities **mixed**


