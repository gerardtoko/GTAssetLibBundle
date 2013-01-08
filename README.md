GTAssetLibBundle
================

Grouping the asset libraries in a symfony bundle

## Using with Twig

### Backbone
* Backbone: http://backbonejs.org

```
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

```
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

```
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

```
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

```
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
```
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

```
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
```
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
```
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
```
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
