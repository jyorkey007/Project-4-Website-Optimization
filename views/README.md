pizza.html/main.js Performance Changes:
	-Took all of newly created variables out of the for loops that were inside functions
	-Lowered amount of appended pizzas to the page from 200 to 20
	-Added translate style to for loop in updatePosition function

index.html Performance Changes:
	-Optimized Images
	-Compressed Images
	-Inlined CSS (print.css, style.css) 
	-Asnyched JavaScript sources (<script async src="http://www.google-analytics.com/analytics.js"></script>
	<script async src="js/perfmatters.js"></script>)
	-Prevented JavaScript and CSS render blocking
	-Deleted Google Fonts  
