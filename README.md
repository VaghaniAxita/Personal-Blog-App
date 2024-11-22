
# Personal Blog App 📝

A Personal Blog App where users can create, view, edit, and delete blog posts. This project demonstrates full-stack development with React.js (frontend), Node.js with Express.js (backend), and MongoDB (database).

## Features

1.  Create Post: Users can add new blog posts   with a title and content.

2. View All Posts: Posts are displayed in reverse chronological order.

3. View Post Details: View the full content of any blog post.

4. Edit Post: Modify the title or content of existing posts.

5. Delete Post: Remove a blog post permanently.

6. Responsive Design: Works seamlessly on both desktop and mobile.

7. Clean UI: Modern, minimalistic design inspired by platforms like Medium and Dev.to.




## Tech Stack

**Frontend:** 

       * React.js: For building the user interface.
       * Axios: For API requests.
       * React Router: For navigation.

**Backend:** 

        * Node.js: For server-side programming.
        * Express.js: For creating RESTful APIs.
        * Mongoose: For MongoDB schema definition and database interaction.

**Database:** 

    * MongoDB: NoSQL database for storing blog posts.

**Deployment:** 

    * Vercel: For hosting the frontend and backend.

## Backend Setup

Navigate to the backend folder:

```bash
  cd blog-backend
```

Install dependencies:

```bash
  npm init -y
  npm install express mongoose cors body-parser dotenv     
```

Create a .env file:

```bash
  MONGO_URI=your_mongo_db_connection_string
```

Run the backend server:
```bash
  node server.js
```

## Frontend Setup

Navigate to the frontend folder:
```bash
 npx create-react-app blog-frontend
 cd ../blog-frontend
```

Install dependencies:
```bash
  npm install axios react-router-dom
```

Run the development server:
```bash
  npm start
```



## Usage

Creating a Post

- Navigate to the /create page.
- Fill in the post's title and content.
- Submit the form to add the post.
------------------------
Viewing All Posts

- The home page (/) lists all blog posts.
- Posts are displayed in reverse chronological order.

------------------------
Editing a Post

- Click on any post to view its details.
- Navigate to the "Edit" button to modify the post's title or content.

------------------------
Deleting a Post

- While viewing a post, click the "Delete" button to remove it.

---------------------
## Deployment

Backend Deployment

```bash
  npm install -g vercel
  cd blog-backend
  vercel
```
------------------------
Frontend Deployment

```bash
  npm run build
  vercel
```
