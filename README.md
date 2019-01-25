# Giphy :fireworks: :tv:

# Overview

This app uses the GIPHY API to make a dynamic web page that populates with gifs of your choice. You create a button with a name of anythng you wish - amnimal, person, whatever. It just gets 10 images from GIPHY and displays them with their rating. The initial display of the image is static. When you click an image, it animates. When you click it again, it goes back to static. It is mobile responsive as well.

Specifics
When the user clicks on a button, the page grabs 10 static, non-animated gif images from the GIPHY API and place them on the page.

When the user clicks one of the still GIPHY images, the gif animates. If the user clicks the gif again, it stops playing.

Under every gif, display its rating (PG, G, so on).

You can type a name into the user input box, press add, and it will add another buttopn used to fetch GIFs. You can use that button like any other on the page.

Click the fav button to sav the image to a favorites section below the chosen images. This persists past refreshes bu utilizing local storage.

