Class CategoryControllerCore
=====================





* Class name: CategoryControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/CategoryController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L27)



Properties
----------

* [$cat_products](#property-$cat_products)
* [$category](#property-$category)
* [$customer_access](#property-$customer_access)
* [$nbProducts](#property-$nbProducts)
* [$php_self](#property-$php_self)

Methods
-------
* [assignProductList](#method-assignProductList)
* [assignScenes](#method-assignScenes)
* [assignSubcategories](#method-assignSubcategories)
* [canonicalRedirection](#method-canonicalRedirection)
* [getCategory](#method-getCategory)
* [init](#method-init)
* [initContent](#method-initContent)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$cat_products"></a>$cat_products

    protected array $cat_products





* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L42)


### <a name="property-$category"></a>$category

    protected \Category $category





* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L33)


### <a name="property-$customer_access"></a>$customer_access

    public boolean $customer_access = true





* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L36)


### <a name="property-$nbProducts"></a>$nbProducts

    protected integer $nbProducts





* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L39)


### <a name="property-$php_self"></a>$php_self

    public mixed $php_self = 'category'

string Internal controller name



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L30)


Methods
-------


### <a name="method-assignProductList"></a>assignProductList

    mixed CategoryControllerCore::assignProductList()

Assigns product list template variables



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L211)




### <a name="method-assignScenes"></a>assignScenes

    mixed CategoryControllerCore::assignScenes()

Assigns scenes template variables



* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L171)




### <a name="method-assignSubcategories"></a>assignSubcategories

    mixed CategoryControllerCore::assignSubcategories()

Assigns subcategory templates variables



* Visibility: **protected**
* Source: [controllers/front/CategoryController.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L197)




### <a name="method-canonicalRedirection"></a>canonicalRedirection

    mixed CategoryControllerCore::canonicalRedirection(string $canonical_url)

Redirects to canonical or "Not Found" URL



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L74)


#### Arguments
* $canonical_url **string**



### <a name="method-getCategory"></a>getCategory

    \Category CategoryControllerCore::getCategory()

Returns an instance of the current category



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L254)




### <a name="method-init"></a>init

    mixed CategoryControllerCore::init()

Initializes controller



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L96)




### <a name="method-initContent"></a>initContent

    mixed CategoryControllerCore::initContent()

Initializes page content variables



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L127)




### <a name="method-setMedia"></a>setMedia

    mixed CategoryControllerCore::setMedia()

Sets default medias for this controller



* Visibility: **public**
* Source: [controllers/front/CategoryController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L47)


