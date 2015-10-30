Class ModuleCore
=====================





* Class name: ModuleCore
* This is an **abstract** class
* Source: [classes/module/Module.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L27)


Contents
--------

### Constants

* [CACHE_FILE_CUSTOMER_MODULES_LIST](#constant-CACHE_FILE_CUSTOMER_MODULES_LIST)
* [CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST](#constant-CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST)
* [CACHE_FILE_MODULES_LIST](#constant-CACHE_FILE_MODULES_LIST)
* [CACHE_FILE_MUST_HAVE_MODULES_LIST](#constant-CACHE_FILE_MUST_HAVE_MODULES_LIST)
* [CACHE_FILE_TAB_MODULES_LIST](#constant-CACHE_FILE_TAB_MODULES_LIST)

### Properties

* [$_INSTANCE](#property-$_INSTANCE)
* [$_confirmations](#property-$_confirmations)
* [$_errors](#property-$_errors)
* [$_generate_config_xml_mode](#property-$_generate_config_xml_mode)
* [$_lang](#property-$_lang)
* [$_path](#property-$_path)
* [$active](#property-$active)
* [$author](#property-$author)
* [$cache_permissions](#property-$cache_permissions)
* [$classInModule](#property-$classInModule)
* [$context](#property-$context)
* [$current_subtemplate](#property-$current_subtemplate)
* [$database_version](#property-$database_version)
* [$dependencies](#property-$dependencies)
* [$description](#property-$description)
* [$displayName](#property-$displayName)
* [$id](#property-$id)
* [$identifier](#property-$identifier)
* [$l_cache](#property-$l_cache)
* [$limited_countries](#property-$limited_countries)
* [$local_path](#property-$local_path)
* [$modules_cache](#property-$modules_cache)
* [$name](#property-$name)
* [$need_instance](#property-$need_instance)
* [$ps_versions_compliancy](#property-$ps_versions_compliancy)
* [$registered_version](#property-$registered_version)
* [$smarty](#property-$smarty)
* [$tab](#property-$tab)
* [$table](#property-$table)
* [$update_translations_after_install](#property-$update_translations_after_install)
* [$version](#property-$version)
* [$warning](#property-$warning)

### Methods

* [__construct](#method-__construct)
* [_clearCache](#method-_clearCache)
* [_generateConfigXml](#method-_generateConfigXml)
* [_getApplicableTemplateDir](#method-_getApplicableTemplateDir)
* [_isTemplateOverloaded](#method-_isTemplateOverloaded)
* [_isTemplateOverloadedStatic](#method-_isTemplateOverloadedStatic)
* [addOverride](#method-addOverride)
* [adminDisplayInformation](#method-adminDisplayInformation)
* [adminDisplayWarning](#method-adminDisplayWarning)
* [cleanPositions](#method-cleanPositions)
* [configXmlStringFormat](#method-configXmlStringFormat)
* [disable](#method-disable)
* [disableByName](#method-disableByName)
* [display](#method-display)
* [displayConfirmation](#method-displayConfirmation)
* [displayError](#method-displayError)
* [displayFlags](#method-displayFlags)
* [editExceptions](#method-editExceptions)
* [enable](#method-enable)
* [enableByName](#method-enableByName)
* [findTranslation](#method-findTranslation)
* [getAuthorizedModules](#method-getAuthorizedModules)
* [getCacheId](#method-getCacheId)
* [getConfirmations](#method-getConfirmations)
* [getCurrentSubTemplate](#method-getCurrentSubTemplate)
* [getErrors](#method-getErrors)
* [getExceptions](#method-getExceptions)
* [getInstanceById](#method-getInstanceById)
* [getInstanceByName](#method-getInstanceByName)
* [getLocalPath](#method-getLocalPath)
* [getModuleIdByName](#method-getModuleIdByName)
* [getModuleName](#method-getModuleName)
* [getModuleNameFromClass](#method-getModuleNameFromClass)
* [getModulesDirOnDisk](#method-getModulesDirOnDisk)
* [getModulesInstalled](#method-getModulesInstalled)
* [getModulesOnDisk](#method-getModulesOnDisk)
* [getNativeModuleList](#method-getNativeModuleList)
* [getNonNativeModuleList](#method-getNonNativeModuleList)
* [getPathUri](#method-getPathUri)
* [getPaymentModules](#method-getPaymentModules)
* [getPaypalIgnore](#method-getPaypalIgnore)
* [getPermission](#method-getPermission)
* [getPermissionStatic](#method-getPermissionStatic)
* [getPosition](#method-getPosition)
* [getTemplatePath](#method-getTemplatePath)
* [getUpgradeStatus](#method-getUpgradeStatus)
* [hookExec](#method-hookExec)
* [hookExecPayment](#method-hookExecPayment)
* [initUpgradeModule](#method-initUpgradeModule)
* [install](#method-install)
* [installOverrides](#method-installOverrides)
* [isCached](#method-isCached)
* [isEnabled](#method-isEnabled)
* [isEnabledForShopContext](#method-isEnabledForShopContext)
* [isHookableOn](#method-isHookableOn)
* [isInstalled](#method-isInstalled)
* [isRegisteredInHook](#method-isRegisteredInHook)
* [l](#method-l)
* [loadUpgradeVersionList](#method-loadUpgradeVersionList)
* [needUpgrade](#method-needUpgrade)
* [preCall](#method-preCall)
* [registerExceptions](#method-registerExceptions)
* [registerHook](#method-registerHook)
* [removeOverride](#method-removeOverride)
* [resetCurrentSubTemplate](#method-resetCurrentSubTemplate)
* [runUpgradeModule](#method-runUpgradeModule)
* [setUpgradeMessage](#method-setUpgradeMessage)
* [uninstall](#method-uninstall)
* [uninstallOverrides](#method-uninstallOverrides)
* [unregisterExceptions](#method-unregisterExceptions)
* [unregisterHook](#method-unregisterHook)
* [updateModuleTranslations](#method-updateModuleTranslations)
* [updatePosition](#method-updatePosition)
* [updateTranslationsAfterInstall](#method-updateTranslationsAfterInstall)
* [upgradeModuleVersion](#method-upgradeModuleVersion)


Constants
----------


### <a name="constant-CACHE_FILE_CUSTOMER_MODULES_LIST"></a>CACHE_FILE_CUSTOMER_MODULES_LIST

```php
const CACHE_FILE_CUSTOMER_MODULES_LIST = '/config/xml/customer_modules_list.xml'
```





* Source: [classes/module/Module.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L133).


### <a name="constant-CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST"></a>CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST

```php
const CACHE_FILE_DEFAULT_COUNTRY_MODULES_LIST = '/config/xml/default_country_modules_list.xml'
```





* Source: [classes/module/Module.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L131).


### <a name="constant-CACHE_FILE_MODULES_LIST"></a>CACHE_FILE_MODULES_LIST

```php
const CACHE_FILE_MODULES_LIST = '/config/xml/modules_list.xml'
```





* Source: [classes/module/Module.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L127).


### <a name="constant-CACHE_FILE_MUST_HAVE_MODULES_LIST"></a>CACHE_FILE_MUST_HAVE_MODULES_LIST

```php
const CACHE_FILE_MUST_HAVE_MODULES_LIST = '/config/xml/must_have_modules_list.xml'
```





* Source: [classes/module/Module.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L135).


### <a name="constant-CACHE_FILE_TAB_MODULES_LIST"></a>CACHE_FILE_TAB_MODULES_LIST

```php
const CACHE_FILE_TAB_MODULES_LIST = '/config/xml/tab_modules_list.xml'
```





* Source: [classes/module/Module.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L129).


Properties
----------


### <a name="property-$_INSTANCE"></a>$_INSTANCE

```php
protected \protected $_INSTANCE = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L105).


### <a name="property-$_confirmations"></a>$_confirmations

```php
protected \protected $_confirmations = array()
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L93).


### <a name="property-$_errors"></a>$_errors

```php
protected \protected $_errors = array()
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L90).


### <a name="property-$_generate_config_xml_mode"></a>$_generate_config_xml_mode

```php
protected \protected $_generate_config_xml_mode = false
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L108).


### <a name="property-$_lang"></a>$_lang

```php
protected array $_lang = array()
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L79).


### <a name="property-$_path"></a>$_path

```php
protected string $_path = null
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L82).


### <a name="property-$active"></a>$active

```php
public boolean $active = false
```





* Visibility: **public**
* Source: [classes/module/Module.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L67).


### <a name="property-$author"></a>$author

```php
public string $author
```





* Visibility: **public**
* Source: [classes/module/Module.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L58).


### <a name="property-$cache_permissions"></a>$cache_permissions

```php
protected \protected $cache_permissions = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L114).


### <a name="property-$classInModule"></a>$classInModule

```php
public array $classInModule = array()
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/module/Module.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L76).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L117).


### <a name="property-$current_subtemplate"></a>$current_subtemplate

```php
protected \currentSmartySubTemplate $current_subtemplate = null
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L123).


### <a name="property-$database_version"></a>$database_version

```php
public mixed $database_version
```





* Visibility: **public**
* Source: [classes/module/Module.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L34).


### <a name="property-$dependencies"></a>$dependencies

```php
public array $dependencies = array()
```





* Visibility: **public**
* Source: [classes/module/Module.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L46).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/module/Module.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L55).


### <a name="property-$displayName"></a>$displayName

```php
public string $displayName
```





* Visibility: **public**
* Source: [classes/module/Module.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L52).


### <a name="property-$id"></a>$id

```php
public integer $id = null
```





* Visibility: **public**
* Source: [classes/module/Module.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L30).


### <a name="property-$identifier"></a>$identifier

```php
protected \protected $identifier = 'id_module'
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L99).


### <a name="property-$l_cache"></a>$l_cache

```php
protected \protected $l_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L111).


### <a name="property-$limited_countries"></a>$limited_countries

```php
public array $limited_countries = array()
```





* Visibility: **public**
* Source: [classes/module/Module.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L73).


### <a name="property-$local_path"></a>$local_path

```php
protected string $local_path = null
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L87).


### <a name="property-$modules_cache"></a>$modules_cache

```php
protected \protected $modules_cache
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L102).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/module/Module.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L49).


### <a name="property-$need_instance"></a>$need_instance

```php
public integer $need_instance = 1
```





* Visibility: **public**
* Source: [classes/module/Module.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L61).


### <a name="property-$ps_versions_compliancy"></a>$ps_versions_compliancy

```php
public array $ps_versions_compliancy = array('min' => '1.4', 'max' => '1.6')
```





* Visibility: **public**
* Source: [classes/module/Module.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L43).


### <a name="property-$registered_version"></a>$registered_version

```php
public string $registered_version
```





* Visibility: **public**
* Source: [classes/module/Module.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L40).


### <a name="property-$smarty"></a>$smarty

```php
protected \Smarty_Data $smarty
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L120).


### <a name="property-$tab"></a>$tab

```php
public string $tab = null
```





* Visibility: **public**
* Source: [classes/module/Module.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L64).


### <a name="property-$table"></a>$table

```php
protected \protected $table = 'module'
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L96).


### <a name="property-$update_translations_after_install"></a>$update_translations_after_install

```php
protected mixed $update_translations_after_install = true
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/module/Module.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L125).


### <a name="property-$version"></a>$version

```php
public float $version
```





* Visibility: **public**
* Source: [classes/module/Module.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L33).


### <a name="property-$warning"></a>$warning

```php
public string $warning
```





* Visibility: **public**
* Source: [classes/module/Module.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L70).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ModuleCore::__construct(string $name, \Context $context)
```

Constructor



* Visibility: **public**
* Source: [classes/module/Module.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L143)


#### Arguments
* $name **string** - Module unique name
* $context **[Context](class.ContextCore.md)**



### <a name="method-_clearCache"></a>_clearCache

```php
mixed ModuleCore::_clearCache($template, $cache_id, $compile_id)
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 1775](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1775)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-_generateConfigXml"></a>_generateConfigXml

```php
mixed ModuleCore::_generateConfigXml()
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 1784](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1784)




### <a name="method-_getApplicableTemplateDir"></a>_getApplicableTemplateDir

```php
mixed ModuleCore::_getApplicableTemplateDir($template)
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 1761](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1761)


#### Arguments
* $template **mixed**



### <a name="method-_isTemplateOverloaded"></a>_isTemplateOverloaded

```php
mixed ModuleCore::_isTemplateOverloaded($template)
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 1672](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1672)


#### Arguments
* $template **mixed**



### <a name="method-_isTemplateOverloadedStatic"></a>_isTemplateOverloadedStatic

```php
mixed ModuleCore::_isTemplateOverloadedStatic($module_name, $template)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/module/Module.php line 1657](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1657)


#### Arguments
* $module_name **mixed**
* $template **mixed**



### <a name="method-addOverride"></a>addOverride

```php
boolean ModuleCore::addOverride(string $classname)
```

Add all methods in a module override to the override class



* Visibility: **public**
* Source: [classes/module/Module.php line 2033](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L2033)


#### Arguments
* $classname **string**



### <a name="method-adminDisplayInformation"></a>adminDisplayInformation

```php
mixed ModuleCore::adminDisplayInformation(string $msg)
```

add a info message to display at the top of the admin page



* Visibility: **protected**
* Source: [classes/module/Module.php line 1979](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1979)


#### Arguments
* $msg **string**



### <a name="method-adminDisplayWarning"></a>adminDisplayWarning

```php
mixed ModuleCore::adminDisplayWarning(string $msg)
```

add a warning message to display at the top of the admin page



* Visibility: **public**
* Source: [classes/module/Module.php line 1967](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1967)


#### Arguments
* $msg **string**



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed ModuleCore::cleanPositions($id_hook, $shop_list)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1513](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1513)


#### Arguments
* $id_hook **mixed**
* $shop_list **mixed**



### <a name="method-configXmlStringFormat"></a>configXmlStringFormat

```php
mixed ModuleCore::configXmlStringFormat($string)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 954](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L954)


#### Arguments
* $string **mixed**



### <a name="method-disable"></a>disable

```php
mixed ModuleCore::disable(boolean $forceAll)
```

Desactivate current module.



* Visibility: **public**
* Source: [classes/module/Module.php line 639](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L639)


#### Arguments
* $forceAll **boolean** - If true, disable module for all shop



### <a name="method-disableByName"></a>disableByName

```php
true ModuleCore::disableByName(array|string $name)
```

This function disable module $name. If an $name is an array,
this will disable all of them



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 621](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L621)


#### Arguments
* $name **array|string**



### <a name="method-display"></a>display

```php
mixed ModuleCore::display($file, $template, $cacheId, $compileId)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1694](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1694)


#### Arguments
* $file **mixed**
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-displayConfirmation"></a>displayConfirmation

```php
mixed ModuleCore::displayConfirmation($string)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1548](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1548)


#### Arguments
* $string **mixed**



### <a name="method-displayError"></a>displayError

```php
mixed ModuleCore::displayError($error)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1538](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1538)


#### Arguments
* $error **mixed**



### <a name="method-displayFlags"></a>displayFlags

```php
mixed ModuleCore::displayFlags(array $languages, integer $default_language, string $ids, string $id, boolean $return, boolean $use_vars_instead_of_ids)
```

Display flags in forms for translations



* Visibility: **public**
* Source: [classes/module/Module.php line 656](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L656)


#### Arguments
* $languages **array** - All languages available
* $default_language **integer** - Default language id
* $ids **string** - Multilingual div ids in form
* $id **string** - Current div id]
* $return **boolean** - define the return way : false for a display, true for a return
* $use_vars_instead_of_ids **boolean** - use an js vars instead of ids seperate by &quot;¤&quot;



### <a name="method-editExceptions"></a>editExceptions

```php
boolean ModuleCore::editExceptions($id_hook, array $excepts)
```

Edit exceptions for module->Hook



* Visibility: **public**
* Source: [classes/module/Module.php line 846](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L846)


#### Arguments
* $id_hook **mixed**
* $excepts **array** - List of shopID and file name



### <a name="method-enable"></a>enable

```php
mixed ModuleCore::enable(boolean $forceAll)
```

Activate current module.



* Visibility: **public**
* Source: [classes/module/Module.php line 588](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L588)


#### Arguments
* $forceAll **boolean** - If true, enable module for all shop



### <a name="method-enableByName"></a>enableByName

```php
true ModuleCore::enableByName(array|string $name)
```

This function enable module $name. If an $name is an array,
this will enable all of them



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 570](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L570)


#### Arguments
* $name **array|string**



### <a name="method-findTranslation"></a>findTranslation

```php
mixed ModuleCore::findTranslation($name, $string, $source)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1433](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1433)


#### Arguments
* $name **mixed**
* $string **mixed**
* $source **mixed**



### <a name="method-getAuthorizedModules"></a>getAuthorizedModules

```php
mixed ModuleCore::getAuthorizedModules($group_id)
```

Get Unauthorized modules for a client group



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1870](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1870)


#### Arguments
* $group_id **mixed**



### <a name="method-getCacheId"></a>getCacheId

```php
mixed ModuleCore::getCacheId($name)
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 1677](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1677)


#### Arguments
* $name **mixed**



### <a name="method-getConfirmations"></a>getConfirmations

```php
array ModuleCore::getConfirmations()
```

Get module messages confirmation



* Visibility: **public**
* Source: [classes/module/Module.php line 1911](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1911)




### <a name="method-getCurrentSubTemplate"></a>getCurrentSubTemplate

```php
mixed ModuleCore::getCurrentSubTemplate($template, $cache_id, $compile_id)
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 1719](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1719)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-getErrors"></a>getErrors

```php
array ModuleCore::getErrors()
```

Get module errors



* Visibility: **public**
* Source: [classes/module/Module.php line 1900](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1900)




### <a name="method-getExceptions"></a>getExceptions

```php
mixed ModuleCore::getExceptions($id_hook, $dispatch)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1563](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1563)


#### Arguments
* $id_hook **mixed**
* $dispatch **mixed**



### <a name="method-getInstanceById"></a>getInstanceById

```php
\Module ModuleCore::getInstanceById(integer $id_module)
```

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 935](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L935)


#### Arguments
* $id_module **integer** - Module ID



### <a name="method-getInstanceByName"></a>getInstanceByName

```php
\Module ModuleCore::getInstanceByName(string $module_name)
```

Return an instance of the specified module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 906](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L906)


#### Arguments
* $module_name **string** - Module name



### <a name="method-getLocalPath"></a>getLocalPath

```php
string ModuleCore::getLocalPath()
```

Get local path for module



* Visibility: **public**
* Source: [classes/module/Module.php line 1922](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1922)




### <a name="method-getModuleIdByName"></a>getModuleIdByName

```php
integer ModuleCore::getModuleIdByName($name)
```

Get id module by name



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1883](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1883)


#### Arguments
* $name **mixed**



### <a name="method-getModuleName"></a>getModuleName

```php
mixed ModuleCore::getModuleName($module)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 960](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L960)


#### Arguments
* $module **mixed**



### <a name="method-getModuleNameFromClass"></a>getModuleNameFromClass

```php
boolean|string ModuleCore::getModuleNameFromClass(mixed $currentClass)
```

This function is used to determine the module name
of an AdminTab which belongs to a module, in order to keep translation
related to a module in its directory (instead of $_LANGADM)



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 868](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L868)


#### Arguments
* $currentClass **mixed** - the



### <a name="method-getModulesDirOnDisk"></a>getModulesDirOnDisk

```php
array ModuleCore::getModulesDirOnDisk()
```

Return modules directory list



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1271](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1271)




### <a name="method-getModulesInstalled"></a>getModulesInstalled

```php
array ModuleCore::getModulesInstalled(integer $position)
```

Return installed modules



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1340](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1340)


#### Arguments
* $position **integer** - Take only positionnables modules



### <a name="method-getModulesOnDisk"></a>getModulesOnDisk

```php
array ModuleCore::getModulesOnDisk(boolean $useConfig, $loggedOnAddons, $id_employee)
```

Return available modules



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 995](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L995)


#### Arguments
* $useConfig **boolean** - in order to use config.xml file in module dir
* $loggedOnAddons **mixed**
* $id_employee **mixed**



### <a name="method-getNativeModuleList"></a>getNativeModuleList

```php
mixed ModuleCore::getNativeModuleList()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1314](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1314)




### <a name="method-getNonNativeModuleList"></a>getNonNativeModuleList

```php
array ModuleCore::getNonNativeModuleList()
```

Return non native module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1296](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1296)




### <a name="method-getPathUri"></a>getPathUri

```php
string ModuleCore::getPathUri()
```

Get uri path for module



* Visibility: **public**
* Source: [classes/module/Module.php line 1933](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1933)




### <a name="method-getPaymentModules"></a>getPaymentModules

```php
array ModuleCore::getPaymentModules()
```

Returns the list of the payment module associated to the current customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1389](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1389)




### <a name="method-getPaypalIgnore"></a>getPaypalIgnore

```php
mixed ModuleCore::getPaypalIgnore()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1375](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1375)




### <a name="method-getPermission"></a>getPermission

```php
boolean ModuleCore::getPermission(array $variable, object $employee)
```

Check employee permission for module



* Visibility: **public**
* Source: [classes/module/Module.php line 1827](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1827)


#### Arguments
* $variable **array** - (action)
* $employee **object**



### <a name="method-getPermissionStatic"></a>getPermissionStatic

```php
boolean ModuleCore::getPermissionStatic(integer $id_module, array $variable, object $employee)
```

Check employee permission for module (static method)



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1839](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1839)


#### Arguments
* $id_module **integer**
* $variable **array** - (action)
* $employee **object**



### <a name="method-getPosition"></a>getPosition

```php
mixed ModuleCore::getPosition($id_hook)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1944](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1944)


#### Arguments
* $id_hook **mixed**



### <a name="method-getTemplatePath"></a>getTemplatePath

```php
string ModuleCore::getTemplatePath(string $template)
```

Get realpath of a template of current module (check if template is overriden too)



* Visibility: **public**
* Source: [classes/module/Module.php line 1745](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1745)


#### Arguments
* $template **string**



### <a name="method-getUpgradeStatus"></a>getUpgradeStatus

```php
boolean ModuleCore::getUpgradeStatus($module_name)
```

Return the status of the upgraded module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 510](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L510)


#### Arguments
* $module_name **mixed**



### <a name="method-hookExec"></a>hookExec

```php
string ModuleCore::hookExec(string $hook_name, array $hookArgs, $id_module)
```

Execute modules for specified hook



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1358](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1358)


#### Arguments
* $hook_name **string** - Hook Name
* $hookArgs **array** - Parameters for the functions
* $id_module **mixed**



### <a name="method-hookExecPayment"></a>hookExecPayment

```php
mixed ModuleCore::hookExecPayment()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1364](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1364)




### <a name="method-initUpgradeModule"></a>initUpgradeModule

```php
boolean ModuleCore::initUpgradeModule($module)
```

Init the upgrade module



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 336](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L336)


#### Arguments
* $module **mixed**



### <a name="method-install"></a>install

```php
mixed ModuleCore::install()
```

Insert module into datable



* Visibility: **public**
* Source: [classes/module/Module.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L196)




### <a name="method-installOverrides"></a>installOverrides

```php
boolean ModuleCore::installOverrides()
```

Install overrides files for the module



* Visibility: **public**
* Source: [classes/module/Module.php line 1991](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1991)




### <a name="method-isCached"></a>isCached

```php
mixed ModuleCore::isCached($template, $cacheId, $compileId)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1766](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1766)


#### Arguments
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-isEnabled"></a>isEnabled

```php
mixed ModuleCore::isEnabled($module_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1629](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1629)


#### Arguments
* $module_name **mixed**



### <a name="method-isEnabledForShopContext"></a>isEnabledForShopContext

```php
mixed ModuleCore::isEnabledForShopContext()
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1617](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1617)




### <a name="method-isHookableOn"></a>isHookableOn

```php
boolean ModuleCore::isHookableOn(string $hook_name)
```

Check if the module is transplantable on the hook in parameter



* Visibility: **public**
* Source: [classes/module/Module.php line 1815](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1815)


#### Arguments
* $hook_name **string**



### <a name="method-isInstalled"></a>isInstalled

```php
mixed ModuleCore::isInstalled($module_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1607](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1607)


#### Arguments
* $module_name **mixed**



### <a name="method-isRegisteredInHook"></a>isRegisteredInHook

```php
mixed ModuleCore::isRegisteredInHook($hook)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1642](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1642)


#### Arguments
* $hook **mixed**



### <a name="method-l"></a>l

```php
string ModuleCore::l(string $string, boolean|string $specific)
```

Get translation for a given module text

Note: $specific parameter is mandatory for library files.
Otherwise, translation key will not match for Module library
when module is loaded with eval() Module::getModulesOnDisk()

* Visibility: **public**
* Source: [classes/module/Module.php line 1449](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1449)


#### Arguments
* $string **string** - String to translate
* $specific **boolean|string** - filename to use in translation key



### <a name="method-loadUpgradeVersionList"></a>loadUpgradeVersionList

```php
boolean ModuleCore::loadUpgradeVersionList($module_name, $module_version, $registered_version)
```

Load the available list of upgrade of a specified module
with an associated version



* Visibility: **protected**
* This method is **static**.
* Source: [classes/module/Module.php line 460](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L460)


#### Arguments
* $module_name **mixed**
* $module_version **mixed**
* $registered_version **mixed**



### <a name="method-needUpgrade"></a>needUpgrade

```php
boolean ModuleCore::needUpgrade($module)
```

Check if a module need to be upgraded.

This method modify the module_cache adding an upgrade list file

* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 436](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L436)


#### Arguments
* $module **mixed**



### <a name="method-preCall"></a>preCall

```php
mixed ModuleCore::preCall($module_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 1370](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1370)


#### Arguments
* $module_name **mixed**



### <a name="method-registerExceptions"></a>registerExceptions

```php
boolean ModuleCore::registerExceptions(integer $id_hook, array $excepts, array $shop_list)
```

Add exceptions for module->Hook



* Visibility: **public**
* Source: [classes/module/Module.php line 812](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L812)


#### Arguments
* $id_hook **integer** - Hook id
* $excepts **array** - List of file name
* $shop_list **array** - List of shop



### <a name="method-registerHook"></a>registerHook

```php
boolean ModuleCore::registerHook(string $hook_name, array $shop_list)
```

Connect module to a hook



* Visibility: **public**
* Source: [classes/module/Module.php line 686](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L686)


#### Arguments
* $hook_name **string** - Hook name
* $shop_list **array** - List of shop linked to the hook (if null, link hook to all shops)



### <a name="method-removeOverride"></a>removeOverride

```php
boolean ModuleCore::removeOverride(string $classname)
```

Remove all methods in a module override from the override class



* Visibility: **public**
* Source: [classes/module/Module.php line 2093](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L2093)


#### Arguments
* $classname **string**



### <a name="method-resetCurrentSubTemplate"></a>resetCurrentSubTemplate

```php
mixed ModuleCore::resetCurrentSubTemplate($template, $cache_id, $compile_id)
```





* Visibility: **protected**
* Source: [classes/module/Module.php line 1733](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1733)


#### Arguments
* $template **mixed**
* $cache_id **mixed**
* $compile_id **mixed**



### <a name="method-runUpgradeModule"></a>runUpgradeModule

```php
array ModuleCore::runUpgradeModule()
```

Run the upgrade for a given module name and version



* Visibility: **public**
* Source: [classes/module/Module.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L366)




### <a name="method-setUpgradeMessage"></a>setUpgradeMessage

```php
mixed ModuleCore::setUpgradeMessage($upgrade_detail)
```

Set errors, warning or success message of a module upgrade



* Visibility: **protected**
* Source: [classes/module/Module.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L300)


#### Arguments
* $upgrade_detail **mixed**



### <a name="method-uninstall"></a>uninstall

```php
boolean ModuleCore::uninstall()
```

Delete module from datable



* Visibility: **public**
* Source: [classes/module/Module.php line 521](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L521)




### <a name="method-uninstallOverrides"></a>uninstallOverrides

```php
boolean ModuleCore::uninstallOverrides()
```

Uninstall overrides files for the module



* Visibility: **public**
* Source: [classes/module/Module.php line 2012](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L2012)




### <a name="method-unregisterExceptions"></a>unregisterExceptions

```php
boolean ModuleCore::unregisterExceptions($hook_id, array $shop_list)
```

Unregister exceptions linked to module



* Visibility: **public**
* Source: [classes/module/Module.php line 796](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L796)


#### Arguments
* $hook_id **mixed**
* $shop_list **array** - List of shop



### <a name="method-unregisterHook"></a>unregisterHook

```php
boolean ModuleCore::unregisterHook($hook_id, array $shop_list)
```

Unregister module from hook



* Visibility: **public**
* Source: [classes/module/Module.php line 759](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L759)


#### Arguments
* $hook_id **mixed**
* $shop_list **array** - List of shop



### <a name="method-updateModuleTranslations"></a>updateModuleTranslations

```php
mixed ModuleCore::updateModuleTranslations()
```





* Visibility: **public**
* Source: [classes/module/Module.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L290)




### <a name="method-updatePosition"></a>updatePosition

```php
mixed ModuleCore::updatePosition($id_hook, $way, $position)
```





* Visibility: **public**
* Source: [classes/module/Module.php line 1464](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L1464)


#### Arguments
* $id_hook **mixed**
* $way **mixed**
* $position **mixed**



### <a name="method-updateTranslationsAfterInstall"></a>updateTranslationsAfterInstall

```php
mixed ModuleCore::updateTranslationsAfterInstall($update)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L285)


#### Arguments
* $update **mixed**



### <a name="method-upgradeModuleVersion"></a>upgradeModuleVersion

```php
boolean ModuleCore::upgradeModuleVersion($name, $version)
```

Upgrade the registered version to a new one



* Visibility: **public**
* This method is **static**.
* Source: [classes/module/Module.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/module/Module.php#L419)


#### Arguments
* $name **mixed**
* $version **mixed**

