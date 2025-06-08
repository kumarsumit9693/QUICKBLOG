QuickBlog
Live Demo: quickblog-chi.vercel.app

QuickBlog is a full-stack blogging platform built with React.js, Node.js, Express.js, and MongoDB, designed to offer a seamless writing and reading experience. 
Users can create, update, and delete blog posts, while also viewing trending and latest content.
The platform integrates ImageKit for optimized image uploads and AI-generated descriptions for intelligent content suggestions.

Tech Stack
Frontend: React.js, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB (Mongoose)

API Testing: Postman

Image Hosting: ImageKit.io

AI Integration: Custom API to generate blog descriptions using OpenAI

Features
Create & Publish blogs with title, category, image, and auto-generated description

Edit/Delete your own blogs securely

Browse blogs by category or recency

AI-generated blog summaries to speed up writing

Optimized image upload via ImageKit for faster loading

Secure API routes with input validation

Folder Structure 

quickblog/
├── client/        # React Frontend
│   └── src/
│       └── pages, components, api etc.
├── server/        # Node + Express Backend
│   └── routes, controllers, models
├── .env           # Environment config (not committed)


