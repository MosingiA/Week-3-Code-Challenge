# 📬 Post Pulse

**Post MANAGER BLOG** is a simple, dynamic blog post manager built with **HTML**, **JavaScript**, and **Tailwind CSS**. It uses `json-server` as a mock REST API to create, read, update, and delete blog posts in real time.

---

## Features

- View a list of blog post titles and their authors
- Display full post details on selection.
- Add new blog posts with title, author, image, and content
- Edit existing blog post title and content
- Delete posts from the list
- Responsive layout styled using Tailwind CSS

---

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/post-pulse.git
cd post-pulse
2. Install JSON Server globally (if not already installed)
bash
Copy
Edit
npm install -g json-server
3. Start the backend (API)
bash
Copy
Edit
json-server --watch db.json
Runs on: http://localhost:3000/posts

4. Start the frontend
Use live-server, VS Code's Live Server extension, or open index.html in your browser.

Project Structure
graphql
Copy
Edit
WEEK-3-CHALLENGE
│
├── index.html       # Main HTML file
├── styles.css       # Optional custom styles
├── index.js         # Main JavaScript logic
├── db.json          # JSON Server data source
└── README.md        # Project documentation

 How It Works
displayPosts(): Fetches all posts and renders them to the sidebar.

handlePostClick(post): Displays post details and injects edit/delete buttons.

addNewPostListener(): Handles new post creation and form logic.

PATCH / DELETE: Used to update or remove posts from the API.

 Tech Stack
HTML5

JavaScript

Tailwind CSS

JSON Server

