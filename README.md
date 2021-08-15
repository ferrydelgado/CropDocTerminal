# CropDocTerminal

## Step 1:

Create an android app. Incorporate ML Kit and CameraX. Use CameraX to grab an image, pass it to MLKit, get the labels back, and render them in a toast.

** This is implemented as fireblightdisease_poc android app **

## Step 2:

Use TensorFlow Model Maker to create a custom model using the fireblight dataset in TensorFlow Data Services. 

** This is implemented as fireblight_With_ModelMaker.ipynb **

## Step 3:
Incorporate the fireblight model into the app, using Import->Other->TensorFlow Lite. Updae the code to use CameraX to get the image and pass it to this model. Get the labels back and render them in a toast

** This is implemented as fireblightdisease_poc_lite android app ** 

## Step 4
Add Firebase services to the app, showing how, when moving towards productizing an app you may need things like analytics, sign-in or remote config

** This is implemented as fireblightdisease_pod_lite_firebase android app **

## Step 5
Show the fireblight model running in the browser with TensorFlow.js

** This is implemented as fireblightapp **




