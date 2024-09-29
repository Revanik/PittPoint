# Team Information
1. Ryan Evanik, rde21@pitt.edu
2. Sara Bergstrom, sab692@pitt.edu
3. Tyler Pierce, typ22@pitt.edu
4. Elena Tamba, elt160@pitt.edu


# Website Overview

Welcome to the **PittPoint** repository! PittPoint is the all-in-one platform for University of Pittsburgh students, featuring personalized schedules, an AI assistant, and campus news—making student life organized and accessible.

---

## Features

### Homepage
The **Homepage** serves as the first point of contact for visitors. It provides an overview of the website, including a welcome video that can be changed by university staff to display current events on campus, weekly news, hype videos, and more. The design is clean and user-friendly, ensuring an easy experience for all visitors.

### Schedule and Calendar
The **Schedule and Calendar** tab allows users to view and manage their schedules. 
- The **Calendar** displays upcoming events, appointments, or tasks. 
- Users can create, edit, and delete their schedule items.

### Gemini
In the **Gemini** tab, users can interact with an AI assistant.
- This feature allows users to type in questions, and Gemini will generate a response based on the input.
- The goal of this feature is to provide fast and useful answers on various topics without the need for an advisor appointment.

### Advisors and Contact Information
The **Advisors and Contact Information** tab lists a directory of available advisors. 
- Each entry includes the advisor's name, email, phone number, and areas of expertise.
- Users can easily reach out to advisors through the listed contact details.

### Sign-in Page
The **Sign-in Page** is the first page users encounter before accessing the website’s core features.
- It uses a secure authentication system that requires users to sign in with their Pitt username and password.
- Once authenticated, users can access the rest of the website’s content and functionalities.
- Genuine Pitt authentication is not implemented due to not having access to those features.

---

## How to Set Up Locally

To set up and run this website on your local machine, follow these steps:

### Prerequisites:
1. Ensure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.
2. Clone this repository: 
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
3. Navigate to the project directory:
   ```bash
   cd your-repo-name
   ```
5. Install the required dependencies:
  ```bash
   npm install
  ```
Running the Website Locally:

7. Start the development server:
  ```bash
    npm start
  ```
6. Open your browser and go to:
  ```bash
    http://localhost:3000
  ```

## How It Works:

### 1. Sign-in Process:
  Users sign in through the authentication page. Once the user submits their credentials they will be granted access to the site via the homepage.

### 2. Tab Navigation:
  After signing in, users can navigate the site using the tabbed menu at the top of the screen. There is currently 5 tabs on the website however more are planned in future iterations.

### 3. Schedule and Calendar Management:
  Users can add, edit, or delete events from their schedule through an easy-to-use form. We hope to be able to incorporate Gemini into this portion of the application as well.

### 4. Gemini Interaction:
  In the Gemini tab, users enter a question, and the Google AI generates a response based on a Gemini model that was trained by us. We included commonly asked questions and responses from numerous Official University of Pittsburgh sources in our training data.

### 5. Contacting Advisors:
  Users can access the advisor directory to contact an advisor directly from the listed details. A search feature will eventually be implemented to make searching for advisors less tedious.
