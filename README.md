# BackendMovielist-elec
# 🎬 Backend MovieList (Express.js + MongoDB)

## 📖 Overview
Backend MovieList is a RESTful API built using **Express.js** and **MongoDB**, allowing users to **fetch, add, and manage movies**, register accounts, **rate movies**, and **write reviews** via **Postman**.

## 🚀 Features
- 🧑‍💻 **User Authentication & Registration**
- 🎥 **CRUD Operations for Movies**
- ⭐ **Rate Movies & Write Reviews**
- 📁 **Data Storage in MongoDB**
- 🛠️ **API Testing with Postman**

## 🔗 API Endpoints

| **Method** | **Endpoint**                | **Description**           |
|-----------|----------------------------|---------------------------|
| `GET`     | `/api/movies`              | Get all movies            |
| `POST`    | `/api/movies`              | Add a new movie           |
| `GET`     | `/api/movies/:id`          | Get a single movie        |
| `PUT`     | `/api/movies/:id`          | Update a movie            |
| `DELETE`  | `/api/movies/:id`          | Delete a movie            |
| `POST`    | `/api/users`               | Register a new user       |
| `POST`    | `/api/movies/:id/reviews`  | Add a review for a movie  |
| `POST`    | `/api/movies/:id/rate`     | Rate a movie              |

## 🛠 Installation & Setup

## 🔧 Technologies Used

- **Node.js** – Backend runtime environment  
- **Express.js** – Web framework for Node.js  
- **MongoDB** – NoSQL database  
- **Mongoose** – ODM (Object Data Modeling) for MongoDB  
- **Postman** – API testing tool  

1️⃣ **Clone the repository**  
```sh
git clone https://github.com/yourusername/BackendMovieList.git
cd BackendMovieList
>>>>>>> d0dce5d8ea0bdb240af6cbf66f65d5e8b76217b9
