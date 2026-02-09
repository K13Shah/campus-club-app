# campus-club-app

Campus Connect Hub

Campus Connect Hub is a full-stack web application designed to help college students discover, join, and manage campus clubs based on their interests, skills, and career goals.
The platform improves student engagement by centralizing all club activities, events, and communication in one place.

🚀 Features
👤 Student Features

Student signup and basic profile creation
Enter college name, course, year, interests, and skills
Automatic club recommendations based on interests
Request to join clubs (public or private)

🏫 Club Features

Club creation and management
Admin approval for private clubs
Club member management
Announcements and updates
Events and workshops (online/offline)
Polls and discussions (basic structure)

🌐 College-wide Features

Discover clubs across campus
Explore college events
Inter-college collaboration support (future ready)

🛠 Tech Stack

Frontend
HTML
CSS
JavaScript
Backend
Node.js
Express.js
Database
MongoDB (Atlas)
Tools
Replit (development & live demo)
GitHub (version control)

#Project Structure

in folder uploaded 
.git inside it

server.js
├── package.json
├── config/
│   └── db.js
│
├── models/
│   ├── Student.js
│   ├── Club.js
│   └── JoinRequest.js
│
├── routes/
│   ├── studentRoutes.js
│   ├── clubRoutes.js
│   └── joinRoutes.js
│
├── public/
│   ├── index.html
│   ├── dashboard.html
│   ├── style.css
│   └── script.js
