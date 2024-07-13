<h1 align="center">
  <br>
    <img src="./images/book-4986.png">
    <br>
    <br>
  Bookworm
    <br>
  <br>
</h1>



## Description
<h4><strong>Bookworm is a one stop book trading platform, allowing users to not only search for their favorite books by ISBN, but also intereact with other users to trade books with each other.</strong></h4>

## Features

### Login & Register Functionality
Leveraging the relationality of PostgreSQL, the Book Exchange has the ability to create new users, and also allow those users to have books that correspond with their user profile. 


### Add Favorite Books By ISBN
Want to add your favorite book? Simply find your favorite reading material's ISBN and add it to the Book Exchange to have a customized platform to note the books you currently own!



## Stack

### React
The choice of React comes with the SPA nature of this type of application designed to render views and easily convert between web or mobile. The reusability of the components and modularity was also key, as we wanted the application to be able to be iterated over by future open source developers. Also, React has the capabilities of server side rending, allowing developers to utilize the Vitual DOM without needing to update the view every time. 

### PostgreSQL
The use of PostgreSQL was chosen to efficiently combine our highly relational data with the combination of users that we required for the application. The relational nature of a SQL database allowed an overarching top down view of the data we were moving from the backend to the frontend, and allowed concise data movement as we were developing the application. 

### Bcrypt
Bcrypt was an ideal choice to encrypt the passwords for our users, as we felt its unique salt hashing system would add increased security, and also an easy framework for hashing passwords exponentially more if warranted. 

### Node / Express
Node and Express was chosen to keep “language consistency" between front and back end. It is a cross-platform runtime environment built on V8, high-performance open-source JavaScript engine, ensures excellent performance in an event-driven, non-blocking I/O paradigm.

## Getting Started
### Close this repository
```bash
git clone 
```

### Install dependencies
```bash
npm install
```

### Run in development
```bash
npm run dev
```

### Start an instance
```bash
npm start
```

#### Happy Book Trading!

