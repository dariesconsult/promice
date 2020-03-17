
# ABOUT PROMICE LIBRARY
Promice is a fully optimzed frontend library for creating user interactive experience on websites e.g Animations, slideshows, header navigations and layout designs. Its an extension of animate.css and gives you total control over your user experience designs.


# PROMICE USUAGE
To use promice in your website, simply drop the promice.css and promice.js into your document's head and add the required classes to elements in your document. That's it! 



# NAVBAR USUAGE
  1. create a ul with multiple li as preferred inside a html nav tag
  2. add class "navbar" to the container(nav) holding all elements
  3. add class "navbar-title" to the first li holding website title and class "navbar-toggle" to the second li holding toggle bar image or html toggle bar( &#9776; )
  4. add class "navbar-items" to the rest li tags


# LAYOUT USUAGE
 COLOR TYPE
  1. BACKGROUND CLASSES: "bg-red", "bg-white", "bg-blue", "bg-yellow", "bg-pink", "bg-green", "bg-purple", "bg-brown", "bg-black", "bg-orange".

  2. TEXT CLASSES:  "text-red", "text-white", "text-blue", "text-yellow", "text-pink", "text-green", "text-purple", "text-brown", "text-black", "text-orange".

  TEXT SIZES
  simply add the preferred class size; "text-small", "text-medium", "text-large"

  TEXT PADDING
  To adding padding simply add your preferred class. the numbers at the end of the class name = the size of the padding in px.
  Classes: "padding-0", "padding-10", "padding-15", "padding-20", "padding-25", "padding-30".

  TEXT ALIGN
  Align classes: "text-center", "text-left", "text-right"

  DIV ALIGN
  Align classes: "div-left", "div-right", "div-center"

  TO PUT MULTIPLE DIVS IN ONE CONTAINER DIV
  1. To align multiple divs in one container simply add the class "showcase" to the container div.
  2. Add the class "showcase-div" to the children div of the parent.
  
  Exception: If you don't want parent container padding simply add the class "Full-showcase"

  BLOCK ATTRIBUTE
  To create a billboard after the header of your html simply add the class "bg-block"

  To create a put a text in a box simply add the class "text-block"

  IMAGE ATTRIBUTES
  To create a rounded image simply add the class "round-image" to a block element containing the image e.g div.

  FIXED ELEMENT IN A POSITION
  1. To put any element in a fixed position, simply add the class "fixed"

#  BUTTON USUAGE
  1. CLASSES: "stylish-1", "stylish-2", "rounded-1", "rounded-2"
  2. INSTRUCTIONS: add any class attributes to preferred button elements

# ANIMATION CLASSES
To animate an element, add the class animate to an element. You can include the class infinite for an infinite loop. Finally you need to add one of the following classes to the element:

  bounce |	heartBeat	| flash	| rubberBand | shake |	headShake	| swing	| tada | wobble	| jello	| bounceIn | bounceInDown | bounceInLeft	| bounceInRight	| bounceInUp	| bounceOut | bounceOutDown	| bounceOutLeft | bounceOutRight	| bounceOutUp | fadeIn	| fadeInDown	| fadeInDownBig	| fadeInLeft | fadeInLeftBig	| fadeInRight	| fadeInRightBig	| fadeInUp | fadeInUpBig	| fadeOut	| fadeOutDown	| fadeOutDownBig | fadeOutLeft	| fadeOutLeftBig	| fadeOutRight	| fadeOutRightBig | fadeOutUp	| fadeOutUpBig	| flipInX	| flipInY | flipOutX	| flipOutY	| lightSpeedIn	| lightSpeedOut | rotateIn	| rotateInDownLeft	| rotateInDownRight	| rotateInUpLeft | rotateInUpRight	| rotateOut	| rotateOutDownLeft	| rotateOutDownRight | rotateOutUpLeft	| rotateOutUpRight	| hinge	| jackInTheBox | rollIn	| rollOut	| zoomIn	| zoomInDown |zoomInLeft	| zoomInRight	| zoomInUp	| zoomOut | zoomOutDown	| zoomOutLeft	| zoomOutRight	| zoomOutUp | slideInDown	| slideInLeft	| slideInRight	| slideInUp | slideOutDown	| slideOutLeft	| slideOutRight	| slideOutUp

#  ADDING DELAY AND SPEED
It's possible to add delays directly on the element's class attribute, just like this:

Class Name	Delay Time
delay-1s	    1s
delay-2s	    2s
delay-3s	    3s
delay-4s	    4s
delay-5s	    5s

It's possible to control the speed of the animation by adding these classes, as a sample below:

Class Name	Speed Time
slow	          2s
slower	        3s
fast	         800ms
faster	       500ms

# SLIDESHOW USUAGE
  1. To use slideshow simply create a parent div. 
  2. Inside the parent div create as many children divs as needed  with your images in each child div. 
  3. Add the class "slidesow" to the parent div and the class "slide" to all children divs containing the images.

  4. In each img tag add as many animation attributes as you like for different slide effects e.g
     

