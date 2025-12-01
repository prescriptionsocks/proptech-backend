# PropTech Backend

This is the backend for the PropTech application, powered by a JSON server. It serves property data for the frontend and allows CRUD operations for managing listings.

---

## Table of Contents

- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Running the Server](#running-the-server)
- [API Endpoints](#api-endpoints)
- [Data Structure](#data-structure)


---

## Getting Started

This backend is a JSON-based server that provides property listings for the PropTech frontend. You can fetch, create, update, and delete properties using the endpoints described below.

---

## Project Structure

proptech-backend/
├── src/
│ └── public/
├── db.json
├── package.json
├── package-lock.json
└── README.md

---

## Installation

Make sure you have Node.js installed.

1. Clone the repository
2. Install dependencies by running npm install
3. Start the server with npm start. It will be available at http://localhost:3001/. All endpoints are relative to the base URL (http://localhost:3001/).

---
## Data Structure
Each property in db.json follows this format:

**ID:** 1  
**Title:** Modern 2 Bedroom Apartment  
**Property Type:** rent  
**House Type:** apartment  
**City:** Nairobi  
**Estate:** Kilimani  
**Price:** 85,000  
**Bedrooms:** 2  
**Bathrooms:** 2  
**Parking Spaces:** 1  

**Main Image:**  
Main Image

**Additional Images:**  
Image 1
Image 2

**Description:**  
Full description of the property...

**Created At:** 2025-11-28T10:00:00Z

