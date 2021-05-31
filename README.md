# whichCat.js
This is a Tensorflow project to create a model that recognizes my cats. I had originally trained a model manually with Keras in Python but found that the Google Teachable Machine model was quick to make and better at classifying. 

Originally this was going to be a webapp using Tensorflow.js but I figured out how to make an iOS App that uses the model so that's on here instead.

Opening up the site will allow the user to use their webcam to classify an image. The only recognized objects are my cats, though, so it's not terribly useful to others. 

I plan to use this model and see what else I can do with Tensorflow.js and I'll use other repos if the model strays from just my cats.

## Usage (Basic)

Using a web browser, open the `index.html` file. Click on the button to activate your webcam and allow the page access to your webcam. From there the app will analyze the image coming from the webcam and show it's confidence of what the image is. Unless you're holding a picture of one of my cats (unlikely), or one of my cats (less likely), it's not particularly useful since it will have high confidence that neither are present. This is untested, but I guess you could hold up your cat and it will tell you which of my cats yours resembles more.

## Usage (Advanced)

You'll have to open the iOS project in XCode and deploy it on an iOS device or simulator. It's honestly not worth it, just watch the videos below. I'm not keeping this up to date with iOS changes so it may not even be compatible with the current version.

## Demo

https://user-images.githubusercontent.com/1556891/119390113-2d86fb00-bc92-11eb-945a-cc8a9a15b219.mov


https://user-images.githubusercontent.com/1556891/119390120-311a8200-bc92-11eb-8ad1-372f711c9cf1.mov


