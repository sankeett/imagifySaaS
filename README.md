Imagify AI SaaS
Imagify AI is a Software-as-a-Service (SaaS) platform that transforms text descriptions into high-quality images using the ClipDrop API. Built with the MERN stack (MongoDB, Express.js, React.js, Node.js), this project offers a responsive and intuitive user interface, seamless API integration, and real-time image generation. Deployed on Vercel, Imagify AI showcases full-stack development capabilities, efficient state management, and scalable application architecture.
Features

Text-to-Image Conversion: Generate images from text prompts using the ClipDrop API.
Responsive UI: A user-friendly interface optimized for desktop and mobile devices.
Real-Time Processing: Instant image generation with minimal latency.
Scalable Backend: Robust MongoDB and Express.js setup for handling user requests.
State Management: Efficient React.js state management for a seamless user experience.
Deployment: Hosted on Vercel for reliable performance and scalability.

Tech Stack

Frontend: React.js
Backend: Node.js, Express.js
Database: MongoDB
API: ClipDrop API for text-to-image generation
Deployment: Vercel
Styling: CSS (with optional Tailwind CSS or similar frameworks)
Version Control: Git, GitHub

Installation
To run Imagify AI locally, follow these steps:
Prerequisites

Node.js (v16 or higher)
MongoDB (local or Atlas)
ClipDrop API key
Git

Steps

Clone the Repository:
git clone https://github.com/yourusername/imagify-ai.git
cd imagify-ai


Install Dependencies:
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install


Set Up Environment Variables: Create a .env file in the backend directory with the following:
MONGODB_URI=your_mongodb_connection_string
CLIPDROP_API_KEY=your_clipdrop_api_key
PORT=5000

Create a .env file in the frontend directory with:
REACT_APP_API_URL=http://localhost:5000/api


Run the Application:
# Start the backend server
cd backend
npm run start

# Start the frontend (in a new terminal)
cd frontend
npm run start


Access the App: Open http://localhost:3000 in your browser.


Usage

Sign Up / Log In: Create an account or log in to access the platform.
Enter Text Prompt: Input a descriptive text prompt for the image you want to generate.
Generate Image: Submit the prompt to create an image using the ClipDrop API.
Download or Share: Save the generated image or share it with others.

Deployment
To deploy Imagify AI on Vercel:

Push your code to a GitHub repository.
Connect the repository to Vercel via the Vercel dashboard.
Configure environment variables in Vercel (e.g., MONGODB_URI, CLIPDROP_API_KEY).
Deploy the backend and frontend separately or as a monorepo, depending on your setup.

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a pull request.


Contact
For questions or feedback, reach out via:

Email: sanketgolekar3@gmail.com
GitHub: sankeett

