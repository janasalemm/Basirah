# Basirah

### A Smart Navigation and Safety Assistant for Deaf and Hard-of-Hearing Users

Basirah is a web-based project designed to help deaf and hard-of-hearing users navigate their surroundings through clear visual information and safety alerts.

The idea started during my CS50x journey, where I wanted to build a project that connects programming with a real-world problem. I started Basirah from scratch and continued developing the idea after completing the course.

## 💡 The Idea

People who cannot rely on audio alerts may miss important information in their surroundings, such as dangerous roads, construction areas, or other potential hazards.

Basirah aims to provide this information visually through a simple and accessible interface.

The project focuses on:

- Showing the user's location on a map.
- Displaying nearby places and reported hazards.
- Providing visual safety alerts.
- Allowing users to report potential hazards.
- Presenting important information without relying on sound.

## ✨ Features

### 🗺️ Interactive Map

Users can view their location and explore nearby areas using an interactive map.

### ⚠️ Safety Alerts

The application displays visual alerts for different types of hazards, such as:

- Dangerous roads
- Construction areas
- Crowded areas
- Blocked paths
- Other reported hazards

### 📍 Hazard Reporting

Users can report a hazard by providing:

- Hazard type
- Location
- Description

The report can then be displayed on the map for other users.

### ♿ Accessibility-Focused Design

Basirah is designed with visual communication in mind, using:

- Clear icons
- Simple navigation
- Easy-to-read text
- Visual alerts
- Minimal reliance on audio

## 🛠️ Technologies

The project is built using:

- Python
- Flask
- HTML
- CSS
- JavaScript
- SQLite
- Leaflet.js
- OpenStreetMap

## 📁 Project Structure

```text
basirah/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── templates/
│   ├── index.html
│   ├── map.html
│   └── alerts.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   ├── js/
│   │   ├── map.js
│   │   └── alerts.js
│   │
│   └── images/
│
├── data/
│   └── basirah.db
│
└── utils/
    ├── location.py
    └── safety.py

## 🚀 Getting Started
1. Clone the repository

git clone https://github.com/YOUR-USERNAME/basirah.git


