# Smart India Hackathon Workshop
## Register Number: 212223040103
## Name: Kurapati Vishnu Vardhan Reddy
## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations
## Problem Description
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

## Proposed Solution

## Solution Name

**RailNav – Smart Railway Station Navigation System**

## Overview

RailNav provides passengers with an easy-to-use navigation platform for railway stations.

The system consists of:

### 1. Mobile Application

* Interactive station maps
* Facility search
* Route guidance
* Voice assistance

### 2. Admin Portal

* Manage station maps
* Add/update facility locations
* Monitor navigation requests

### 3. Backend API

* Route generation
* Facility management
* User request handling

### 4. Database

* Station layouts
* Facility information
* Navigation paths

## Key Features

### Facility Search

Users can search for:

* Platforms
* Ticket counters
* Waiting rooms
* Restrooms
* Food stalls
* Medical rooms
* ATMs
* Exits

### Interactive Maps

* Zoomable station map
* Facility markers
* Route visualization

### Navigation

* Source → Destination path generation
* Turn-by-turn instructions
* Shortest route calculation

### Accessibility Features

* Voice navigation
* Wheelchair-friendly route suggestions
* High-contrast UI mode

### Digital Kiosk Support

Passengers without smartphones can:

* Search destinations
* View routes
* Scan QR codes to continue navigation on mobile

---

## Use Cases

## Use Case 1: Finding a Platform

**Actor:** Passenger

### Flow

1. Open the application.
2. Enter platform number.
3. System identifies current location.
4. Route is generated.
5. Passenger follows navigation instructions.

---

## Use Case 2: Locating Facilities

**Actor:** Passenger

### Flow

1. Search for a facility (ATM, restroom, food court, etc.).
2. System displays the nearest location.
3. Route is generated.
4. Passenger reaches the destination.

---

## Use Case 3: Voice Navigation

**Actor:** Visually Impaired Passenger

### Flow

1. Enable voice assistance.
2. Select destination.
3. System provides spoken directions.
4. Passenger follows instructions.

---

## Use Case 4: Station Staff Updating Layout

**Actor:** Admin

### Flow

1. Login to the admin portal.
2. Update facility locations.
3. Save changes.
4. Updates become available to users.

---

## Architecture Diagram:
<img width="1068" height="702" alt="Screenshot 2026-05-30 at 8 01 45 PM" src="https://github.com/user-attachments/assets/25993901-a33c-4e7f-9919-094c0165d7bb" />



## Use Case Diagram (PlantUML)
<img width="776" height="1065" alt="Screenshot 2026-05-30 at 7 58 57 PM" src="https://github.com/user-attachments/assets/38ef7a29-8fb3-4c1d-92bd-61da2cdd91e2" />


## Technology Stack

## Frontend (Web)

* React.js
* Tailwind CSS
* React Router
* Axios
* Leaflet.js / React Leaflet

## Mobile Application

* React Native
* React Native Maps
* React Native Voice

## Backend

* Node.js
* Express.js
* JWT Authentication

## Database

* PostgreSQL
* Prisma ORM

## Accessibility

* Web Speech API
* React Speech Recognition

## Deployment

* Docker
* Nginx
* AWS EC2 (Optional)

---

# Dependencies
- Railway station layout and facility mapping data – 10 days
- Data collection and verification – 10 days
- Mobile application development and testing – 15 days
- Cloud hosting and backend infrastructure – 5 days
