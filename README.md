# Parallaxie
Parallaxie is a jQuery plugin to create parallax effects on your websites or templates. It is very lightweight to download and rendering by your browser.

### Current Version:
0.5

### Dependency:
This plugin has only one dependency, which is `jQuery`

### Installation
Installing this plugin is very easy.
You have to include jQuery and Parallaxie scripts to your website.
```
<script src="js/jquery.min.js"></script>
<script src="js/parallaxie.min.js"></script>
```

Fire up the plugin with any css selector. You must have a background image set into that element or you can use the `data-image` attribute, will explain about this later. Also, make sure the parallax element must have some height or some content which has some height.

```
<style>
.parallaxie{
    min-height: 360px;
}
</style>
<div class="parallaxie" style='background: url("path/to/your/image.png")'></div>
<script>
$('.parallaxie').parallaxie();
</script>
```

View a more intutive [Parallaxie example](http://theultrasoft.com/project/parallaxie).