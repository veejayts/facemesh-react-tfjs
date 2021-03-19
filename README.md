# Facemesh using react and tensorflow

Outputs mesh of face in the browser using the tfjs model called face landmark detection. This gives a set of points which maps to particular points on the detected face.

Triangulation of these points is done and drawn on the canvas for this project.

Main code is present in `src/App.jsx` and `src/utilities.js`.

This code was inspired from [this video](https://www.youtube.com/watch?v=7lXYGDVHUNw).

## Run the project

`npm run start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.