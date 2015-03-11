iosCheckbox.js
==============

A jQuery plugin that transform any checkbox element into a beautiful ios style checkbox.

![alt tag](http://s15.postimg.org/gbyj9pzk7/ios_Checbox.png)

Demo: http://jsfiddle.net/bttkc3jg/1/

Demo Alternative Theme: http://jsfiddle.net/5xzevfq7/

Usage:

Include the css

```
<link rel="stylesheet" type="text/css" href="iosCheckbox.css" />
```

Add some checkboxs to your page

```
<input type="checkbox" class="ios" checked />
<input type="checkbox" class="ios" />
```

Load jQuery and iosCheckbox 

```
<script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script type="text/javascript" src="iosCheckbox.js"></script>
```

Transform all checkboxs with the class of `ios`

```
<script type="text/javascript">
	jQuery(function ($){
	     $(".ios").iosCheckbox();
	});
</script>
```

We also have a Zepto based version thanks to [LeoUnglaub](https://github.com/LeoUnglaub) you can find it in [here](https://bitbucket.org/foxship/ioscheckbox.js)
