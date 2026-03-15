# Full Stack eCommerce demo

Full Stack eCommerce demo platform built with a **decoupled frontend and backend architecture**.  
The project demonstrates how to build a modular eCommerce system using reusable components and a custom REST API.

## Overview

ModuCommerce is designed as a **flexible and reusable eCommerce architecture** where the frontend communicates exclusively with a backend API built with Express.

All UI components were built as **fully reusable and responsive modules**, allowing them to be integrated into different projects or applications.

The project includes common eCommerce features such as product filtering, pagination, shopping cart persistence and a simulated payment system.

---

## Tech Stack

### Frontend
- React
- Vite
- Zustand (Global State Management)
- CSS Modules

### Backend
- Node.js
- Express
- Nodemailer (Email service)

---

## Features

- Decoupled **Frontend / Backend architecture**
- Custom **REST API** built with Express
- Fully **reusable UI components**
- **Responsive components** adaptable to any project
- Product filtering by:
  - Category
  - Brand
  - Price
- Product search by name
- Automatic pagination (10 products per page)
- Persistent shopping cart
- Simulated custom payment gateway
- Email sending system using Nodemailer
- Global state management using Zustand

---

## Project Structure


project
│
├── frontend
│ ├── components
│ ├── pages
│ ├── store
│ └── services
│
├── backend
│ ├── routes
│ ├── controllers
│ ├── services
│ └── server.js

---

## Installation

Clone the repository:

```bash
git clone https://github.com/ClaudioBarlassina/moducommerce.git

Install dependencies.

Frontend:

cd frontend
npm install
npm run dev

Backend:

cd backend
npm install
node server.js
Purpose of the Project

This project was created as a technical demonstration of a modular full stack architecture.

The goal is to showcase:

reusable component design

scalable architecture

frontend and backend separation

state management patterns

Author

Claudio Barlassina
Full Stack Web Developer

GitHub:
https://github.com/ClaudioBarlassina
