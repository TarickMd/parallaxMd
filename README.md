
**parallaxMd**
==========
	Easy JQuery plugin to create parallax effect.
***

Working
-------
Plugin add background url to your block and create parallax effect.

*How to use?*
-------
Plugin works with the dom of your html like this:
 jQuery:
			
     $( document ).ready(function() {
            $("#someContainer").parallaxMd({
                "imgHeight": "500px",
			    "imgWidth": "80%",
			    "speed" : "15"
            });
     });
   HTML:
   			
     <div id="someContainer" data-mdparallax="img.jpg"> 
     </div>
 There is a possibility to change all input values.
 Defaults
-------
 - **imgHeight:** 300px;
 - **imgWidth:** 100%;
 - **speed:** 15

Important
---------
You need have JQuery lib.

Copyright
---------
Taras Dzhulai  (c) 2015