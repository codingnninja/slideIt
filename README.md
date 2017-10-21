# slideIt
It is a css library just like animate css but for image slide show...


To use this library, you can study below html code and play with below classes.

  	slideUp
  	slideDown
  	slideLeft
  	slideRight
  	assorted
  	assortedUpLeft
  	assortedUpRight
  	assortedDownLeft
  	assortedDownRight
  	

	<div class="slide-it">
		<div class="slideShow">

			<div class="image">
				<!-- TO dispay three images, don't add the effect here -->
				<img src="bg2.jpg" class = "" alt>
				<h1 class = "">
					Learn and move forward
				</h1>
			</div>


			<div class="image">
				<!--To display two images, remove waitForTwelveSeconds start fadeOut infinite here--> 
				<img src="bg1.jpg" class="waitForTwelveSeconds start slideLeft infinite" alt>
				<h1 class = "text waitForTwelveSeconds start slideLeft infinite">
					Solve the problem
				</h1>
			</div>


			<div class="image">
				<img src="ayo.jpg" class="waitForSixSeconds start slideRight infinite" alt>
				<h1 class = "text waitForSixSeconds start slideRight infinite">
					Create a problem for yourself...
				</h1>
			</div>


		</div>
	</div>

	<div class="displayOthers"> This is another very important thing we have to work on this day</div>


How chech it out and play with on https://codepen.io/codingnninja/pen/MERWJZ

