GTAssetLibBundle
================

Grouping the asset libraries in a symfony bundle

## Using with Twig

### jQuery and JQuery UI
jQuery WebSite: http://jquery.com
jQuery UI WebSite: http://jqueryui.com

```
    {% javascripts
	'vendor/jquery/jquery.min.js'
	'vendor/jquery/jquery.ui.min.js'
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
	'vendor/bootstrap/css/bootstrap.min.css' 
	output='assets/compiled/style.css'
	filter='yui_css'
    %}
    <link rel="stylesheet" href="{{ asset_url }}" />
    {% endstylesheets %}

    {% javascripts
	'vendor/bootstrap/js/bootstrap.min.js'
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
	'vendor/datatables/media/css/demo_page.css'
	'vendor/datatables/media/css/demo_table.css'
	'vendor/datatables/media/css/demo_table_jui.css'
	'vendor/datatables/media/css/jquery.dataTables.css'
	'vendor/datatables/media/css/jquery.dataTables_themeroller.css'
     output='assets/compiled/style.css'
     filter='yui_css'
    %}
    <link rel="stylesheet" href="{{ asset_url }}" />
    {% endstylesheets %}

    {% javascripts
	'vendor/datatables/media/js/jquery.dataTables.min.js'
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
	'vendor/chosen/chosen/chosen.css'
     output='assets/compiled/style.css'
     filter='yui_css'
    %}
    <link rel="stylesheet" href="{{ asset_url }}" />
    {% endstylesheets %}

    {% javascripts
	'vendor/chosen/chosen/chosen.jquery.min.js'
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
	'vendor/datepicker/css/datepicker.css'
     output='assets/compiled/style.css'
     filter='yui_css'
    %}
    <link rel="stylesheet" href="{{ asset_url }}" />
    {% endstylesheets %}

    {% javascripts
	'vendor/datepicker/js/bootstrap-datepicker.js'
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
	'vendor/ckeditor/ckeditor.js'
	'vendor/ckeditor/adapters/jquery.js'
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
	'vendor/jquery-cookie/jquery.cookie.js'
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
	'vendor/dynatree/src/skin/ui.dynatree.css'
     output='assets/compiled/style.css'
     filter='yui_css'
    %}
    <link rel="stylesheet" href="{{ asset_url }}" />
    {% endstylesheets %}

    {% javascripts
	'vendor/dynatree/src/jquery.dynatree.js'
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
	'vendor/dynatree/src/skin/ui.dynatree.css'
     output='assets/compiled/style.css'
     filter='yui_css'
    %}
    <link rel="stylesheet" href="{{ asset_url }}" />
    {% endstylesheets %}

    {% javascripts
	'vendor/dynatree/src/jquery.dynatree.js'
     output='assets/compiled/script.js'
     filter='yui_js'
    %}
    <script src="{{ asset_url }}"></script>
    {% endjavascripts %}
```

## All Libraries
###jQuery 
###jQuery UI
###Bootstrap Twitter
###Datepicker for Bootstrap Twitter
###Datatables
###Chosen
###Ckeditor
###JQuery Cookie
###Dynatree
###Import Player
###JQuery-tokeninput
###Loader
###Swfobject
###Uploadify
###Tinymce
###Tapmodo-Jcrop