# Distracted Driver Recognition Neural Network Application ~ 24 Hour Hackathon Project

This application identifies distracted drivers in real-time. It can be used in the real world by police officers to 
actively identify distracted drivers and create and/or store additional information in their permanent records.

## Table of Contents

- [Distracted Driver Recognition Application](#project-name)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## Introduction

Welcome to the Distracted Driver Detection GitHub repository! This application is designed
to identify distracted drivers in real-time, offering a powerful tool for law enforcement
officers to actively detect and record instances of distracted driving. In this README, you'll
find information on how to use, contribute, and further develop this essential application for
enhancing road safety. Let's make our roads safer together! 🚗💻👮‍♂️

## Features

- Android Studio Interface
- Communication through Neurons
- Image Classification System
- End Points with Weight
- Distracted Driver State

## Getting Started

- Clone this GitHub repository
- Open this on Android Studio or any other compatible IDE
- Run class 'main'
- Make sure to set up a virtual or external machine

## Figures

- Figure describing Neural Network
- Figure describing over workflow
- Figure describing output flow

### Prerequisites

- Android compatible device required
- Access of drivers images

### Installation

This is installed fully locally and takes 30 mb.

## Usage

Once the program is run, upload an image through your Android device. If safe driving is detected, the corresponding output will be shown. If distracted driving is detected, the user is asked to confirm if this is correct, and if it is confirmed, the complaint will be filed.

## Limitations

- The functionality has not been verified with validation data - received a 99.3 percent accuracy on training data.
- The application is trained with pictures that would be challenging to take in the real world.

## Contributing
You can contribute to this application by cloning the GitHub, making your respective changes, and sending a commit request. If you intend to use the neural network for your own application make sure you add nihalgunu (Github), Nihal Gunukula (Full Name) as acknowledgment in your project.


## Acknowledgments

This project was made during Purdue's Hello World 2023 Hackathon by:

Nihal Gunukula
- Developed the entire Neural Network through TensorFlow in Google Colab.
- Established Integration with Andriod Studio adding the functionality to take a photo or pic picture from the gallery -> send it to the neural network -> get a "distracted driver" or "non-distracted driver response".

Molik Mishra
- Established the human verification option within the Andriod application through Andriod Studio.
- Tested our application with his Android phone & downloaded the finished app.

Ayush Pai
- Found the database of 1,000 distracted drivers that were utilized within the application.
- Found out how many people die due to distracted driving. 

Aathman Bhavaraju
- Created the figures representing what our application did through excalidraw.
- Wrote a majority of the readme file.

