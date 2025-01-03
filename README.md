# PG Life - Full-Stack Web Application

**PG Life** is a fully responsive, feature-rich web application designed to help users find and manage **Paying Guest (PG)** accommodations across various cities. Built during my **Full Stack Web Development internship** at **Internshala**, this project incorporates the latest web technologies and provides an engaging user experience.

## Tech Stack

- **Frontend:**  
  - HTML, CSS, Bootstrap 5, JavaScript, AJAX
- **Backend:**  
  - PHP
- **Database:**  
  - MySQL

## Key Features

### Home Page
- **Search Bar:**  
  Users can easily search for PGs by city (case-insensitive). The app displays a list of PGs available in the selected city.
- **Main Cities Section:**  
  Click on circular sections representing popular cities to explore PG listings in that city.

### PG List Page
- **PG Cards:**  
  PG listings are displayed as interactive cards, showcasing essential details like rent, location, and amenities.
- **Filter Bar:**  
  Sort PGs by **rent** and **rating** in ascending or descending order.
- **Popularity Indicator:**  
  See how many users have marked a PG as “interested” to gauge its popularity.
- **Interest Marking:**  
  Logged-in users can mark PGs as interested by clicking the **heart icon** on each PG card. The heart icon dynamically toggles between filled and unfilled states based on user actions, and the number of interested users updates in real-time.

### PG Details Page
- **Image Carousel:**  
  A beautiful carousel at the top showcases high-quality images of the PG.
- **Detailed Information:**  
  Displays the PG's amenities, testimonials, and address in a clean layout.
- **Interest Marking:**  
  Logged-in users can mark PGs as interested directly from the details page. The heart icon toggles and updates the number of interested users dynamically.

### Dashboard (For Logged-In Users)
- **User Profile:**  
  Displays the user’s account details, including username and profile information.
- **Interested Properties:**  
  Shows the PGs the user has marked as interested across any city.
- **Manage Interested PGs:**  
  Users can easily remove a PG from their interested list by clicking the heart icon again. The list dynamically updates based on the user’s actions.

### Navbar
- **Brand Name:**  
  The navbar features the app’s brand name for easy identification.
- **Login/Signup Options:**  
  If the user is not logged in, they are prompted to **Sign Up** or **Log In**.
- **Dashboard & Logout:**  
  For logged-in users, the navbar displays a link to the **Dashboard** and a **Logout** button, along with the user’s first name fetched dynamically via **SESSION**.
- **Responsive Toggler:**  
  The navbar adapts to all screen sizes, ensuring a smooth experience across mobile, tablet, and desktop devices.

### Breadcrumbs
- **Visual Location Indicator:**  
  Helps users understand their location within the web app by showing a clickable breadcrumb trail.
- **Easy Navigation:**  
  Each level in the breadcrumb allows users to quickly navigate back to previous pages or sections.

### Footer
- **Popular Cities List:**  
  The footer includes links to PG listings in popular cities, allowing users to quickly explore PGs across different locations.
- **Copyright Information:**  
  Displays the copyright notice, ensuring legal protection for the platform’s content.

### Web App Accessibility & Error Handling
- **No Login Required for Browsing:**  
  Users can browse PG listings, view PG details, and search for PGs without needing to log in. This makes the app more accessible and engaging for new users.
- **Login-Only Features:**  
  Certain features like the **Dashboard** and marking PGs as **Interested** require users to sign in.
- **Exception Handling:**  
  Comprehensive error handling ensures that any issues (such as incorrect inputs or failed submissions) are handled gracefully with clear, user-friendly error messages.

## How to Run the Project Locally

1. **Clone this repository:**

   ```bash
   git clone https://github.com/anjana1511/PG-Life.git
   ```

2. **Set up the database:**

   - Import the provided **PG Life database schema** (`pg_life.sql`) into your MySQL database.

3. **Configure the backend:**

   - Update the database connection details in `config.php` with your MySQL server credentials.

4. **Run the application:**

   - Launch the app on your local server (using tools like XAMPP, WAMP, or MAMP) by opening `index.php` in your browser.
