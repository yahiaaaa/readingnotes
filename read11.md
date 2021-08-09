# Audio, Video, Images on HTML 

You can :

Controlling size of images in CSS
Aligning images in CSS
Adding background images on HTML…
About images on HTML :

You can control the size of an image using the width and height properties in CSS by width and height

images are inline elements.

The background-imageproperty allows you to place an image behind any HTML element.

To add image as abackground to an element on HTML : {background-image: url(the url of the image);}
Images can be aligned both horizontally and vertically using CSS ..

![image text](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/07/html-images-df.jpg "image Title")

Centering images in css
By default, images are inline elements. This means that they flow within the surrounding text. In order to center an image, it should be turned into a blocklevel element using the display property with a value of block.

* On the containing element, you can use the text-align property with a value of center.
 * On the image itself, you can use the use the margin property and set the values of the left and right margins to auto.

# audio and vedio in HTML

we can add audio to html by write video tag includes source tags

<video controls>
  
  <source src="rabbit320.mp4" type="video/mp4"> // this for the video
  
  <source src="rabbit320.webm" type="video/webm"> // tis for the audio 
  
</video>

this example was from MDN (Links to an external site.)

for a video we can add buttons using html add style to the buttons using css and then add functionality related to the video play , pause , stop and more proprties using CSS
