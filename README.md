Basirah

A Smart Navigation and Safety Assistant for Deaf and Hard-of-Hearing Users

Basirah is a web-based project designed to help deaf and hard-of-hearing users navigate their surroundings through clear visual information and safety alerts.

The idea started during my CS50x journey, where I wanted to build a project that connects programming with a real-world problem. I started Basirah from scratch and continued developing the idea after completing the course.

💡 The Idea

People who cannot rely on audio alerts may miss important information in their surroundings, such as dangerous roads, construction areas, or other potential hazards.

Basirah aims to provide this information visually through a simple and accessible interface.

The project focuses on:

* Showing the user’s location on a map.
* Displaying nearby places and reported hazards.
* Providing visual safety alerts.
* Allowing users to report potential hazards.
* Presenting important information without relying on sound.

✨ Features

🗺️ Interactive Map

Users can view their location and explore nearby areas using an interactive map.

⚠️ Safety Alerts

The application displays visual alerts for different types of hazards, such as:

* Dangerous roads
* Construction areas
* Crowded areas
* Blocked paths
* Other reported hazards

📍 Hazard Reporting

Users can report a hazard by providing:

* Hazard type
* Location
* Description

The report can then be displayed on the map for other users.

♿ Accessibility-Focused Design

Basirah is designed with visual communication in mind, using:

* Clear icons
* Simple navigation
* Easy-to-read text
* Visual alerts
* Minimal reliance on audio

🛠️ Technologies

The project is built using:

* Python
* Flask
* HTML
* CSS
* JavaScript
* SQLite
* Leaflet.js
* OpenStreetMap

📁 Project Structure

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

🚀 Getting Started

1. Clone the repository

git clone https://github.com/YOUR-USERNAME/basirah.git

2. Open the project

cd basirah

3. Create a virtual environment

Windows

python -m venv venv
venv\Scripts\activate

macOS / Linux

python3 -m venv venv
source venv/bin/activate

4. Install dependencies

pip install -r requirements.txt

5. Run the application

python app.py

Then open:

http://127.0.0.1:5000

🧪 Current Development Stage

Basirah is currently being developed as a prototype.

The first version focuses on building the core navigation and safety features before expanding into more advanced functionality.

🔮 Future Improvements

Future versions may include:

* Real-time hazard detection
* Integration with external map services
* More detailed accessibility information
* User accounts and personalized settings
* Community-based hazard reports
* Improved location-based alerts
* Mobile application development
* Machine-learning-based risk detection

🎯 Motivation

I created Basirah because I wanted to use programming to solve a real-world problem.

The project began as an idea during my CS50x experience and became an opportunity for me to continue learning by building something useful.

Rather than stopping after completing the course, I decided to keep developing the project and explore how software can be used to create more accessible and inclusive technology.

👩🏻‍💻 Author

Jana Balhareth

Computer Engineering / Technology Enthusiast

GitHub:
https://github.com/janasalemm/Dawaa

⸻

📄 License

This project is licensed under the MIT License.
