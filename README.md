# Internshala Full Stack Project

Welcome to the Internshala Full Stack Project repository! This project was developed as part of the Internshala Full Stack Web Development assignment, following the UI/UX design specified in **Portfolio.fig** (Figma) and the detailed instructions outlined in **Full Stack Assignment.pdf**.

## Overview

This repository contains a complete full‐stack web application built to satisfy the requirements laid out in the “Full Stack Assignment.pdf.” The front‐end was designed in Figma (see **Portfolio.fig**) and then implemented using standard web technologies. On the back‐end, RESTful APIs handle data storage and retrieval according to the assignment specs.

## Features

- **Figma-Designed UI**: All pages and components follow the mockups in **Portfolio.fig**.
- **Responsive Layout**: Mobile‐first design that scales up to desktop viewports.
- **CRUD Functionality**: Create, Read, Update, and Delete operations for all primary data models.
- **User Authentication**: Registration and login system (as specified in the assignment PDF).
- **RESTful Back‐End**: API routes matching the endpoints described in **Full Stack Assignment.pdf**.
- **Database Integration**: Persists data in a MongoDB (or MySQL) database, per assignment requirements.
- **Instructions & Documentation**: See **Full Stack Assignment.pdf** for full context on “what,” “where,” and “how.”

## Technologies Used

- **Figma**: Design file `Portfolio.fig` contains all UI/UX mockups.  
- **HTML5 / CSS3 / JavaScript**: Core front‐end implementation.  
- **Node.js & Express.js**: Server and API framework.  
- **MongoDB** (or **MySQL**, depending on your local setup): Stores application data.  
- **Mongoose** (if using MongoDB) or an ORM/Query Builder (if using MySQL).  
- **dotenv**: Environment variable management for database credentials, ports, etc.  
- **Axios / Fetch API**: Front‐end HTTP client for communicating with back‐end APIs.  
- **npm / npx**: Dependency management and scripts.

> **Note:** Adjust the database driver (MongoDB vs. MySQL) based on what’s specified in your `Full Stack Assignment.pdf`.

## Getting Started

Follow these steps to run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/PrathameshBamb/Internshala-Full-Stack-Project.git
cd Internshala-Full-Stack-Project
