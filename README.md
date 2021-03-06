## Note It
A  javascript note taking application based on voice

![home](https://github.com/jyl0725/Note-it-Frontend/blob/master/src/assets/home.png?raw=true)

## Motivation
As the future of tech is moving away from typing and moving toward native speech recognition software. This project is a small sample as for the future of note taking

## Demo
A Demo of this project can be found at :

[Youtube](https://www.youtube.com/watch?v=81jq2OM2rEM)

## Built with

* Ruby on Rails
* SpeechRecognition API
* Weather API

## Features
* Detects speech from browser microphone and transcribe speech to text to display on the frontend
* Utilizes keywords(listed below) for frontend and backend interactions
* Accesses current Weather(currently working only for NYC)

## Use Case
* Take Notes: clears the input on screen/ start note taking session
* Save my notes: saves the current note to the backend
* Get my notes: display saved notes in backend to the frontend
* Get the weather: display weather in NYC.

## Installation
1. Run Bundle install

2. Run `Rails s -p 4000`

3. Run `http-server` after staring up Note-it FrontEnd](https://github.com/jyl0725/Note-it-backend)

## EndPoint 
* Get/Post request allowed to localhost:4000/notes end point.
![API](https://github.com/jyl0725/Note-it-Frontend/blob/master/src/assets/API.png?raw=true)


Click on Start Button to start taking notes

This project servers as a backend APi for [Note-it FrontEnd](https://github.com/jyl0725/Note-it-backend) API.
