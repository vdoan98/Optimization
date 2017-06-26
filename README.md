
### Website optimization 
1. views/js/main.js:
	- Styling of pizzaImageContainer and pizzaDescriptionContainer take use of boostrap grid system instead of manual styling in JS
	- All document.querySelector are changed document.getElementById(); # are removed inside the brackets
	- All document.querySelectorAll are changed document.getElementsByClass(); . are removed inside the brackets.
	- document.querySelectorAll(".randomPizzaContainer") value is held in arrayLength
  	- newwidth and dx variables are instantiated outside of for loop
	- pizzaDivs is moved out of for loop
	- variable phrase is moved and instantiated outside of for loop
	- instead of 200 pizzas, 24 pizzas are created on screen 
	- updatePosition is changed so (document.body.scrollTop / 1250) isn't repeatedly calculated
2. pizza.html:
	- Styling that manual style using % is changed to boostrap grid system 
	- Google font is loaded with Javascript 
3. index.html
	- All images are compressed. 
	- Inline critical CSS 
4. views/images
	- pizzeria.jpg is compressed 
5. css/style.css
	- Critical CSS codes that were moved to index.html are commented out. 
6. minified files
	- index.html
	- perfmatters.js
	- style.css
	- print.css
