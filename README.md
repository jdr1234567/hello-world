7dr.org free-for-all non-commercial site. Current host is Weebly

A

/* Colorings:
* #FA053A; Vivid Red	
* #E6FFFF = 95% light blue bgrnd	
* #FF8C00 = Dark Orange	
* #FB7200 = Glow Orange	
* #05FA26 = Glow Green	
* #0099FF = bright blue	
* #CC5500 = Burnt Orange	
* #fd5f00 = Links, Bright Orange	
*/	
	
/* Resets	
--------------------------------------------------------------------------------*/	
ul, ol, li, h1, h2, h3, h4, h5, h6, pre, form, body, html, p, blockquote,	
fieldset, input {	
	margin: 0;
	padding: 0;
}	
	
a img {	
	border: 0;
}	
	
a {	
	text-decoration: none;
	border: 0;
	outline: 0;
}	
	
:focus {	
	outline: 0;
}	
	
/* Fonts	
--------------------------------------------------------------------------------*/	
	
@font-face {	
    font-family: 'bebas_neueregular';	
    src: url('images/BebasNeue-webfont.eot');	
    src: url('images/BebasNeue-webfont.eot?#iefix') format('embedded-opentype'),	
         url('images/BebasNeue-webfont.woff') format('woff'),	
         url('images/BebasNeue-webfont.ttf') format('truetype'),	
         url('images/BebasNeue-webfont.svg#bebas_neueregular') format('svg');	
    font-weight: normal;	
    font-style: normal;	
}	
	
@import url('//fonts.googleapis.com/css?family=Crimson+Text:600italic');	
	
/* General Styling and Structure	
--------------------------------------------------------------------------------*/	
	
html {	
  height:100%;	
}	
	
body {	
	width:100%;
    height:100%;	
	font-family: 'Patua One', sans-serif;
	font-size: 27px;
	line-height: 1;
	color: #555555;     
	background: #E6FFFF; /*95% light blue bgrnd*/ /*#f1f1f1;*/
	-webkit-font-smoothing:antialiased;
}	
	
.container, .wsite-footer {	
	margin: 0 auto;
	width: 100%;
	max-width: 1100px;
	box-sizing: border-box;
    padding: 0 2.5em;  	
}	
	
#banner-wrap,	
#main-content,	
#footer-wrap  {	
  width:100%;	
}	
	
a {	
/*	color:#07d3ee;  sky blue */
/*	-webkit-transition: all 0.3s ease-in-out;
	-moz-transition: all 0.3s ease-in-out;
	-o-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;         */
}	
	
a:hover, #commentUserInfo a:hover {	
	color: #05FA26; /*=Glow Green*/ /*#05bfd8;= blue green */
}	
	
h2 {	
	line-height: 1.2;
	color: #333;  
	font-size: 0.1em; /*1.875em;*/
	font-weight: normal;
	margin: 0 auto .77em;   /* .25em; */
}	
	
.wsite-content-title {	
  font-size: 1.0em;	
  font-family: 'Patua One', 'Crimson Text', serif;	
  font-style: italic;	
  font-weight: 700;	
  text-align: center;	
}	
	
p {	
	line-height: 1.25;
	padding: .07em 0;
}	
	
blockquote {	
	background: url(images/jumping-bottlenose-dolphins_2_orig) repeat-x;
	font-family: 'Patua One', sans-serif;
	font-size: 1.250em;
	font-style: italic;
	line-height: 1.5em !important;
	color: #777;
	padding: 0em 1em 1em 1.7em !important; 
	margin: 1em 1em !important; 
	border-left: 0px !important;
}	
	
	
div#content {min-height:400px;}	
	
/* Header	
--------------------------------------------------------------------------------*/	
/*	
* .main_menu ul:first-child > li > a {                         	
*    line-height: 180px  !important;	
* }	
*	
* .header-scrolled .main_menu ul:first-child > li > a {	
*    line-height: 62.5px  !important;	
* }                                                            	
* http://www.kriesi.at/support/topic/id-like-to-move-menu-text-nav-bar-down/ */	
	
.wsite-logo a {	
  color: #E6FFFF; /* 95% Very Light Blue */	
}	
	
.wsite-logo a img {	
  max-width: 100%;	
}	
	
#header-wrap {	
  position: relative;	
	width: 100%;
	right: 0;
	background-color: #0099FF; /*= bright blue*/ /*rgba(0, 0, 0, 0.3);*/  
	z-index: 5; 
	padding: 30px 15px 20px;  /* my addition */
  -webkit-transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important;	
  -moz-transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important;	
  -o-transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important;	
  -ms-transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important;	
  transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important;	
}	
	
 .stuck {	
  position: fixed !important;	
}  	
	
.darken #header-wrap {	
	background-color: #CC5500; /*=Burnt Orange*/ /*#FB7200;=Glow Orange*/ /*rgba(102, 102, 102, 0.95);*/
}	
	
#header table{	
	/* border-collapse: collapse; */
	border-spacing: 0px;
    width: 100%;	
}	
	
#header table td {	
	vertical-align: middle;
	text-align: right;
}	
	
.wsite-logo {	
    font-family: "Crimson Text",serif;	
    font-size: 2.25em;	
    font-weight: 600;	
	font-style : italic;
	text-shadow: 0px 1px 1px rgba(0, 0, 0, 0.137); /* Light Gray */
}	
	
#banner h2 {	
	font-family:'bebas_neueregular';
	font-size: 2.75em;
	text-shadow: 0px 1px 1px rgba(0, 0, 0, 0.35);
	color:#fff;
	letter-spacing:2px;
	margin: 0px auto;
}	
	
.wsite-headline-paragraph {	
  font-size: 0.875em;	
  font-family: 'Patua One', sans-serif;	
  color: rgb(255, 255, 255);	
  font-weight: bold;	
  text-transform: uppercase;	
  text-align: center;	
  letter-spacing: 2px;	
  text-shadow: 0px 1px 1px rgba(0, 0, 0, 0.196); 	
}	
	
.wsite-background {	
	background: url(images/jumping-bottlenose-dolphins_2_orig) repeat-x;
}	
	
	
/* Header: Search Box	
--------------------------------------------------------------------------------*/	
	
.search {	
    max-width: 210px;	
}	
	
.wsite-search {	
	vertical-align: middle;
}	
	
.search .wsite-search-input {	
  background: transparent;	
  border-color: transparent;	
  border-radius: 5px;	
  border-style: solid;	
  border-width: 1px;	
  float: right;	
  height: 34px;	
  padding: 0 32px 0 15px !important;	
  width: 100%;	
  color: #fff;	
  box-sizing: border-box;	
}	
	
.wsite-search-button {	
    height: 19px;	
    position: relative;	
    top: 8px;	
    width: 19px;	
    background: url(images/search-icon.png) no-repeat;	
}	
	
#header .wsite-search {	
  width: 210px;	
}	
	
#header .search .wsite-search-input {	
  max-width: 105px;	
  font-family: 'Patua One', sans-serif;	
  color: #ffffff;	
  font-size: 13px;	
  -webkit-transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important;	
  -moz-transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important;	
  -o-transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important;	
  -ms-transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important;	
  transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important;	
}	
	
#header .search .wsite-search-input:focus, .wsite-search-input.expanded {	
  max-width: 200px !important;	
  background: none repeat scroll 0 0 rgba(0, 0, 0, .25) !important;	
}	
	
#header .wsite-search-button {	
  position: absolute;	
  right: 10px;	
}	
	
#header .search .wsite-search-input:focus + .wsite-search-button, .expanded + .wsite-search-button {	
  z-index: 1;	
}	
	
#header ::-webkit-input-placeholder {	
   color: #ffffff;	
   text-transform: uppercase;	
   font-family: /*'Lato',*/ sans-serif;	
   font-size: inherit;	
   font-weight: bold;	
}	
	
#header :-moz-placeholder { /* Firefox 18- */	
   color: #ffffff;	
   text-transform: uppercase;	
   text-transform: uppercase;	
   font-family: /*'Lato',*/ sans-serif;	
   font-size: inherit;	
   font-weight: bold;	
}	
	
#header ::-moz-placeholder {  /* Firefox 19+ */	
   color: #ffffff;	
   text-transform: uppercase;	
   text-transform: uppercase;	
   font-family: 'Lato', sans-serif;	
   font-size: inherit;	
   font-weight: bold;	
}	
	
#header :-ms-input-placeholder {	
   color: #ffffff;	
   text-transform: uppercase;	
   text-transform: uppercase;	
   font-family: /*'Lato',*/ sans-serif;	
   font-size: inherit;	
   font-weight: bold;	
}	
	
/* Navigation	
--------------------------------------------------------------------------------*/	
	
#nav-trigger, .mobile-trigger, #navmobile {	
  display: none;	
}	
	
#nav-wrap {	
	clear: both;
	overflow: hidden;
	position: relative;
}	
	
#nav-wrap ul {	
	list-style: none;
  text-align: center;	
}	
	
#nav-wrap ul li {	
    display: inline-block;	
    list-style: none !important;	
    vertical-align: top;	
}	
	
#nav-wrap ul span:last-child li,	
#nav-wrap ul > li:last-child {	
	background: none;
}	
	
#nav-wrap ul li a {	
	display: block;
	font-family: 'Patua One', sans-serif;
	color: #05FA26; /*GlowGreen*/ /*#ffffff;*/
    padding: 13px 15px 15px; */	
	list-style-type: none;
	font-size: 1.2em; /*0.8em;*/
	font-weight: bold;
	text-transform:uppercase;
}	
	
#nav-wrap ul li#active a,	
#nav-wrap ul li a:hover {	
    background:  #ff8c00; /*=Dark Orange, #FA053A= Vivid Red*/ 	
	border: 0;
}	
	
/* Navigation Submenu's	
--------------------------------------------------------------------------------*/	
	
#wsite-menus .wsite-menu-wrap {	
	margin-top: 0.1px; /*1px !important;*/
}	
	
#wsite-menus .wsite-menu li{	
	width: /*183px;*/ 197px;
}	
#wsite-menus .wsite-menu-title {	
    padding: 10px !important;	
}	
#wsite-menus .wsite-menu li a {	
    border: 0 none;	
  	/* color:#fff; */)
	background: rgba(0, 0, 0, .3);
	color: /* #05fa26;*/  #ff8c00; /*Dark Orange*/
	font-size: 14px;
    padding: 5px;	
	font-family: 'Patua One', sans-serif;
}	
	
.darken #wsite-menus .wsite-menu li a {	
    background: #F1FF00; /*Yellow Hghlight*/ 	
	/* background: rgba(102, 102, 102, 0.95); */
}	
	
#wsite-menus .wsite-menu li a:hover {	
    background: #05FA26; /*GlowGreen*/	
	/* background: rgba (0,255,255);  (0, 0, 0, .4); */ 
}	
	
.darken #wsite-menus .wsite-menu li a:hover {	
    /* background: #05FA26; GlowGreen */	
	background: #F1FF00; /* = Yellow Highlight */
	/* background: rgba (255,255,0);  (65, 65, 65, 0.95); */  
}	
	
	
/* Mobile Nav	
--------------------------------------------------------------------------------*/	
	
#navmobile .search {	
  position: absolute;	
  top: 8px;	
  left: 26px;	
}	
	
#navmobile .wsite-search-input {	
  background: transparent;	
	   color: #555555;      
  text-align: center;	
}	
	
#navmobile .wsite-search-button {	
  background: url(images/search.png);	
}	
	
#navmobile a, #navmobile li {	
	display: block !important;
  text-align: left;	
  font-size: 1.1em;	
  padding-left: 0;	
  padding-right: 0;	
	color: #0000FF; /*=Deep Blue*/ /* #F1FF00;=Yellow*/ 
}	
	
#navmobile a {	
  padding: 15px;	
  text-align: center;	
  line-height: 1.0; /*1.2;*/	
  border-top: /*1px*/ 0.1px solid #d9d9d9; /* light gray */	
}	
	
#navmobile ul > li:last-child a {	
  border-bottom: /*1px*/ 0.1px solid #FFFFFF; /* #0099FF; /*= bright blue*/ /*#e1e1e1; very light gray */	
}	
	
#navmobile .wsite-menu-wrap {	
  max-height: 0;	
}	
	
#navmobile .expand .wsite-menu-wrap {	
  max-height: 400px;	
}	
	
.wsite-menu-arrow {	
  display: none !important;	
}	
	
.wsite-menu-mobile-arrow {	
  display: inline-block !important;	
  font-size: inherit !important;	
  padding: /*0 5px;*/  0  1px; 	
}	
	
.wsite-menu-mobile-arrow::before {	
  display: inline-block;	
  content: '\203A';	
  vertical-align: bottom;	
}	
	
.wsite-menu-back-item .wsite-menu-mobile-arrow {	
  padding: /*0 5px 0 0;*/ 0 1px 0 0; 	
}	
	
.wsite-menu-back-item .wsite-menu-mobile-arrow::before {	
  content: '\2039' !important;	
}	
	
	
/* Universal banner	
-------------------------------------------------------------------------------*/	
/*	
#banner p {	
	margin-bottom: 1.2em;
}	
	
#banner .wsite-button-inner {	
	text-transform:uppercase;
	font-weight:700;
}	
	
#banner-inner {	
  padding: 1em 0;	
}	
	
#banner .button-wrap {	
  display: inline-block;	
}	
*/	
	
	
/* Page type: Tall header	
--------------------------------------------------------------------------------*/	
	
.tall-header-page #banner:after {	
  content: '';	
  display: table-cell;	
}	
	
#banner-wrap .container {	
	height:100%;
}	
	
.tall-header-page #banner {	
	display: table;
  table-layout: fixed;	
	vertical-align:middle;
	height:30em;
}	
	
.tall-header-page #banner-inner * {	
  text-align: center !important;	
}	
	
	
/* Page type: Short header	
--------------------------------------------------------------------------------*/	
	
.short-header-page .wsite-logo {	
  font-size: 1.75em;	
  float:left;	
	margin-right:1.15em;
	line-height:1;
}	
	
.short-header-page #wsite-title {	
  display: block;	
}	
	
.short-header-page #banner-inner h2 {	
	float:right;
	font-size: 3em;
  text-align: left;	
}	
	
.short-header-page #banner-inner h2 .wsite-headline {	
  display: inline-block;	
  padding-left: 50; /* 1em; */	
  background: url(images/banner-divider.png) no-repeat left center;	
}	
	
.short-header-page #banner {	
	display:table;
	vertical-align:middle;
	height: 15em;
}	
	
	
/* Page type: No header	
--------------------------------------------------------------------------------*/	
/*	
.no-header-page .wsite-logo {	
    font-size: 1.75em;	
	line-height:1em; 
	margin-right:1.5em; 
}	
	
.no-header-page #banner-inner {	
    text-align: left;	
}	
	
.no-header-page #banner-wrap {	
	background: #07d3ee /* sky blue */
	       /*     url(DolphinsFolder/C.10Bright-50ContrastDolphins.png) repeat-x; */
/*	
}	
	
.no-header-page #banner {	
    width: 100%;	
	display: table;
	height: 8em;
	vertical-align:middle; 
} 	
*/	
	
	
/* Page type: Landing page	
--------------------------------------------------------------------------------*/	
	
.landing-page #banner {	
  display: table;	
  table-layout: fixed;	
  height: 42em;	
}	
	
.landing-page #banner:after {	
  content: '';	
  display: table-cell;	
}	
	
#banner-inner {	
    display: table-cell;	
    text-align: center;	
    vertical-align: middle;	
    width: 50%;	
}	
	
.landing-page #banner-inner * {	
  text-align: center !important;	
}	
	
/* Main Content	
--------------------------------------------------------------------------------*/	
	
  #main-wrap {	
  position: relative;	
  display: table;	
  table-layout: fixed;	
  width: 100%;	
  height: 0%;      /* 1%; */ /*100%;*/	
  right: 0;	
  background: #E6FFFF; /* light blue */  /*#ffffff;*/	
  z-index: 2; 	
  -webkit-transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important;	
  -moz-transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important;	
  -o-transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important;	
  -ms-transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important;	
  transition: all 300ms cubic-bezier(0.55, 0.085, 0.68, 0.53) !important; 	
} 	
	
	
#main-content {	
  position: relative;	
  background: #E6FFFF; /*#fff;*/	
  z-index: 1; 	
 }	
	
#main-content .container, .wsite-footer {	
  padding: 0em; /* 2.5em; */	
}	
	
.wsite-social {	
  white-space: normal;	
}	
	
.wsite-social .wsite-social-item:before, .wsite-social .wsite-social-item:after {	
  color: #ffffff;	
  font-size: 16px;	
}	
/*	
.wsite-social .wsite-social-item {	
  display: inline-block;	
  margin: 0 5px 10px;	
  color: #ffffff;	
  background: #07d3ee;	
  border-radius: 100%;   */	
}	
	
.wsite-social .wsite-social-item:before {	
  display: block;	
  padding: 8px !important; 	
}	
	
.wsite-social .wsite-social-item:hover {	
  background: #05FA26; /*=Glow Green*/  /*#05bfd8; /* blue green */	
}	
	
	
/* Store	
--------------------------------------------------------------------------------*/	
	
	
.wsite-com-content {	
  padding: 0 !important;	
}	
	
/* Category Blocks */	
	
.wsite-com-category-product-image-wrap, .wsite-com-category-product-featured-image-wrap, .wsite-com-category-subcategory-image-wrap, .wsite-product-image {	
  border-color: #cccccc; /*light gray*/	
  border-radius: 0;	
}	
	
	
.wsite-com-category-subcategory-name-bg {	
	-webkit-transition: all 0.3s ease-in-out;
	-moz-transition: all 0.3s ease-in-out;
	-o-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;
}	
	
.wsite-com-category-subcategory-name {	
  bottom: 0;	
  width: 100%;	
  text-align: center;	
  padding: 1em;	
  box-sizing: border-box;	
}	
	
.wsite-com-category-subcategory-name-text {	
	color: #ffffff;
	font-size: .85em;
  font-weight: bold;	
  font-style: italic;	
  text-shadow: none;	
  text-align: center;	
  text-transform: uppercase;	
  padding: 0;	
	-webkit-transition: all 0.3s ease-in-out;
	-moz-transition: all 0.3s ease-in-out;
	-o-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;
}	
	
.wsite-com-category-subcategory-link:hover .wsite-com-category-subcategory-name-bg, .wsite-com-category-subcategory-link:focus .wsite-com-category-subcategory-name-bg{	
  background-color: #05FA26; /*= Glow Green*/  /* #07d3ee;= blue green */	
  opacity: 1;	
}	
	
/* Sidebar */	
	
#wsite-com-store #wsite-com-hierarchy ul {	
  font-size: 1.125em;	
}	
	
#wsite-com-store #wsite-com-hierarchy ul ul {	
  font-size: .85em;	
}	
	
#wsite-com-hierarchy .wsite-link-unselected:hover {	
  color: #05FA26; /*=Glow Green /*#07d3ee;*/	
}	
	
/* Product page */	
	
#wsite-com-product-images-strip {	
  margin-top: 15px;	
}	
	
#wsite-com-product-images-strip .wsite-com-product-images-secondary-outer {	
  border-radius: 0px;	
  box-shadow: none;	
  margin-right: 15px;	
  padding: 0;	
	border:1px solid #cccccc; /* light gray */
}	
	
#wsite-com-product-list {	
  text-align: center;	
	font-size:1em;
}	
	
.wsite-com-product-price, .wsite-product-price {	
  text-align: center;	
	color:#000;
	font-size: 1em;
}	
	
#wsite-com-product-info {	
	color: #777;                    
}	
	
.wsite-com-product-option-color .wsite-com-product-option-color-swatch {	
  width: 14px;	
  height: 14px;	
  border-radius: 20px;	
  border: 2px solid #fff;	
}	
	
.wsite-com-product-option-color-swatch.wsite-selected {	
  background-image: none;	
  box-shadow: 0 0 0 1px rgba(0,0,0,0.3);	
}	
	
.wsite-com-product-option-color .wsite-com-product-option-color-container {	
  box-shadow: none;	
}	
	
#wsite-com-product-quantity-input {	
  width: 100px !important;	
  height: auto;	
  padding: .25em .5em !important;	
}	
	
.wsite-com-price, .wsite-com-sale-price {	
	font-size: .85em;
}	
	
.wsite-com-category-product-image-wrap, .wsite-com-category-product-featured-image-wrap, .wsite-com-category-subcategory-image-wrap {	
  border: none !important;	
}	
	
#wsite-com-product-info-inner {	
  position: relative;	
  padding-bottom: 120px;	
}	
	
#wsite-com-product-social-sharing {	
  position: absolute;	
  width: 100%;	
  bottom: 0;	
  right: 0;	
  padding: 13px 0 10px;	
  text-align: center;	
  border-top: 1px solid #ccc;	
  border-bottom: 1px solid #ccc;	
}	
	
#wsite-com-product-social-sharing:before {	
  content: 'Share this';	
  display: inline-block;	
  background: #fff;	
  position: absolute;	
  top: -10px;	
  left: 50%;	
  margin-left: -50px;	
  width: 100px;	
}	
	
#wsite-com-product-title {	
	font-family: 'Lato', sans-serif;
	font-size: 1.5em;
	margin-bottom: .25em;
	font-weight: bold;
}	
	
#wsite-com-product-price-area {	
  border-bottom: none;	
  margin-bottom: 0;	
}	
	
#wsite-com-product-price-area .wsite-com-product-price-container {	
	font-size:0.825em;
	font-family: 'Lato', sans-serif;
	font-weight:700;
	color:#555555;      
}	
	
#wsite-com-product-options, .wsite-com-product-option-groups {	
  border: none;	
  margin-top: 0;	
}	
	
.wsite-com-product-option, #wsite-com-product-inventory, #wsite-com-product-buy {	
  padding-top: 2em;	
}	
	
.wsite-com-product-option-label {	
  margin: 0 0 3px;	
}	
	
.wsite-com-product-title {	
  font-weight: normal;	
}	
	
#wsite-com-product-quantity-input {	
	
}	
	
/* Product Element */	
	
.wsite-product {	
  padding: 0;	
  border: none;	
  box-shadow: none;	
}	
	
.wsite-product-top, .wsite-product-button-wrap {	
  float: none;	
  text-align: left;	
  width: auto;	
}	
	
.wsite-product-image-wrap {	
  margin-right: 40px;	
}	
	
.wsite-com-continue-shopping .caret {	
  vertical-align: middle;	
}	
	
/* Blog	
--------------------------------------------------------------------------------*/	
.blog-post h2 {	
	font-family: 'Lato', sans-serif;
	font-size: 1.375em;
}	
	
.blog-sidebar h2 {	
	font-family: 'Lato', sans-serif;
	font-size: 1em;
}	
	
.blog-title a {	
	font-size: 1.375em;
	color: #333; /* dark blackish gray */
	font-weight:700;
}	
	
.blog-sidebar p {	
	font-size:0.875em;
}	
	
.blog-content .paragraph {	
	color:#777;  
}	
	
.blogCommentHeading .blogCommentDate {	
	float:left;
	color:#777;
	font-size:0.813em;
	text-shadow:none;
}	
	
.blogCommentOwner, .blogCommentOwner .blogCommentHeading, .blogCommentOwner .blogCommentHeadingInner {	
    background-image: none;	
}	
	
.blogCommentOwner .blogCommentHeading .blogCommentAuthor, .blogCommentHeading,	
.blogCommentHeading .blogCommentHeadingInner, .blogCommentHeading .blogCommentAuthor {	
    background-image: none;	
}	
	
.blogCommentHeading .blogCommentAuthor a.link {	
	display:none;
}	
	
.blogCommentHeading .blogCommentAuthor span.name, .blogCommentHeading .blogCommentAuthor a.name {	
  color: #3b3b3b !important; /* brownish gray */	
  margin: 0 1em 0 0;	
	font-size:0.938em;
	font-family: 'Lato', sans-serif;
	font-weight:700;
	text-transform: capitalize;
}	
	
.blogCommentHeading {	
	margin:0px;
}	
	
.blogCommentWrap {	
	background: url(images/person-img.png) no-repeat 0px 10px;
	padding-left:65px;
}	
	
.blogCommentReplyWrapper iframe {	
    height: 470px;	
}	
	
.blog-post .blog-separator {	
    border-bottom: none;	
}	
	
.blog-button {	
    background: none repeat scroll 0 0 #07d3ee;	
    color: #fff !important;	
	border-radius: 0.188em;
    display: inline-block;	
    font-size: 1em;	
    padding: 0.688em 1.7em;	
}	
	
.blog-button:hover {	
	background: #05FA26; /*=Glow Green*/  /*#05bfd8;*/
}	
	
.blog-button span {	
    background: none repeat scroll 0 0 #07d3ee;	
    border-radius: 0.188em;	
    display: block;	
    font-size: 1em !important;	
    height: auto;	
    line-height: 1.188em;	
	font-family: 'Lato', sans-serif;
}	
	
.blog-button:hover span {	
	background: #05FA26; /*=Glow Green*/ /*#05bfd8;*/
}	
	
.blog-button {	
	height:auto;
}	
	
.blog-button span {	
	margin:0px;
	padding:0px;
}	
	
/* Gallery	
--------------------------------------------------------------------------------*/	
	
.imageGallery .galleryCaptionInnerText p, .imageGallery .galleryCaptionInnerText {	
	font-weight:700 !important;
}	
	
.fancybox-skin {	
  background: transparent !important;	
  webkit-box-shadow: none !important;	
  -moz-box-shadow: none !important;	
  box-shadow: none !important;	
}	
	
.fancybox-overlay {	
  background: rgba(33, 33, 33, .9) !important;	
}	
	
.fancybox-close {	
  right: 20px;	
  top: 18px;	
}	
	
.fancybox-close,	
.fancybox-next span,	
.fancybox-prev span {	
  background: none !important;	
  width: auto;	
  height: auto;	
}	
	
.fancybox-close:before,	
.fancybox-next span:before,	
.fancybox-prev span:before {	
  font-size: 50px;	
  line-height: .5;	
  color: #fff !important;	
}	
	
.fancybox-close:hover:before,	
.fancybox-next:hover span:before,	
.fancybox-prev:hover span:before {	
  color: #fff !important;	
}	
	
.fancybox-close:before {	
  font-family: 'Calibri';	
  font-size: 50px;	
  content: '\00D7';	
}	
	
.fancybox-prev span:before {	
  content: '\3008';	
  font-family: arial;	
}	
	
.fancybox-next span:before {	
  content: '\3009';	
  font-family: arial;	
}	
	
.fancybox-title {	
  font-size: 1em;	
  color: #fff;	
}	
	
#fancybox-thumbs ul li a {	
  border: none;	
}	
	
#fancybox-thumbs ul li.active {	
  opacity: 1;	
}	
	
/* Splash Page	
--------------------------------------------------------------------------------*/	
	
	
body.splash-page .wsite-background {	
  background-attachment: fixed;	
}	
	
.splash-page #header-wrap {	
  position: absolute;	
  top: 0;	
}	
	
.splash-page .sticky-wrapper {	
  height: 0 !important;	
}	
	
.splash-page .wsite-button {	
	font-weight: 700 !important;
}	
	
.splash-page .wsite-button-inner {	
	text-transform: uppercase;
}	
	
.splash-page .wsite-background,	
.splash-page #main-wrap {	
	background: url(images/background.jpg) no-repeat center center /cover;
}	
	
.splash-page #main-wrap {	
  height: 100%;	
  overflow: visible;	
}	
	
.splash-page #splash-wrap {	
	display: table;
  table-layout: fixed;	
  height: 100%;	
  vertical-align: middle;	
  width: 100%;	
}	
	
#splash-main {	
  position: relative;	
  width: 100%;	
	height:100%;
	display: table;
  table-layout: fixed;	
  z-index: 2;	
}	
	
.splash-inner {	
	display: table-cell;
	vertical-align: middle;
	padding: 3em 0;
}	
	
.splash-content {	
	padding:22px;
	text-align:center;
	width: 50%;
	color:#fff;
}	
	
.splash-content #wsite-content {	
	text-align: center;
}	
	
.splash-content h2 {	
	font-weight:400;
	color: #fff;
	font-family: "bebas_neueregular";
	font-size: 4.75em;
	letter-spacing: 1.9px;
	text-shadow: 0 1px 1px rgba(0, 0, 0, 0.137);
  margin: 0 auto;	
}	
	
.splash-content p {	
	color: rgb(255, 255, 255);
	font-family: "Lato",sans-serif;
	font-size: 0.875em;
	font-weight: bold;
	letter-spacing: 2px;
	text-align: center;
	text-shadow: 0 1px 1px rgba(0, 0, 0, 0.196);
	text-transform: uppercase;
}	
	
.splash-page #banner, .splash-page #footer-wrap  {	
	display:none;
}	
	
/* Footer	
--------------------------------------------------------------------------------*/	
#footer-wrap {	
	text-align:right;
	color: #0000FF; /* = deep blue */ /* Matthew 11:28-30 */
	background: #E6FFFF; /* = 95% light blue bgrnd */ 
    overflow: visible;	
}	
	
#footer-wrap .wsite-footer {	
	
}	
	
#footer-wrap .wsite-footer h2 {	
	font-size: 0.80em;
	font-family: 'Lato', sans-serif;
	font-weight: 700;
	text-transform:uppercase;
	color:#555555; 
}	
.wsite-footer p {font-size: 0.77em;}  /*0.813em;}*/	
.wsite-footer a { color: #fd5f00;} /* = Links, Bright Orange */	
.wsite-footer blockquote {font-size: 0.813em;}	
	
#footer-wrap .wsite-form-container {	
	text-align:left;
	margin-top: 0 !important;
}	
	
/* Form Customization	
--------------------------------------------------------------------------------*/	
	
.formlist, .wsite-editor .formlist {	
  min-height: 50px;	
}	
	
.wsite-form-field {	
  text-align: left;	
  padding: 0 0 .5em;	
}	
	
.wsite-form-label {	
	display: inline-block;
	font-size: 1em;
	line-height: 1.5;
	font-weight: normal;
}	
	
.wsite-form-input,	
.form-select,	
.wsite-search-element-input,	
.field input[type="text"],	
.field textarea {	
  max-width: 100%;	
  padding: 0.5em !important;	
  background: none;	
  border: 1px solid rgba(153, 153, 153, 0.5);	
  border-radius: 3px;	
  color: inherit !important;	
  font-family: inherit !important;	
  line-height: 1 !important;	
  min-height: 36px !important;	
  box-sizing: border-box;	
}	
	
#wsite-search-submit {	
  border: none !important;	
}	
	
.wsite-form-input:focus,	
.form-select:focus,	
.wsite-search-element-input:focus,	
.field input[type="text"]:focus,	
.field textarea:focus {	
  border-color: #333333;	
}	
	
.wsite-form-field select,	
.wsite-com-product-option select {	
  -webkit-appearance: none !important;	
	-moz-appearance: none !important;
	appearance: none !important;
	background: url(images/select.png) no-repeat 97% center !important;
	padding: 5px;
	color: inherit;
}	
	
/* Custom Form: Radios & Checkboxes */	
	
.wsite-com-product-option-label input,	
.form-radio-container input {	
  display: none !important;	
}	
	
.wsite-com-product-option-label > span:before,	
.form-radio-container label:before {	
  content: '';	
  display: inline-block;	
  margin: 0 5px 0 1px;	
  color: #ffffff;	
	border: 4px solid #ffffff;
	-webkit-box-shadow: 0px 0px 0px 1px #d1d1d1;
  -moz-box-shadow:    0px 0px 0px 1px #d1d1d1;	
  box-shadow:         0px 0px 0px 1px #d1d1d1; /* light gray */	
  vertical-align: middle;	
  -webkit-transition: all 240ms linear;	
      -moz-transition: all 240ms linear;	
      -o-transition: all 240ms linear;	
      -ms-transition: all 240ms linear;	
      transition: all 240ms linear;	
}	
	
.wsite-com-product-option-label input[type="radio"] + span:before,	
.form-radio-container input[type="radio"] + label:before {	
  width: 10px;	
  height: 10px;	
  border-radius: 100%;	
}	
	
.wsite-com-product-option-label input[type="checkbox"] + span:before,	
.form-radio-container input[type="checkbox"] + label:before {	
  width: 10px;	
  height: 10px;	
}	
	
.wsite-com-product-option-label input:checked + span:before,	
.form-radio-container input:checked + label:before {	
  background: #07d3ee;	
}	
	
	
/* Buttons	
--------------------------------------------------------------------------------*/	
	
/* Small structure & regular style */	
	
.wsite-button,	
.wsite-editor .wsite-button {	
    background: #07d3ee; /* aqua blue */	
    color: #FFFFFF; /*F1F1F1;= WHITISh GRAY */  /* #0000FF; deep blue */  /* #fff !important; */  	
	border-radius: 0.188em; /* tab corners */
    display: inline-block;	
    font-size: 1em !important;	
    padding: 0;	
}	
	
.wsite-button:hover {	
	background: #05FA26; /*=Glow Green*/  /*#05bfd8;= blue green */
}	
	
.wsite-button-inner {	
    color: #fff !important;	
    background: none !important;	
    background-image: none !important;	
    display: block;	
    font-size: 1em !important;	
    height: auto !important;	
    line-height: 0.77 !important; /* 1.25 */	
    font-family: 'Arial Rounded', 'Maven Pro'; /*'Lato', sans-serif;*/	
    padding: 0.5em 0.5em; /* TopBottom LeftRight */ /* 0.65em 1.75em !important; */	
 }	
	
.wsite-button:hover .wsite-button {	
	background: /*#05bfd8;*/ rgba(0, 0, 0, 0.137); /* Light Gray*/
}	
	
.blog-button {	
	height: auto;
}	
	
.blog-button span {	
	margin:0px;
	padding:0px;
}	
	
.wsite-button.wsite-button-large {	
	font-size: 1.25em !important;
}	
	
.wsite-button-large:hover {	
 background: /*#05bfd8;*/ #05FA26; /*=Glow Green*/	
}	
	
	
.wsite-button-large .wsite-button-inner {	
    font-size: 0.938em;	
    padding: 4px 31px;	
}	
	
.wsite-button-large:hover {	
	background: /*#05bfd8;*/ #05FA26; /*=Glow Green*/
}	
	
	
/* Highlighted styles */	
	
	
.wsite-button-highlight,	
.wsite-editor .wsite-button-highlight {	
	background: #aeaeae !important;  /* light gray */
}	
	
.wsite-button-highlight:hover {	
	background: #969392 !important;  /* gray */
}	
	
	
/* Cart	
--------------------------------------------------------------------------------*/	
	
#wsite-mini-cart {	
  position: fixed !important;	
  top: auto !important;	
  width: 100% !important;	
  max-width: 450px !important;	
  overflow: auto;	
  box-sizing: border-box;	
  padding: 2em 2em 0em !important;	
  border-radius: 0;	
  background: #f5f6f6 !important;	
}	
	
#wsite-mini-cart .wsite-product-list {	
  display: block;	
  max-height: 275px;	
  overflow: auto;	
}	
	
#wsite-mini-cart .wsite-product-list .wsite-list-image-container {	
  margin: 5px !important;	
}	
	
#wsite-mini-cart .wsite-items-right {	
  padding-right: 5px;	
}	
	
#wsite-mini-cart .wsite-product-list > li {	
  display: table;	
  width: 100%;	
}	
	
#wsite-mini-cart .wsite-product-list > li > div {	
  padding-top: 0 !important;	
  padding-bottom: 0 !important;	
}	
	
#wsite-mini-cart:before, #wsite-mini-cart:after {	
  display: none !important;	
}	
	
#wsite-mini-cart .wsite-name-header, #wsite-mini-cart .wsite-product-price, #wsite-mini-cart .wsite-subtotal-wrapper {	
  color: #3b3b3b !important;	
  font-weight: bold;	
}	
	
.wsite-cart-bottom {	
  padding: 1em 0;	
}	
	
@media (min-width: 1024px) {	
  .wsite-product-list {	
    border-top: 1px solid rgba(153, 153, 153, 0.5);	
    border-right: 1px solid rgba(153, 153, 153, 0.5);	
    border-left: 1px solid rgba(153, 153, 153, 0.5);	
  }	
}	
	
/* Tablet + Mobile	
--------------------------------------------------------------------------------*/	
	
@media (max-width: 1024px) {	
	
  /* General */	
	
  body {	
  	font-size: 23px;
  }	
	
  #main-wrap {	
    position: relative;	
    background: #E6FFFF; /* #0099FF; =Bright Blue*/ /* #f1f1f1; */	
    -webkit-box-shadow: 1px 0px 0px 0px rgba(0, 0, 0, 0.1);	
    -moz-box-shadow:    1px 0px 0px 0px rgba(0, 0, 0, 0.1);	
    box-shadow:         1px 0px 0px 0px rgba(0, 0, 0, 0.1);	
  }	
	
  #main-content .container, .wsite-footer {	
    padding: .3em; 	
  }	
	
  /*  Collapse column within a column*/	
	
  .wsite-multicol-col .wsite-multicol-col {	
    max-width: 100% !important;	
    display: block;	
    width: auto !important;	
    margin: 0 auto .25em !important;	
  }	
	
  /* Nav */	
	
  #nav-trigger, #navmobile {	
    display: block;	
  }	
	
  #navmobile {	
  	position: fixed;
    right: 0;	
    top: 0;	
  	box-sizing: border-box;
    width: 270px; /*260px;*/	
    height: 100%;	
  	padding: 50px 0;
    background: #A1CAF1; /*baby blue eyes*/ /*#8d2424;=maroon*/ /*#f1f1f1;*/  /* #FB7200;= Glow Orange*/ /* #f1f1f1; */	
  	text-align: left;
  	overflow-y: auto;
  	opacity: 0;
    z-index: 1;	
  	-webkit-transition: opacity 0s .5s ease-in-out;
        -moz-transition: opacity 0s .5s ease-in-out;	
        -o-transition: opacity 0s .5s ease-in-out;	
        -ms-transition: opacity 0s .5s ease-in-out;	
        transition: opacity 0s .5s ease-in-out;	
	}
	
  #header > .container table {	
	
  	max-width: /*200px;*/ 180px;
  }	
	
	#nav-trigger:before {
  	content: "";
  	display: block;
  	background: url(images/menu.png) no-repeat center center;
    width: /*28px;*/  32px;	
    height: 22px;	
    background-size: contain;	
  }	
	
  #nav-trigger {	
	float: right;
	right: /*2.5em;*/  2.8em;
    margin: /*13px 0 15px;*/ 10px 0 10px;	
    color: #000000;	
	z-index: 12;
  }	
	
 body.menu-open  #navmobile {	
    opacity: 1;	
  	-webkit-transition: opacity 0s 0s ease-in-out;
        -moz-transition: opacity 0s 0s ease-in-out;	
        -o-transition: opacity 0s 0s ease-in-out;	
        -ms-transition: opacity 0s 0s ease-in-out;	
        transition: opacity 0s 0s ease-in-out;	
  }	
	
  body.menu-open  #main-wrap,	
  body:not(.wsite-checkout-page).menu-open  #main-wrap #header-wrap {	
    right: 270px;	
  }	
	
  #nav-wrap ul li, #header .search {	
    display: none !important;	
  }	
	
  #nav-wrap ul li.wsite-nav-cart, #nav-wrap ul li#member-login {	
    display: inline-block !important;	
    vertical-align: middle;	
    padding: 15px 15px 15px 0;	
  }	
	
  #member-login {	
    padding-left: 55px !important;	
    margin-right: -170px;	
  }	
	
  li#member-login:last-child {	
    padding-left: 0px !important;	
  }	
	
  #member-login a {	
    min-width: 100px;	
    padding: 0 !important;	
  }	
	
   #nav-wrap ul li.wsite-nav-cart {	
     padding-top: 5px;	
   }	
	
  /*Restyled Cart*/	
	
  #wsite-nav-cart-a {	
    text-indent: -9999px;	
    white-space: nowrap;	
    overflow: hidden;	
    width: 45px;	
    height: 30px;	
    padding: 0 !important;	
    text-align: left;	
    z-index: 5;	
  }	
	
  #wsite-nav-cart-a:after {	
    content: '';	
    display: block;	
    position: absolute;	
    left: 0;	
    bottom: 0;	
    background: url(images/icon-cart.png) no-repeat left center;	
  	background-size: contain;
    width: 28px;	
    height: 22px;	
  }	
	
  #wsite-nav-cart-num {	
    position: absolute;	
    padding: 5px;	
    background: /*#07d3ee;*/ rgba(0, 0, 0, 0.137); /* Light Gray */	
    font-family: helvetica;	
    text-indent: 0;	
    top: 0;	
    right: 0;	
    border-radius: 20px;	
    line-height: 1;	
    font-size: .85em;	
    min-width: 10px;	
    text-align: center;	
    z-index: 6;	
  }	
	
  #wsite-mini-cart {	
    position: fixed !important;	
    left: 0 !important;	
    top: 52px !important;	
  }	
	
  /* Layouts */	
	
  .splash-content {	
    margin: 0 auto;	
    width: 60%;	
  }	
	
  /*  Store and Blog sidebar collapse*/	
	
    #wsite-com-store .wsite-com-content-with-sidebar .wsite-com-category-product-featured-wrap {	
      margin: 0 10px 10px;	
    }	
	
}	
	
@media (max-width: 767px) {	
	
  /* General */	
	
	
  body {	
  	font-size: 32px;
  }	
	
  .wsite-multicol-col {	
    max-width: 100% !important;	
    display: block;	
    width: auto !important;	
    margin: /*0 auto 0.25em !important;*/ 0 auto 0.1em;	
  }	
	
  /* Layouts */	
	
 .wsite-section {	
    height: auto !important;	
  }	
	
  #banner-inner {	
    width: 100%;	
  }	
	
  #banner-inner td {	
    display: block;	
    text-align: left;	
  }	
	
	.wsite-logo {
	
	}
	
	.wsite-logo, .wsite-logo * {
    display: block;	
    max-width: 100%;	
	  margin: 0 auto !important;
	}
	
  #banner h2 {	
    font-size: 3em !important;	
  }	
	
  #banner h2 span, #banner h2 font, #banner p span, #banner p font {	
    font-size: inherit !important;	
    line-height: inherit !important;	
  }	
	
  .splash-content {	
    width: 100%;	
    padding: 0;	
  }	
	
  .landing-page #banner {	
    height: 26em;	
  }	
	
  .tall-header-page #banner {	
    height: 20em;	
  }	
	
  .short-header-page #banner {	
  	height: 14em;
  }	
	
  .short-header-page #banner-inner h2 .wsite-headline, .no-header-page #banner-inner h2 .wsite-headline {	
    padding-left: 0 !important;	
    background: none !important;	
  }	
	
  .short-header-page #banner-inner h2, .no-header-page #banner-inner h2, .short-header-page .wsite-logo, .no-header-page .wsite-logo {	
    float: none !important;	
  }	
	
	/* Gallery */
	
  .imageGallery .halfwidth-mobile {	
    width: 50% !important;	
  }	
	
	.galleryCaptionHolder {
	
	}
  /* Cart */	
	
	
  #wsite-mini-cart {	
    padding: 2em 2em 0em !important;	
  }	
	
  /* Store */	
	
  .wsite-com-sidebar, .wsite-com-content-with-sidebar {	
    display: block;	
    width: 100%;	
    margin: 0 auto;	
    padding: 0;	
    text-align: center;	
  }	
	
  .wsite-com-sidebar {	
    margin-bottom: 2em;	
  }	
	
  #wsite-com-store .wsite-com-category-subcategory-group .wsite-com-column, #wsite-com-store .wsite-com-category-product-featured-group .wsite-com-column,  #wsite-com-store .wsite-com-category-product-group .wsite-com-column {	
    width: 50% !important;	
  }	
	
  #wsite-com-product-images {	
    width: 100% !important;	
  }	
	
  #wsite-com-product-images, #wsite-com-product-images .wsite-com-column {	
    float: none !important;	
  }	
	
  #wsite-com-product-info {	
    margin-left: 0 !important;	
    margin-top: 25px;	
  }	
	
  /* Blog */	
	
  #blogTable > tbody > tr > td {	
    display: block !important;	
    width: 100% !important;	
    margin: 0 auto;	
    padding: 0 !important;	
  }	
  .blog-body {	
    float: none !important;	
  }	
  .blog-header {	
    text-align: left;	
  }	
  .blog-sidebar .column-blog {	
    width: 100%;	
    float: none;	
    padding-top: 3em;	
    border-top: 1px solid $btnHLnormal;	
  }	
	
  #commentPostDiv .commentInput, #commentPostDiv .commentTextarea {	
    padding: 0 12px !important;	
  }	
	
  /***************************************/	
	
  .blogCommentWrap {	
    background: none !important;	
    padding-left: 6px !important;	
  }	
	
  .blogCommentLevel1 {	
    margin-left: 20px !important;	
  }	
	
  .blogCommentLevel2 {	
    margin-left: 40px !important;	
  }	
	
  .blogCommentReplyWrapper iframe, .blogCommentSubreplyWrapper div.iframeWrapper {	
    padding: 0 !important;	
    height: 570px !important;	
    background: none !important;	
    border: none !important;	
  }	
	
 /*  Search Results */	
	
  #wsite-search-sidebar {	
   display: none;	
  }	
	
  #wsite-search-results, #wsite-search-product-results .wsite-search-product-result {	
    width: 100% !important;	
    padding: 0 !important;	
  }	
	
  #wsite-search-form-container {	
    float: none;	
    width: 100%;	
    margin-top: 10px;	
  }	
	
  /* Checkout */	
	
  #wsite-com-checkout-list .wsite-remove-button, #wsite-com-checkout-summary-list .wsite-remove-button {	
    display: block;	
    margin: 5px auto 0;	
    left: auto;	
    top: auto;	
  }	
	
  #wsite-com-checkout-cart-footer {	
    display: table;	
    table-layout: fixed;	
    width: 100%;	
  }	
	
  .wsite-com-continue-shopping {	
    display: table-cell;	
    vertical-align: middle;	
    width: 50%	
  }	
	
  h2.wsite-checkout-header {	
    padding-bottom: 0 !important;	
  }	
	
  .wsite-com-continue-shopping .caret, #wsite-com-checkout-list, #wsite-com-checkout-summary-list {	
    line-height: 2em;	
  }	
	
  #wsite-com-checkout-list .wsite-form-input:not(.wsite-coupon-input), #wsite-com-checkout-summary-list .wsite-form-input:not(.wsite-coupon-input) {	
    width: 25px;	
  }	
	
  #wsite-com-checkout-list .wsite-coupon-input, #wsite-com-checkout-summary-list .wsite-coupon-input {	
    width: 100px;	
  }	
	
  #wsite-com-checkout-list .wsite-com-checkout-item-image, #wsite-com-checkout-summary-list .wsite-com-checkout-item-image {	
    width: 50px !important;	
    height: 50px !important;	
  }	
	
  .wsite-com-continue-shopping .caret, #wsite-com-checkout-list, #wsite-com-checkout-summary-list {	
    font-size: .65em !important;	
  }	
	
  /* Checkout Page	
  ---------------------------------------*/	
	
  .wsite-com-checkout-payment-column,	
  .wsite-com-checkout-summary-column {	
    display: block !important;	
    width: auto !important;	
    max-width: 100% !important;	
    margin: 0 auto 1em !important;	
  }	
	
  #wsite-com-checkout-cart-footer {	
    text-align: center;	
  }	
	
  .wsite-com-continue-shopping {	
    display: block;	
    margin: 0 auto 5px;	
  }	
	
  #wsite-com-checkout-cart-footer form {	
    float: none !important;	
  }	
	
  #wsite-com-checkout-list,	
  #wsite-com-checkout-list * {	
    font-size: 12px !important;	
  }	
	
  #wsite-com-checkout-payment-order {	
    margin-left: 0;	
  }	
	
	
}
