# Sugar Drop Down Bar #

*Description:*  Sugar Bar adds a drop down bar to the top of your page that's shown in a non intrusive manner, only when the page is scrolled and past the designated threshold (ie: &gt; 50px from the top of the page). It is ideal for pushing content that's optional yet merits user attention, such as an opt-in box or advertisement. The content inside the Sugar Bar can either be defined inline on the page, or inside a separate file and embedded via Ajax. A "close" button inside the Bar when clicked on dismisses the bar either just once, or for the entire user session.

## Directions ##

*Step 1:* This script uses the following external files:

+ jQuery 1.11 or above (served via Google CDN)
+ sugarbar.css.js
+ sugarbar.css
+ sugarcontent.htm (external file containing sugar bar markup)

*Step 2:* Add the below code to the HEAD section of your page:

	<link rel="stylesheet" href="sugarbar.css" />
	
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
	
	<script src="sugarbar.js">
	
	/***********************************************
	* Sugar Bar- (c) Dynamic Drive DHTML code library (www.dynamicdrive.com)
	* This notice MUST stay intact for legal use
	* Visit Dynamic Drive at http://www.dynamicdrive.com/ for this script and 100s more
	***********************************************/
	
	</script>
	
	<script>
	
	var mysugarbar
	
	jQuery(function(){ // on DOM load
		mysugarbar = new sugarbar({
			sugarbarid: 'sugarbar',
			externalfile: 'sugarcontent.htm',
			persistclose: false
		})
	})
	
	</script>

*Step 3:* Make sure your page contains the following in the HEAD section:

	<!doctype html>
	<meta name="viewport" content="width=device-width, initial-scale=1">


## Sugar Drop Down Bar ##

See script project page for additional details on setup and documentation: <http://www.dynamicdrive.com/dynamicindex17/sugarbar.htm>
