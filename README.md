# 4xx

https://4xx.iambeardednbroke.com

inside out project version 400-0

	-added base code to index.html and added initial JavaScript to app.js.
	
inside out project version 401-0

	- created the appData object, moved the title & tag line variables in to appData and refactored the initializeApplication function.

inside out project version 401-1

	- added bootstrap to the index.html
	- added a DOM injection of the progress bar in the app.js
	- created the displayPB fucntion in the app.js

inside out project version 402-0

	- added style.css and linked in index.html
	- added login form function and call after progress bar is completed
	- added minimal validateLogin function to check for blank strings
	
inside out project version 403-0

	- index.html
		- updated all hrefs/links to passive protocol
		- moved style sheet link below animate and bootstrap to allow for custom styles to override all
		
	- style.css
		- added styles for application interface - sidebar, wrapper, navigation, etc.
	- app.js
		- added the applicationUserInterface function which defines the application user interface
		- added the buildMenu function which returns the nav mune and will increase in dynamic nav building
		- added the buildMenu function which returns the primary content area and will evolve to return content dynamically
		- replaced document write with call to applicationUserInterface function in the validateLogin function
		- added the linkClicked function which is called by click events on anchor elements and returns dynamically driven results
	
inside out project version 404-0

	-index.html
		- removed comments and cleaned code
    	- added script tag for quotes.js file
	- style.css
    	- modified the sidebar and sidebar ul classes 
    	- added the auth and infoDiv classes
	- app.js
		- added the quotArr sort to the initializeApplication function
		- modified buildMenu function to dynamically build the menu from the array
		- modified linkClicked function to dynamically populate main content with array content
	- added the assets/data/quotes.js file
	
inside out project version 405.0

	- index.html
    	- added script tag to pull in ajax.js file
	- style.css
		- modifed .contStage by adjusting the (left: 180px;) - changed value to 80px to close gap between side manu and the content
		- clead up comments
	- app.js
		- clead up comments
		- added sideMenu array to the appData object to be used to call ajax to load the pages & posts from the me site
		- modified the displayPB() function - changed preloader time from 50 to 15 to speed up load during development
		- modified the buildMenu() function to accept menu items from appData object - removed call to quotes array
		- modified the linkClicked() function 
			 - added conditional to evaluate if the object clicked is in the menu array of the appData.sidemenu object
			 - added ajax call to grab posts/pages
	- added the assets/data/ajax.js file
		
		