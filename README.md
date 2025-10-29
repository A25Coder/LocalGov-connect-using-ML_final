LocalGov Connect

Connecting Citizens. Empowering Communities.

LocalGov Connect is a modern, real-time web application designed to streamline communication between citizens and their local government. It provides a platform for reporting civic issues, tracking their resolution, and fostering community engagement.


![re](https://github.com/user-attachments/assets/965c259c-051a-462e-aa00-6dba4755648a)


🚀 Core Features

Citizen Reporting: Users can submit new issues with a title, description, category, severity, and image upload.

Real-Time Issue Feed: A central dashboard showing all reported issues, updated live using Supabase Realtime.

Interactive Feed: Users can like/upvote issues to help officials prioritize, and view comment counts.

Dynamic Filtering: Filter the main feed by issue status (Pending, In Progress, Resolved), severity (e.g., Emergency, Critical, Minor), and category (e.g., Traffic, Roads, Water).

Trending Issues: A "Top Reports" sidebar shows the most-liked issues from the past week.

Community Stats: A high-level overview of total vs. resolved issues.

Dual User Roles: Separate login portals for Citizens and Government Officials.

🛠️ Tech Stack

Frontend: React

Routing: React Router

Backend-as-a-Service: Supabase

Database: Supabase (PostgreSQL)

Auth: Supabase Auth

Real-Time: Supabase Realtime (for live issue/like updates)

Functions: Supabase RPC (for toggle_like function)

Styling: Tailwind CSS

🏁 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

1. Prerequisites

Node.js (v18 or newer)

npm or yarn

A free Supabase account

2. Installation

Clone the repository:

git clone [https://github.com/your-username/localgov-connect.git](https://github.com/your-username/localgov-connect.git)
cd localgov-connect



Install dependencies:

npm install



3. Supabase Setup

Create a Supabase Project:

Go to supabase.com and create a new project.

Save your project's Project URL and anon key.

Create Environment File:

Create a file named .env in the root of your project.

Add your Supabase credentials. (Make sure to use the VITE_ prefix for React).

VITE_SUPABASE_URL=your-supabase-project-url
VITE_SUPABASE_ANON_KEY=your-supabase-anon-key

Set up the Database

4. Run the Application

You're all set! Run the development server:

npm run dev



Open http://localhost:5173 (or a different port if specified) to see your app in action.

📄 License

This project is licensed under the MIT License. See the LICENSE file for details. a platform for reporting civic issues, tracking their resolution, and fostering community engagement.
