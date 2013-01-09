GTAssetLibBundle
================

Grouping the asset libraries in a symfony bundle

##  Installation

### Download GTAssetLibBundle using composer

Add GTAssetLibBundle in your composer.json:

```js
{
    "require": {
        "gerardtoko/assetlib-bundle": "dev-master"
    }
}
```

Now tell composer to download the bundle by running the command:

```bash
$ php composer.phar update gerardtoko/assetlib-bundle
```

Composer will install the bundle to your project's `vendor/gerardtoko/assetlib-bundle` directory.


### Register the bundle

You must register the bundle in your kernel:
```php
    <?php
    
    // app/AppKernel.php    
    public function registerBundles()
    {
        $bundles = array(    
            // ...    
             new GT\AssetLibBundle\GTAssetLibBundle(),
        );    
        // ...
    }
```

## Using with Twig

### Backbone
* Backbone: http://backbonejs.org

```jinja
    {% javascripts
	'@GTAssetLibBundle/Resources/public/backbone/backbone-min.js'	
	output='assets/compiled/script.js'
	filter='yui_js'
    %}
    <script src="{{ asset_url }}"></script>
    {% endjavascripts %}
```

### jQuery and JQuery UI
* jQuery WebSite: http://jquery.com
* jQuery UI WebSite: http://jqueryui.com

```jinja
    {% javascripts
	'@GTAssetLibBundle/Resources/public/jquery/jquery.min.js'
	'@GTAssetLibBundle/Resources/public/jquery/jquery.ui.min.js'
	output='assets/compiled/script.js'
	filter='yui_js'
    %}
    <script src="{{ asset_url }}"></script>
    {% endjavascripts %}
```


### Bootstrap Twitter
Bootstrap Twitter WebSite: http://twitter.github.com/bootstrap

```jinja
    {% stylesheets
	'@GTAssetLibBundle/Resources/public/bootstrap/css/bootstrap.min.css' 
	output='assets/compiled/style.css'
	filter='yui_css'
    %}
    <link rel="stylesheet" href="{{ asset_url }}" />
    {% endstylesheets %}

    {% javascripts
	'@GTAssetLibBundle/Resources/public/bootstrap/js/bootstrap.min.js'
	output='assets/compiled/script.js'
	filter='yui_js'
    %}
    <script src="{{ asset_url }}"></script>
    {% endjavascripts %}
```

### Datatables
Datatables WebSite: http://www.datatables.net

```jinja
    {% stylesheets
	'@GTAssetLibBundle/Resources/public/datatables/media/css/demo_page.css'
	'@GTAssetLibBundle/Resources/public/datatables/media/css/demo_table.css'
	'@GTAssetLibBundle/Resources/public/datatables/media/css/demo_table_jui.css'
	'@GTAssetLibBundle/Resources/public/datatables/media/css/jquery.dataTables.css'
	'@GTAssetLibBundle/Resources/public/datatables/media/css/jquery.dataTables_themeroller.css'
     output='assets/compiled/style.css'
     filter='yui_css'
    %}
    <link rel="stylesheet" href="{{ asset_url }}" />
    {% endstylesheets %}

    {% javascripts
	'@GTAssetLibBundle/Resources/public/datatables/media/js/jquery.dataTables.min.js'
     output='assets/compiled/script.js'
     filter='yui_js'
    %}
    <script src="{{ asset_url }}"></script>
    {% endjavascripts %}
```

### Chosen
Chosen WebSite: http://harvesthq.github.com/chosen

```jinja
    {% stylesheets
	'@GTAssetLibBundle/Resources/public/chosen/chosen/chosen.css'
     output='assets/compiled/style.css'
     filter='yui_css'
    %}
    <link rel="stylesheet" href="{{ asset_url }}" />
    {% endstylesheets %}

    {% javascripts
	'@GTAssetLibBundle/Resources/public/chosen/chosen/chosen.jquery.min.js'
     output='assets/compiled/script.js'
     filter='yui_js'
    %}
    <script src="{{ asset_url }}"></script>
    {% endjavascripts %}
```

### Datepicker for Bootstrap Twitter
Datepicker for Bootstrap Twitter WebSite: http://www.eyecon.ro/bootstrap-datepicker
```jinja
    {% stylesheets
	'@GTAssetLibBundle/Resources/public/datepicker/css/datepicker.css'
     output='assets/compiled/style.css'
     filter='yui_css'
    %}
    <link rel="stylesheet" href="{{ asset_url }}" />
    {% endstylesheets %}

    {% javascripts
	'@GTAssetLibBundle/Resources/public/datepicker/js/bootstrap-datepicker.js'
     output='assets/compiled/script.js'
     filter='yui_js'
    %}
    <script src="{{ asset_url }}"></script>
    {% endjavascripts %}
```

### Ckeditor
Bootstrap Twitter Datepicker WebSite: http://ckeditor.com

```jinja
    {% javascripts
	'@GTAssetLibBundle/Resources/public/ckeditor/ckeditor.js'
	'@GTAssetLibBundle/Resources/public/ckeditor/adapters/jquery.js'
     output='assets/compiled/script.js'
     filter='yui_js'
    %}
    <script src="{{ asset_url }}"></script>
    {% endjavascripts %}
```

### JQuery Cookie
Dynatree Website: https://github.com/carhartl/jquery-cookie
```jinja
    {% javascripts
	'@GTAssetLibBundle/Resources/public/jquery-cookie/jquery.cookie.js'
     output='assets/compiled/script.js'
     filter='yui_js'
    %}
    <script src="{{ asset_url }}"></script>
    {% endjavascripts %}
```

### Dynatree
Dynatree WebSite: http://code.google.com/p/dynatree
```jinja
    {% stylesheets
	'@GTAssetLibBundle/Resources/public/dynatree/src/skin/ui.dynatree.css'
     output='assets/compiled/style.css'
     filter='yui_css'
    %}
    <link rel="stylesheet" href="{{ asset_url }}" />
    {% endstylesheets %}

    {% javascripts
	'@GTAssetLibBundle/Resources/public/dynatree/src/jquery.dynatree.js'
     output='assets/compiled/script.js'
     filter='yui_js'
    %}
    <script src="{{ asset_url }}"></script>
    {% endjavascripts %}
```

### Import Player
ImportPlayer: https://github.com/gerardtoko/importplayer
```jinja
    {% stylesheets
	'@GTAssetLibBundle/Resources/public/dynatree/src/skin/ui.dynatree.css'
     output='assets/compiled/style.css'
     filter='yui_css'
    %}
    <link rel="stylesheet" href="{{ asset_url }}" />
    {% endstylesheets %}

    {% javascripts
	'@GTAssetLibBundle/Resources/public/dynatree/src/jquery.dynatree.js'
     output='assets/compiled/script.js'
     filter='yui_js'
    %}
    <script src="{{ asset_url }}"></script>
    {% endjavascripts %}
```

## All Libraries
* Backbone
* jQuery 
* jQuery UI
* Bootstrap Twitter
* Datepicker for Bootstrap Twitter
* Datatables
* Chosen
* Ckeditor
* JQuery Cookie
* Dynatree
* Import Player
* JQuery-tokeninput
* Loader
* Swfobject
* Uploadify
* Tinymce
* Tapmodo-Jcrop
