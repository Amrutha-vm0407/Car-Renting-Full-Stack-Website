
<h1 align="justify">About Car Rentals</h1>

<p>A car rentals website built with ReactJS and MongoDB allows users to browse, reserve, and manage car bookings easily. ReactJS provides a dynamic, user-friendly interface for searching and filtering cars, while MongoDB stores user data, booking details, and car inventory efficiently. The site can offer real-time availability and secure login using React's state management and MongoDB's flexible schema. This combination enables scalable, responsive, and interactive car rental services for customers.</p>

<h1>Technology used</h1>
<p><B>HTML5</B>: For structuring the interface.</p>
<p><b>CSS3</b>: For styling the elements and creating a responsive design.</p>
<p><b>JavaScript (ES6)</b>: For implementing logic, handling user interactions, and updating the user move state dynamically.</p>
<p><b>ReactJS</b> : ReactJS is used for building efficient, interactive UIs with a component-based structure and fast updates through a virtual DOM. It promotes reusability, performance, and easier maintenance in web applications.</p>
<p><b>NodeJS</b> : Node.js is a runtime that allows JavaScript to run on the server side, enabling scalable, real-time applications. It uses a non-blocking, event-driven architecture for handling multiple connections efficiently.</p>
<P><b>ExpressJS</b> : Express.js is a lightweight web application framework for Node.js that simplifies building APIs and web applications</P>
<P><b>MongoDB</b> : 
MongoDB is a NoSQL database that stores data in flexible, JSON-like documents, making it highly scalable and suitable for handling large, unstructured datasets.</P>

<h1>Screenshots of the application</h1>
<h1>Home Page</h1>
<img src=Car-renting-Full-Stack-Website-main/images/home%20page.png  width="500" height="316">

<h1>Contact Page</h1>
<img src= Car-renting-Full-Stack-Website-main/images/contact%20page.png  width="500" height="316">

<h1>Service Page</h1>
<img src=Car-renting-Full-Stack-Website-main/images/service%20page.png  width="500" height="316">

<h1>Cars Page</h1>
<img src=Car-renting-Full-Stack-Website-main/images/cars%20page.png width="500" height="316" >

<h1>Cars booking Page</h1>
<img src= Car-renting-Full-Stack-Website-main/images/cars%20booking%20page.png width="500" height="316">

<h1>Admin Dashboard</h1>
<img src= Car-renting-Full-Stack-Website-main/images/admin%20dashboard.png width="500" height="316">

<h1>Car Management page</h1>
<img src=Car-renting-Full-Stack-Website-main/images/car%20management%20page.png  width="500" height="316">

<h1>Car adding page</h1>
<img src= Car-renting-Full-Stack-Website-main/images/adding%20cars%20page.png width="500" height="316">

<h1>Number of cars booked</h1>
<img src= Car-renting-Full-Stack-Website-main/images/numbers%20of%20cars%20booked.png width="2000" height="316">


## Application Structure
```
│
├── bin
├── models (MongoDB Mongoose Models)
├── node_modules 
├── public (application resources - css, js, images)
├── routes (handles admin, electric and gas routes)
├── views  (express-handlebars templates)
    ├── admin (admin templates)
    ├── layouts (default layout templates)
    └── electric and gas template files
├── app.js (root Node app script)
├── package.json
└── README.md
```


## 📋 Instructions
1. Install Dependencies using `npm install`
2. Make sure `MongoDB` server is running
3. Create a database named `CarRentals`
4. Create all the required `collections` in the created database and fill in the data from `db_data`


#### Local
1. Inside  `--> app.js` under MongoDB section, replace the url with `mongodb://localhost:27017/CarRentals`
2. Open Terminal in the app folder
3. Run `npm start` or `nodemon start` (if nodemon is preinstalled)
4. Launch client app in `localhost:5000`
4. Launch admin app in `localhost:5000/admin`
   


