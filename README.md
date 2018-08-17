# liveBgZoom
LiveBgZoom is a low size and simple js library to add zoomin animation to your html elements backgrounds.
[demo](https://livebgzoomdemo.netlify.com/)

# add to webpage

1-download zip file and extract in your webpage directory
2-add jquery and css and js file to html file:
:
  
```
<head>
<link rel="stylesheet" href="css/livebg.css" />
</head>
```
at the end of body:
  
```
<script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
<script src="js/livebg.js"></script>
```
# usage
add 'lbg-container' class to the element you want and specify the zoom speed with one of the following classes(the default speed is normal you can set custom speed in livebg.css file and remove zoom-speed class):
-zoom-speed-slow
-zoom-speed-normal
-zoom-speed-fast
-zoom-speed-none(remove zoom animation)
```
<div class="lbg-container zoom-speed-normal"></div>
```




