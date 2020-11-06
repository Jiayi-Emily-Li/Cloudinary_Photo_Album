# Cloudinary_Photo_Album

I installed the "photo album" project on Node.js

1. Clone from Github
2. Copy the Enviroment variable configuration parameters from Cloudinary's Management Console of my account into .env file of the project.
3. Run 'npm install' to install all the required dependencies.
4. Run 'npm start' to start the server.
5. Open the page in a browser: http://localhost:9000
6. Install the jQuery library using a package manager
 
   npm install jquery --save 
   
   npm install blueimp-file-upload --save
   
   npm install cloudinary-jquery-file-upload --save
   
# Exercise 1:

In /controllers/photo_controller.js, change 'tag' to "width_height_500" and set width: 500, height: 500, crop: "limit"

# Exercise 2:

1. Upload Cloudinary logo image to my own asset.
2. In /views/photos/index.ejs, add two more tansformation.

   { crop : "scale", height : 150, width : 150 , transformation : {
     overlay: "yais6gcdxppuedri9ixj", gravity: "south_east", x: 5, y: 5, width: 200, opacity: 60, effect: "brightness:200"} },
   { crop : "scale", height : 150, width : 150 , effect: "saturation:50"}
   
# Bonus:
 
Use jQuery and blueimp-file-upload to take care of all different upload methods of the app, server side, signed direct/client-side uploads and unsigned direct/client-side uploads
             


   
   
   
