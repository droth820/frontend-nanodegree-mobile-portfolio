## Website Performance Optimization portfolio project

This was by far the most challenging project to date. The tools I used to complete this project were:
1. Page Speed Insights
2. http://cssminifier.com/
3. http://validator.w3.org/#validate_by_input
	Valide HTML
4. http://jigsaw.w3.org/css-validator/
	Validate CSS
5. Photoshop CS5 for image optimization.
    I used photoshop to resize and save for web devices, which made file sizes smaller resulting in faster load times
    **I did not clean up images to remove white outlines, which came with original file.
6. ImageOptim (Application)
	After optimizing images with Photoshop I used ImageOptim to further compress image files for faster load time while maintaining quality.
7. Documentation on Google Developers focusing on Analyzing Critical 		Rendering Path Performance.
8. Sublime Text 2
9. Git Hub

Steps for optimization:
1. Optimized images
2. Inlined critical CSS
3. Minified CSS
4. Applied Bootstrap
5. Did not need to modify resizePizzas() to achieve 60fps
6. Amended for loop changing value of 'i' from 0 to 5.
	for (var i = 5; i < 100; i++) {
  		var pizzasDiv = document.getElementById("randomPizzas");
  		pizzasDiv.appendChild(pizzaElementGenerator(i));
	}
7. Changed sum/10 to sum/5
	console.log("Average time to generate last 10 frames: " + sum / 5 + "ms");
8. Within the Event listener I changed cols to 6 and s to 400 within the updatePositions() function.
	
	This decreased the amount of pizzas drawn on the screen. MovingPizzas1 was overly congested and took away from content on the page so I felt the need to minimize the amount in the background.

