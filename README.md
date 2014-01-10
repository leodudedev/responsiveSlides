# [jQuery responsiveSlides]
#### Full Width images slide with fixed height

Usage
-----

Just include this script after jQuery. Requires jQuery 1.5+ and onImagesLoad 1.2.2+

``` html

<div id="content">
	<img src="https://drive.google.com/uc?export=view&id=0B8uoQ-Ue05dOMXhYcjJDbE9mcms">
	<img src="https://drive.google.com/uc?export=view&id=0B8uoQ-Ue05dOTFJTT2w2Zll1TGc">
	<img src="https://drive.google.com/uc?export=view&id=0B8uoQ-Ue05dOaF9hY0UtNEFiaVE">
    ...
    ...
</div>

<script src="jquery-1.9.1.min.js"></script>
<script src="jquery.onImagesLoad.min.js"></script>
<script src="jquery.responsiveSlides.js"></script>

<script language="javascript">

var p=$('#content').responsiveSlides({
	
 // list of images url if the container is empty
 img:[
 	"https://drive.google.com/uc?export=view&id=0B8uoQ-Ue05dOMXhYcjJDbE9mcms",
	"https://drive.google.com/uc?export=view&id=0B8uoQ-Ue05dOTFJTT2w2Zll1TGc",
	"https://drive.google.com/uc?export=view&id=0B8uoQ-Ue05dOaF9hY0UtNEFiaVE"
 ],
	
 height:450,				// slides conteiner height
 background:'#FFF',			// background color and color of overlayer to fadeout on init
 autoStart:true,			// boolean autostart
 startDelay:0,				// start whit delay
 effectInterval:5000,			// time to swap photo
 effectTransition:1000,			// time effect
 pagination:[
 {
	active:true,			// activate pagination
	inner:true,			// pagination inside or aouside slides conteiner
	position:'B_C',			// pagination align:
						// T_L = top left
						// T_C = top center
						// T_R = top right
						// B_L = bottom left
						// B_C = bottom center
						// B_R = bottom right
	margin:10, 			// pagination margin
	dotStyle:'', 			// dot pagination class style
	dotStyleHover:'', 		// dot pagination class hover style
	dotStyleDisable:''		// dot pagination class disable style
 }]
 
});

</script>

```

Demo
---------------

http://leodudedev.github.io/responsiveSlides/

