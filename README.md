Project Setup Guide
This guide will help you clone and run all parts of the project step-by-step.

Prerequisites
Make sure you have the following installed on your machine:

Flutter
Node.js & npm
Go

1. Clone the Project
git clone <repo-url>

2. Run the Flutter App (Bnext-App)
Navigate to the Flutter app directory and install dependencies:

cd Bnext-App
flutter clean
flutter pub get
flutter run

3. Run the React Frontend (FE_CRM_REACT)
Open a new terminal window, then:

cd FE_CRM_REACT
npm audit fix
npm run dev

4. Configure Environment Variables
Adjust the .env files in each part of the project to match your local setup and credentials.

5. Run the Golang Backend (BE_CRM_GO)
Open another terminal window, then:

cd BE_CRM_GO
go run migrate/migrate.go
go run main.go

