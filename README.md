# JobApp

JobApp is a mobile application built using React Native that helps users search for job listings from various sources using the RapidAPI job search API.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [API Integration](#api-integration)

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, make sure you have the following installed on your system:

- Node.js
- npm or yarn
- React Native CLI
- Android Studio or Xcode for mobile emulator/simulator

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/LaxmanZ/jobApp-react-native.git
   ```
   
2. Navigate to the project directory:
   ```bash
   cd jobApp
   ```
   
3. Install the project dependencies:
   ```bash
   npm install
   or
   yarn install
    ```
   
4. Start the development server:
   ```bash
   npm start
   or
   yarn start
   ```
   
5. Open the app on your mobile emulator/simulator or use the Expo Go app on your physical device by scanning the QR code in the terminal.

### Usage
   Describe how to use your application here. Include any important instructions for users, such as how to search for jobs, filter results, and navigate through the app.

 ### Features
   List the key features of your application:

  1) Job search from various sources
  2) View Job Details
  3) Filter job listings based on criteria
  4) Save favorite job listings
  5) Apply for the Job through main website

### API Integration
  This project utilizes the RapidAPI job search API for fetching job listings. To integrate your API key, follow these steps:

  1) Sign up for an account on RapidAPI.
  2) Subscribe to the job search API and obtain an API key.
  3) Create a .env file in the project root directory and add your API key:
       RAPIDAPI_KEY=your-api-key
  4) In your code, import the environment variables using react-native-dotenv:
     ```bash
       import { RAPIDAPI_KEY } from 'react-native-dotenv';
     ```
       Use `RAPIDAPI_KEY` to authenticate your API requests.


      
Thank You....!


If Your are looking to hire a react-native/reactjs developer please contact me. laxmanbhajantri547@gmail.com
   
