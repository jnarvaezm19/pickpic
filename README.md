## PickPic ##
This is an application to upload images and group ones per album.
Also each photo contains title and descriptions. 
Then you can filter by title, description or date.

Based on React js.

## How it Works? ##
The app works adding an album to start, so you can add a lot of one. Then you have to select an album, the app will show you a buttom in the middle of the screen to add a image.
To add a image you could put it a title and description
Note: when you pick an image just wait a few seconds, in the left side the one will load and give you a preview before upload.
Another thing that you can do is filter by title, description or date to find images.

## How to install
Steps:
1. you have to clone the repository:
##### `git clone https://github.com/jnarvaezm19/pickpic.git`
2. enter to project folder
##### `cd pickpic`
3. then you must to install all dependencies
##### `npm install`

## How to run ##
Locate into the app folder then execute:
##### `npm start`
 
#### Implemented Libraries ####
>React Materialize
>uikit-react
>classnames

#### Versions: ####
>classnames: 2.2.6,
>materialize-css: 1.0.0,
>react: 16.12.0,
>react-alert: 6.0.0,
>react-alert-template-basic: 1.0.0,
>react-dom: 16.12.0,
>react-materialize: 3.5.8,
>react-scripts: 3.3.0,
>uikit-react: 3.0.20,

To save the images I used the API of cloudinary. All image upload in this app will be locate in this site.


## Issues Found ##
When I installed the react-materialize library, I couldn't use the 'className' in the html tags so, the issue wasn't let me work. So to fix that I had to install classnames library  `npm install classnames`
I found how to fix in this link https://stackoverflow.com/questions/51197486/classnames-is-not-defined

### Anotations ###
This is my first react app, that's explain the basic structure, so I put the conecction with the generated API RestFul in the same file named index.js stored in /containers/index.js  that contains all the functions and methods. 
So.. why react? I choose react to develop this app because is a popular technology, further you actually use that, so I accepted your technical test but also I set a challange to me and thats was make this technical test in this technology to show me that I can do whatever challange, obviously I have a lot of thing to improve.

### To Improve ###
Making this project I realize about I have to improve the component handling, search more about the react structure to divide the code in little compontents to make it more understable and organizate. To the layout improve I thing that need explore more libraries, adjust some fields to make the layout more pretty.
Personality I feel better when I've a mockup to guide me.
And the more important to improve in this project is the photo view when thery're storages, because, is a simple view, I tried to make it more beautiful implementing mediaboxes to show the image in all the screen, but I don't know if that is a issue to the library, or maybe I'm knowless about how it work in special functions. 
Note: When we uploaded a images a file field cannot reset, so this little detail is happening, but te functionality is the same, just choose another image.
