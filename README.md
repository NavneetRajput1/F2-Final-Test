# Generate token
Create a gallery using either a flex or grid layout that displays 4 images in a single row.
When the first image is clicked, a form appears where the user can register themselves by providing their name, email, and username.
The registered person's name and username should be displayed when the second image is clicked.
When the third image is clicked, it should display a picture of a dice. When clicking the dice, it should generate a random number between 1 and 6. The user should be able to click the dice 3 times. If the sum of the three generated values is greater than 10, the user should be able to click the fourth image. If the sum is not greater than 10, the user should be prompted to try again after scoring more than 10.
When the fourth image is clicked, a random 12-digit text should be generated as a coupon.
Ensure that the images can only be clicked once and in a specific order (from first to last). Once an image has been clicked, it should not be able to be clicked again. [10 marks]
If the user does not score more than 10 on their first attempt, they should be given one more chance to click the third and fourth images.
If the user fails to score more than 10 even after their second attempt, display the message "Bad luck" and do not give them another chance.
If the user can generate a coupon, display a congratulatory image.
