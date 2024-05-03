# Simple Express Static HTML Page Server

This repository contains a simple Node.js application that serves a static HTML page using Express.js.

## Overview

This project aims to provide a basic setup for serving a static HTML page using a Node.js backend with Express.js framework. 
It includes a simple HTML page located in the `public` folder and a backend server implemented in `index.js`. 
The server utilizes Express.js and `body-parser` middleware to handle incoming requests.

## Features

- Serves a static HTML page
- Uses Express.js for routing and handling HTTP requests
- Implements `body-parser` middleware for parsing incoming request bodies

## Installation

1. Clone this repository to your local machine:
```
git clone https://github.com/Endekalu-Zemenu/secret
```
2. Navigate to the project directory:
```
cd secret
```
3. Install dependencies using npm:
```
npm install
```

4. Install nodemon globally (if not already installed) to automatically restart the server when changes are made:
```
npm install -g nodemon
```

## Usage

1. Start the server by running:
```
nodemon index.js
```

2. Open your web browser and navigate to [http://localhost:3000](http://localhost:3000) to view the static HTML page served by the application.

## Project Structure
```
.
├── public/ # Static HTML page folder
│ └── index.html # Main HTML page
├── index.js # Backend server implementation
├── package.json # npm package configuration
└── README.md # Project README file
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or create a pull request.
