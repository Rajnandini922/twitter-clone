# twitter-clone
 Twitter clone using react.js, next.js, mongodb and tailwind css.
  Simple tutorial with social sign in, tweeting, likes/hearts, comments/replies, profile edits (username, name bio), drag&drop image uploads and much more.
 Welcome to the Twitter Clone project! This project is a full-stack application that replicates the core functionalities of Twitter using modern web technologies. It uses React.js and Next.js for the front end, MongoDB for the database, and Tailwind CSS for styling.

Table of Contents
Features
Getting Started
Prerequisites
Installation
Running the Application
Folder Structure
Technologies Used
Contributing
License
Features
User Authentication
Social Sign-In (Google, Facebook, etc.)
Tweeting
Create, Read, Delete Tweets
Drag-and-Drop Image Uploads
Interactions
Like/Heart Tweets
Comment/Reply to Tweets
Profile Management
Edit Profile (Username, Name, Bio)
Responsive Design
Fully responsive design using Tailwind CSS
Getting Started
To get a local copy up and running follow these simple steps.

Prerequisites
Make sure you have the following installed on your local machine:

Node.js
MongoDB
Git
Installation
Clone the repository:
sh
Copy code
git clone https://github.com/yourusername/twitter-clone.git
Navigate to the project directory:
sh
Copy code
cd twitter-clone
Install the dependencies for the client and server:
sh
Copy code
npm install
Set up your environment variables. Create a .env file in the root directory and add the following:
env
Copy code
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
NEXT_PUBLIC_API_URL=http://localhost:3000/api
NEXT_PUBLIC_GOOGLE_CLIENT_ID=your_google_client_id
NEXT_PUBLIC_GOOGLE_CLIENT_SECRET=your_google_client_secret
NEXT_PUBLIC_FACEBOOK_CLIENT_ID=your_facebook_client_id
NEXT_PUBLIC_FACEBOOK_CLIENT_SECRET=your_facebook_client_secret
Running the Application
Start the MongoDB server:
sh
Copy code
mongod
Start the Next.js development server:
sh
Copy code
npm run dev
The application will be available at http://localhost:3000.

Folder Structure
plaintext
Copy code
twitter-clone/
├── components/      # Reusable React components
├── pages/           # Next.js pages
├── public/          # Public assets
├── styles/          # Tailwind CSS styles
├── utils/           # Utility functions
├── .env             # Environment variables
├── .gitignore       # Git ignore file
├── next.config.js   # Next.js configuration
├── package.json     # Project dependencies and scripts
├── README.md        # Project documentation
└── server.js        # Custom server (if applicable)
Technologies Used
Frontend:

React.js
Next.js
Tailwind CSS
Backend:

Node.js
MongoDB
Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
License
Distributed under the MIT License. See LICENSE for more information.
