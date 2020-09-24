<div align="center">

## Image Preloader


</div>

### Description

An Image Preloader preloads images to a web-page viewers hard drive before they need the picture. In other words, no more waitng for those darned mouseovers!

Please Rate My Work!!!!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[unholy\-slacker](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/unholy-slacker.md)
**Level**          |Beginner
**User Rating**    |5.0 (25 globes from 5 users)
**Compatibility**  |
**Category**       |[Controls/ Forms/ Graphics/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-graphics-menus__2-59.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/unholy-slacker-image-preloader__2-2044/archive/master.zip)





### Source Code

```
<html>
<script language="javascript">
function doPreload()
{
	// you chg all the images in this array to the ones you want to preload
	var the_images = new Array('image1.gif','image2.gif','image3.gif');
	preloadImages(the_images);
}
function preloadImages(the_images_array) {
	for(loop = 0; loop < the_images_array.length; loop++)
	{
  		var an_image = new Image();
		an_image.src = the_images_array[loop];
	}
}
</script>
<body onLoad="doPreload();">
put your mouseovers here
</body>
</html>
```

