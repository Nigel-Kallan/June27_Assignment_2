

# Trinbago Day

## Table of Contents

* [Description](#description)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Known Bugs](#known-bugs)
* [Contributors](#contributors)
* [Instructions](#instructions)

---

## Description

**Trinbago Day** is a cultural celebration event dedicated to showcasing the vibrant traditions of Trinidad and Tobago. This event brings together food, music, and arts from the twin-island nation, offering a truly immersive experience. Whether you're enjoying the rhythms of calypso and soca, tasting traditional Caribbean dishes, or learning about the rich cultural heritage, **Trinbago Day** is the ultimate celebration of everything that makes Trinidad and Tobago unique.

---

## Features

* **Event Calendar**: Display upcoming events related to Trinidad and Tobago culture.
* **Food Vendor Listings**: A directory of local food vendors serving authentic Trinidadian cuisine.
* **Music Playlists**: Curated playlists featuring soca, calypso, and steel pan music.
* **Cultural Workshops**: Listings and details of workshops where attendees can learn about the art, history, and traditions of Trinidad and Tobago.
* **Real-time Updates**: Notifications and updates about the event, changes to schedules, or special announcements.
* **Social Media Integration**: Easy sharing features to allow attendees to share their experience on social platforms.

---

## Technologies Used

* **Languages**: HTML, CSS, JavaScript, Python
* **Frameworks**: React.js (for event management interface), Flask (for server-side logic)
* **Database**: PostgreSQL (for storing event information, vendor details, and user data)
* **APIs**: YouTube API (for music playlists), Google Calendar API (for event scheduling)
* **Hosting**: AWS (for event page and media hosting)
* **Version Control**: Git, GitHub

---

## Known Bugs

* [ ] **Event Time Zone Issue**: Event times displayed incorrectly for users in different time zones.
* [ ] **Mobile Layout Bug**: On some mobile devices, the event schedule page layout doesn't render correctly.
* [ ] **Image Gallery Slideshow**: Image gallery doesn't loop through images automatically on the home page.
* [ ] **Food Vendor Filtering**: Food vendor filter by category is not working as expected.

---

## Contributors

* [@user1](https://github.com/user1)
* [@user2](https://github.com/user2)
* [@user3](https://github.com/user3)

---

## Instructions

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/trinbago-day.git
   ```
2. Navigate to the project folder:

   ```bash
   cd trinbago-day
   ```

### Running the Project Locally

#### Frontend (React.js)

1. Install dependencies:

   ```bash
   npm install
   ```
2. Start the React development server:

   ```bash
   npm start
   ```
3. Open your browser and go to `http://localhost:3000` to see the app in action.

#### Backend (Flask)

1. Create a virtual environment:

   ```bash
   python -m venv venv
   ```
2. Activate the virtual environment:

   * On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```
   * On Windows:

     ```bash
     venv\Scripts\activate
     ```
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
4. Run the Flask app:

   ```bash
   python app.py
   ```
5. Visit `http://localhost:5000` to access the backend API.
