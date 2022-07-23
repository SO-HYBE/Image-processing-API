# Image-processing-API
----------IMAGE PROCESSING API----------

This project was made by Sohib Amer in 7/21/2022.

It was made for a Udacity course (Web Development- Advanced Track).

The project is a image processing api that resizes an image and returns it as a thumbnail.

I learnt alot about using node, typscript, testing with jasmine, building a server, using npm to make a better code.

I tried to be as convinient as possible in my project.

TO RUN THE CODE: 

Type in the terminal:

1. npm run prettier
2. npm run lint
3. npm run test
4. node build/index

TO USE THE PROJECT: 
You should have a folder that contain images.
Take one of the image names and add it as a query parameter in the url along with the desired width and height.
Make a 'thumb' folder in the outer folder. 
Finally, enjoy your thumbnail image.

Endpoint access instructions: 

http://localhost:3000/myapp/process?filename=(file-name)&width=(custom-width)&height=(custom-height)

Example of a working endpoint url to test the funcionality: 
http://localhost:3000/myapp/process?filename=fjord&width=200&height=200

This will take the image, resize it , save it in 'thumb' folder , and display it in the browser.

---------------------THIS PROJECT IS FULLY MADE BY SOHIB AMER AND ALL COPYRIGHTS ARE SAVED FOR HIM.---------------------


