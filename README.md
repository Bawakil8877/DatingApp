DatingApp

Overview

DatingApp is a modern web application designed to connect users in a seamless and interactive way. It allows users to register, create profiles, upload photos, and communicate with potential matches. The application is built with a robust backend using ASP.NET Core and a dynamic frontend using Angular, ensuring scalability, performance, and a smooth user experience.

Features

User Authentication: Secure login and registration system using JWT authentication.

Profile Management: Users can edit their profile details, update their preferences, and upload photos.

Real-Time Messaging: Integrated chat functionality for instant communication.

Like & Match System: Users can like profiles and get matched with others.

Admin Panel: Role-based access control for managing users and app settings.

Error Handling: Comprehensive error handling to ensure a smooth experience.

Responsive UI: Fully optimized for desktop and mobile devices.

Technologies Used

Frontend (Client)

Angular (Latest Version)

TypeScript

Bootstrap & CSS for styling

ngx-bootstrap for UI components

ng2-file-upload for photo uploads

Backend (Server)

ASP.NET Core Web API

Entity Framework Core

SQL Server for data storage

JWT Authentication for secure login

Cloudinary for image hosting

Development Tools

Visual Studio & Visual Studio Code for development

Postman for API testing

Node.js & npm for managing frontend dependencies

Installation & Setup

Prerequisites

Install Node.js (Latest version)

Install Angular CLI

Install .NET SDK (Version 7 or later)

Install SQL Server

Steps to Run the Project

Clone the Repository:

git clone https://github.com/your-repo-url.git
cd DatingApp-DotNet7Angular1

Setup Backend (ASP.NET Core API)

cd API
dotnet restore
dotnet run

Setup Frontend (Angular)

cd client
npm install
npm start

Access the App

Backend runs on https://localhost:5001

Frontend runs on https://localhost:4200

Database Seeding

The application is seeded with test users. You can log in as an admin or user with predefined credentials.

Check the Seed.cs file for details.

Contribution & Support

Feel free to contribute by reporting issues or suggesting improvements. Reach out if you need any help setting up the project!
