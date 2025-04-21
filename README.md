# Deploy node.js app in Google Cloud App Engine using Cloud Build and Github

> This project demonstrate how to deploy node.js sample app in Google Cloud App Enging using Cloud Build and Github

## 🚀 Features

- ✨ Google cloud acount setup
- ⚡ App Engine
- 🔒 How to deploy app using Google cloud SDK from local

## 🛠 Tech Stack

- Node.js
- Express
- Google Cloud(App Engine)

## 🧑‍💻 Local Setup
- Create free account in google cloud if not already have
- Login to Google cloud console, create a new project, or can use existing one
- Link billing account to project if not already linked
- Install and setup google cloud cli(Google cloud sdk) in local as per OS
- Create simple node.js app in local
- Enable App Engine Admin API and Cloud Build API from Google cloud console (this is one time activity and has to be done for first time)
- In Google Cloud select App Engine and create application in any region
- Create a trigger - go to Cloud Build, click Triggers, Create trigger (Provide name, description, Event, Connect new GitHub repository, add service account, click create)
- Prepare app.yaml and cloudbuild.yaml file in node app’s root folder
- When you push to GitHub, app will be deployed to app engine

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/rupachowrasia/node-gcp-app-engine-deploy-with-cloudbuild-github.git

# Move into the project directory
cd node-gcp-app-engine-deploy-with-cloudbuild-github

# Install dependencies
npm install

# Run the app
npm run start
