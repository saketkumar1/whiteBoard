
### Project Desciption:
The project comprises of basic openboard functionalities such as, writing, erasing, downloading the canvas, adding notes (with minimising it, closing it, dragging it around on the page), uploading the image (features same as of notes), undo and redo actions. <br>
Added realtime drawing functionality using Socket.io by connecting to server using Express.js

![Screenshot (182)](https://user-images.githubusercontent.com/66872047/150637432-e40868cd-292a-4afc-8e31-fa4b96030f0a.png)

#### Adding notes and uploading image:
Using green button, we can minimise the notes and by clicking red button, notes can be closed. Similarly for uploading images. <br>

![Screenshot (185)](https://user-images.githubusercontent.com/66872047/150637298-ecb28e9b-0c19-4efb-90c3-35b3def4d122.png)

#### Realtime drawing:
Realtime drawing can be achieved by the people using same link at same time.

![Screenshot (186)](https://user-images.githubusercontent.com/66872047/150637297-283698f0-bdae-4378-8448-d778ff483040.png)

### Tech Stack used:
- HTML
- CSS
- JavaScript
- Express.js 
- Socket.io
### Key Features
This real-time whiteboard provides the user with following features:

- Draw using pencil (3 different colors, scale the pencil size)
- Erase the drawn area using eraser(scale the eraser size)
- Include a sticky note to make notes (feature to add multiple sticky notes, move sticky note around the drawing area, minimize and close the sticky note)
- Upload an image or gif (feature to add multiple files,feature to move the file, close the file)
- Download the drawing part on the user screen
- Redo or undo the drawing content changes.
- Zoom in or zoom out the drawing content.
- Real-time virtual environment for drawing and erasing.

### Run on your local machine:
```
npm init
```
Press Enter. Then,
```
npm install socket.io
npm install --save-dev nodemon
node app.js
```
Now open the browser and type `localhost:3000`.

