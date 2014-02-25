# jQzoom Evolution Library

## Javascript Image magnifier

Written by Marco Renzi, http://www.mind-projects.it

*Features:*

*  based on jQuery
*  zoom with separate magnifier
*  zoom directly inside image
*  multiple customization options
*  support for large images
*  support for multiple images / galleries
  
*Updates:*

*  improved support of current browsers
*  improved support for large images

*Examples / Docu:*

http://www.mind-projects.it/projects/jqzoom/

*Installation:*

1. copy jqzoom-files to your webserver's `DocumentRoot`, e.g. inside dir `/js/jqzoom/`
2. copy jquery-files to your webserver's `DocumentRoot`, e.g. inside dir `/js/jquery/`
3. insert HTML tags for CSS and JS files:  
  <link rel="stylesheet" type="text/css" href="http://mydomain.com/js/jqzoom/css/jquery.jqzoom.css">  
  <script type="text/javascript" src="http://mydomain.com/js/jquery.min.js"></script>  
  <script type="text/javascript" src="http://mydomain.com/js/jqzoom/js/jquery.jqzoom-core.js"></script>  
4. insert jQuery call to init the jQzoom script:  
  $(document).ready(function() {  
    $('.imageZoom').jqzoom();  
  });  
5. insert HTML tags for displaying an image:  
  <a id="imageZoom" href="http://mydomain.com/images/test_a.jpg" title="" rel="gallery1">  
    <img id="imageZoom_img" src="http://mydomain.com/images/test_a.jpg" title="Magnifier" />  
  </a>  

