Class LanguageCore
=====================





* Class name: LanguageCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Language.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L28)


Contents
--------


### Properties

* [$_LANGUAGES](#property-$_LANGUAGES)
* [$_cache_language_installation](#property-$_cache_language_installation)
* [$_checkedLangs](#property-$_checkedLangs)
* [$active](#property-$active)
* [$countActiveLanguages](#property-$countActiveLanguages)
* [$date_format_full](#property-$date_format_full)
* [$date_format_lite](#property-$date_format_lite)
* [$definition](#property-$definition)
* [$id](#property-$id)
* [$is_rtl](#property-$is_rtl)
* [$iso_code](#property-$iso_code)
* [$language_code](#property-$language_code)
* [$name](#property-$name)
* [$translationsFilesAndVars](#property-$translationsFilesAndVars)
* [$webserviceParameters](#property-$webserviceParameters)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$table](#property-$table)
* [$tables](#property-$tables)

### Methods

* [__construct](#method-__construct)
* [_copyNoneFlag](#method-_copyNoneFlag)
* [_generateFiles](#method-_generateFiles)
* [_getThemesList](#method-_getThemesList)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [checkAndAddLanguage](#method-checkAndAddLanguage)
* [checkFiles](#method-checkFiles)
* [checkFilesWithIsoCode](#method-checkFilesWithIsoCode)
* [clearCache](#method-clearCache)
* [copyLanguageData](#method-copyLanguageData)
* [countActiveLanguages](#method-countActiveLanguages)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getDefinition](#method-getDefinition)
* [getEntity](#method-getEntity)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFilesList](#method-getFilesList)
* [getIdByIso](#method-getIdByIso)
* [getIsoById](#method-getIsoById)
* [getIsoIds](#method-getIsoIds)
* [getLanguage](#method-getLanguage)
* [getLanguageCodeByIso](#method-getLanguageCodeByIso)
* [getLanguages](#method-getLanguages)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isInstalled](#method-isInstalled)
* [isLangMultishop](#method-isLangMultishop)
* [isMultiLanguageActivated](#method-isMultiLanguageActivated)
* [loadLanguages](#method-loadLanguages)
* [loadUpdateSQL](#method-loadUpdateSQL)
* [makeTranslationFields](#method-makeTranslationFields)
* [moveToIso](#method-moveToIso)
* [recurseDeleteDir](#method-recurseDeleteDir)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$_LANGUAGES"></a>$_LANGUAGES

```php
protected mixed $_LANGUAGES
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Language.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L73).


### <a name="property-$_cache_language_installation"></a>$_cache_language_installation

```php
private mixed $_cache_language_installation = null
```





* Visibility: **private**
* This property is **static**.
* Source: [classes/Language.php line 713](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L713).


### <a name="property-$_checkedLangs"></a>$_checkedLangs

```php
protected array $_checkedLangs
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Language.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L72).


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Language.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L51).


### <a name="property-$countActiveLanguages"></a>$countActiveLanguages

```php
protected mixed $countActiveLanguages
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Language.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L74).


### <a name="property-$date_format_full"></a>$date_format_full

```php
public string $date_format_full = 'Y-m-d H:i:s'
```





* Visibility: **public**
* Source: [classes/Language.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L45).


### <a name="property-$date_format_lite"></a>$date_format_lite

```php
public string $date_format_lite = 'Y-m-d'
```





* Visibility: **public**
* Source: [classes/Language.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L42).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'lang', 'primary' => 'id_lang', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageIsoCode', 'required' => true, 'size' => 2), 'language_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageCode', 'size' => 5), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_rtl' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_format_lite' => array('type' => self::TYPE_STRING, 'validate' => 'isPhpDateFormat', 'required' => true, 'size' => 32), 'date_format_full' => array('type' => self::TYPE_STRING, 'validate' => 'isPhpDateFormat', 'required' => true, 'size' => 32)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Language.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L56).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Language.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L30).


### <a name="property-$is_rtl"></a>$is_rtl

```php
public boolean $is_rtl = false
```





* Visibility: **public**
* Source: [classes/Language.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L48).


### <a name="property-$iso_code"></a>$iso_code

```php
public string $iso_code
```





* Visibility: **public**
* Source: [classes/Language.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L36).


### <a name="property-$language_code"></a>$language_code

```php
public string $language_code
```





* Visibility: **public**
* Source: [classes/Language.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L39).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Language.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L33).


### <a name="property-$translationsFilesAndVars"></a>$translationsFilesAndVars

```php
protected mixed $translationsFilesAndVars = array('fields' => '_FIELDS', 'errors' => '_ERRORS', 'admin' => '_LANGADM', 'pdf' => '_LANGPDF')
```





* Visibility: **protected**
* Source: [classes/Language.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L81).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectNodeName' => 'language', 'objectsNodeName' => 'languages')
```





* Visibility: **protected**
* Source: [classes/Language.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L76).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L122).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L72).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L57).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L87).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L92).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L82).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L97).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L51).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L53).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L67).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L108).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L111).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L62).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L102).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed LanguageCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Language.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L88)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-_copyNoneFlag"></a>_copyNoneFlag

```php
mixed LanguageCore::_copyNoneFlag($id)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Language.php line 708](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L708)


#### Arguments
* $id **mixed**



### <a name="method-_generateFiles"></a>_generateFiles

```php
mixed LanguageCore::_generateFiles($newIso)
```

Generate traslations files



* Visibility: **private**
* Source: [classes/Language.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L109)


#### Arguments
* $newIso **mixed**



### <a name="method-_getThemesList"></a>_getThemesList

```php
array LanguageCore::_getThemesList()
```

Return an array with themes and thumbnails



* Visibility: **private**
* Source: [classes/Language.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L166)




### <a name="method-add"></a>add

```php
mixed LanguageCore::add($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/Language.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L176)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 961](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L961)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1009](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1009)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-checkAndAddLanguage"></a>checkAndAddLanguage

```php
mixed LanguageCore::checkAndAddLanguage($iso_code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 650](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L650)


#### Arguments
* $iso_code **mixed**



### <a name="method-checkFiles"></a>checkFiles

```php
mixed LanguageCore::checkFiles()
```





* Visibility: **public**
* Source: [classes/Language.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L216)




### <a name="method-checkFilesWithIsoCode"></a>checkFilesWithIsoCode

```php
mixed LanguageCore::checkFilesWithIsoCode(mixed $iso_code)
```

This functions checks if every files exists for the language $iso_code.

Concerned files are those located in translations/$iso_code/
and translations/mails/$iso_code .

* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L230)


#### Arguments
* $iso_code **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L975)


#### Arguments
* $all **mixed**



### <a name="method-copyLanguageData"></a>copyLanguageData

```php
mixed LanguageCore::copyLanguageData($from, $to)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 586](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L586)


#### Arguments
* $from **mixed**
* $to **mixed**



### <a name="method-countActiveLanguages"></a>countActiveLanguages

```php
mixed LanguageCore::countActiveLanguages()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 726](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L726)




### <a name="method-delete"></a>delete

```php
mixed LanguageCore::delete()
```





* Visibility: **public**
* Source: [classes/Language.php line 413](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L413)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1079](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1079)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed LanguageCore::deleteSelection($selection)
```





* Visibility: **public**
* Source: [classes/Language.php line 486](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L486)


#### Arguments
* $selection **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $className, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 740](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L740)


#### Arguments
* $field **mixed**
* $className **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1049](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1049)


#### Arguments
* $id **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1113)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L272)


#### Arguments
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L319)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getDefinition"></a>getDefinition

```php
mixed ObjectModelCore::getDefinition($class, $field)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1209](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1209)


#### Arguments
* $class **mixed**
* $field **mixed**



### <a name="method-getEntity"></a>getEntity

```php
mixed ObjectModelCore::getEntity($entity)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1269](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1269)


#### Arguments
* $entity **mixed**



### <a name="method-getFields"></a>getFields

```php
array LanguageCore::getFields()
```





* Visibility: **public**
* Source: [classes/Language.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L97)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L249)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 953](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L953)


#### Arguments
* $all **mixed**



### <a name="method-getFilesList"></a>getFilesList

```php
mixed LanguageCore::getFilesList($iso_from, $theme_from, $iso_to, $theme_to, $select, $check, $modules)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L241)


#### Arguments
* $iso_from **mixed**
* $theme_from **mixed**
* $iso_to **mixed**
* $theme_to **mixed**
* $select **mixed**
* $check **mixed**
* $modules **mixed**



### <a name="method-getIdByIso"></a>getIdByIso

```php
integer LanguageCore::getIdByIso(string $iso_code)
```

Return id from iso code



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L559)


#### Arguments
* $iso_code **string** - Iso code



### <a name="method-getIsoById"></a>getIsoById

```php
string LanguageCore::getIsoById(integer $id_lang)
```

Return iso code from id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 546](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L546)


#### Arguments
* $id_lang **integer** - Language ID



### <a name="method-getIsoIds"></a>getIsoIds

```php
array LanguageCore::getIsoIds($active)
```

Return array (id_lang, iso_code)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 581](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L581)


#### Arguments
* $active **mixed**



### <a name="method-getLanguage"></a>getLanguage

```php
mixed LanguageCore::getLanguage($id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 533](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L533)


#### Arguments
* $id_lang **mixed**



### <a name="method-getLanguageCodeByIso"></a>getLanguageCodeByIso

```php
mixed LanguageCore::getLanguageCodeByIso($iso_code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 567](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L567)


#### Arguments
* $iso_code **mixed**



### <a name="method-getLanguages"></a>getLanguages

```php
array LanguageCore::getLanguages(boolean $active, $id_shop)
```

Return available languages



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 518](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L518)


#### Arguments
* $active **boolean** - Select only active languages
* $id_shop **mixed**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fieldsArray)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 589](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L589)


#### Arguments
* $fieldsArray **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $className)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L130)


#### Arguments
* $className **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 929](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L929)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
mixed ObjectModelCore::getWebserviceParameters($wsParamsAttributeName)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 799](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L799)


#### Arguments
* $wsParamsAttributeName **mixed**



### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1148)


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
* Source: [classes/ObjectModel.php line 1167](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1167)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-isAssociatedToGroupShop"></a>isAssociatedToGroupShop

```php
boolean ObjectModelCore::isAssociatedToGroupShop(integer $id_group_shop)
```

Check if current object is associated to a group shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1035](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1035)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 990](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L990)


#### Arguments
* $id_shop **integer**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string $table, boolean $has_active_column)
```

This method is allow to know if a entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1131)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isInstalled"></a>isInstalled

```php
mixed LanguageCore::isInstalled($iso_code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 714](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L714)


#### Arguments
* $iso_code **mixed**



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1069](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1069)




### <a name="method-isMultiLanguageActivated"></a>isMultiLanguageActivated

```php
boolean LanguageCore::isMultiLanguageActivated()
```

Check if more on than one language is activated



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 739](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L739)




### <a name="method-loadLanguages"></a>loadLanguages

```php
mixed LanguageCore::loadLanguages()
```

Load all languages in memory for caching



* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 614](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L614)




### <a name="method-loadUpdateSQL"></a>loadUpdateSQL

```php
boolean LanguageCore::loadUpdateSQL()
```

loadUpdateSQL will create default lang values when you create a new lang, based on default id lang



* Visibility: **public**
* Source: [classes/Language.php line 358](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L358)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fieldsArray, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 605](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L605)


#### Arguments
* $fields **mixed**
* $fieldsArray **mixed**
* $id_language **mixed**



### <a name="method-moveToIso"></a>moveToIso

```php
mixed LanguageCore::moveToIso($newIso)
```

Move translations files after editiing language iso code



* Visibility: **public**
* Source: [classes/Language.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L126)


#### Arguments
* $newIso **mixed**



### <a name="method-recurseDeleteDir"></a>recurseDeleteDir

```php
mixed LanguageCore::recurseDeleteDir($dir)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Language.php line 394](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L394)


#### Arguments
* $dir **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L360)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1224](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1224)




### <a name="method-toggleStatus"></a>toggleStatus

```php
mixed LanguageCore::toggleStatus()
```





* Visibility: **public**
* Source: [classes/Language.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L200)




### <a name="method-update"></a>update

```php
mixed LanguageCore::update($nullValues)
```





* Visibility: **public**
* Source: [classes/Language.php line 631](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Language.php#L631)


#### Arguments
* $nullValues **mixed**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L753)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 759](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L759)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 704](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L704)


#### Arguments
* $field **string** - Field name
* $value **mixed** - Field value
* $id_lang **integer**



### <a name="method-validateFields"></a>validateFields

```php
boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L643)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
boolean|string ObjectModelCore::validateFieldsLang(boolean $die, boolean $error_return)
```

Check for multilingual fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L669)


#### Arguments
* $die **boolean**
* $error_return **boolean**


