# Movie Review App

This project is a simple Movie Review application built using:

- Frontend: Lovable AI
- Backend Database: Firebase Firestore (NoSQL)

## Features
- Users can submit movie details and give ratings/reviews
- Data is stored in Firebase Firestore
- Reviews are displayed in the "Latest Reviews" section

## Database Schema (Firestore)

Collection name: reviews

Fields:
- movie_name (string)
- rating (number)
- review_text (string)
- reviewer_name (string)
- created_at (timestamp)

## Division of Work

Student 1:
- Designed front-end user interface using Lovable AI
- Created original GitHub repository
- Managed final merge

Student 2:
- Created Firebase database and collection
- Forked repository
- Created feature branch
- Updated README
- Raised Pull Request and resolved conflicts

## Note

Due to a TypeScript build limitation in Lovable while processing Firebase SDK, 
real-time integration could not be achieved directly inside Lovable. 
However, database connection and data persistence were successfully 
verified using Firebase Firestore.
