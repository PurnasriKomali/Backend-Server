# Backend-Server
# GoogleformReplica
## To create a Desktop App using Visual Basic language and Backend using Express and Typescript to replicate the functionality of Google forms.
## This project is a Google Forms-like application that consists of a Windows Desktop application built using Visual Basic and a backend server built with Express.js and TypeScript. The application allows users to create new submissions and view existing submissions.
### Prerequisites
To run this project, you need the following:

Node.js (v14, v16, or v18 recommended)
npm (Node package manager)
Visual Studio (not Visual Studio Code) with Visual Basic support
.NET Framework
## Backend Setup
### Clone the Repository:
First, clone the repository to your local machine and navigate to the project directory:
- git clone https://github.com/yourusername/GoogleFormsReplica-Backend.git
- cd GoogleFormsReplica-Backend
### Install Dependencies:
Install the required npm packages by running:
- npm install
### Create tsconfig.json:
Initialize the TypeScript configuration file with the command:
- npx tsc --init
### Configure tsconfig.json:
Open the tsconfig.json file and update it with the following configuration:
{
  "compilerOptions": {
    "target": "ES6",
    "module": "commonjs",
    "outDir": "./dist",
    "rootDir": "./src",
    "strict": true,
    "esModuleInterop": true
  }
}
### Create src Directory and index.ts File:
Create the source directory and an initial TypeScript file by running:
- mkdir src
- cd src
- echo > index.ts
### Implement API Endpoints:
Implement the necessary API endpoints in the src/index.ts file.
### Create db.json File:
In the root directory of the backend project, create a db.json file with the following initial content:
- []
### Compile and Run the Server:
Compile the TypeScript files and start the server by running:
- npx tsc
- node dist/index.js
