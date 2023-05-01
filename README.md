# Ex.04 Images as Hyperlinks
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
  
## CODE
~~~
<html>
<body>
<h1>PLOUGHER</h1>
<a href="https://www.thefreedictionary.com/plougher#:~:text=n.,means%20of%20a%20strong%20blade.">
<img src="PLOUGHER.JPG"
width="200" height="200"></a>
<br>
<br>
<h1>SEEDER</h1>
<a href="https://www.merriam-webster.com/dictionary/seeder">
<img src="SEEDER.JPG"  width="200" height="200"></a>
<br>
<br>
<h1>TILLAGE</h1>
<a href="https://www.britannica.com/topic/tillage">
<img src="TILLAGE.JPG"
width="200" height="200"></a>
<br>
<br>
<br>
<h1>SICKLE</h1>
<a href="https://www.merriam-webster.com/dictionary/sickle">
<img src="SICKLE.JPG"
width="200" height="200"></a>
<br>
<br>
<br>
<h1>SPADING FORK</h1>
<a href="https://www.cjonline.com/story/lifestyle/home-garden/2017/06/30/home-spading-fork-must-have-gardening-tool/16538623007/#:~:text=The%20fork%20can%20be%20used,ground%20with%20compost%20for%20renewal.">
<img src="SPADING FORK.JPG"
width="200" height="200"></a>
</body>
</html>
~~~
## OUTPUT
![OUT 01](https://user-images.githubusercontent.com/127817091/235475990-c6ae10e4-7778-40f4-89c9-5e4fbdd5bb69.png)
![OUT 02](https://user-images.githubusercontent.com/127817091/235476059-92af1ec2-9b79-403e-85bd-d6c76d58a3a9.png)
![OUT 03](https://user-images.githubusercontent.com/127817091/235476163-ae71d2dd-e1fc-485f-a14a-07c0b3d5371e.png)


## RESULT
 Images as hyperlinks is implemented successfully.
