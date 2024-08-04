# Build and Deploy a MERN(MongoDB, Express JS, React, Node JS) Stack Admin Dashboard

Live at [https://harikiranvusirikala-admin-dashboard.onrender.com/](https://harikiranvusirikala.github.io/Kirby-Game/).


- For frontend, I have used Material UI (for styling), Material UI Data Grid(for tables), Nivo Charts(for charts), Redux Toolkit(for state management) and Redux Toolkit Query(for making API calls).

- For backend, I have used Node JS(as runtime), Express Js(as backend framework), Mongoose(for managing MongoDB), and MongoDB.


## Backend file structure and changes needed to implement new page/feature:
1. data folder -> data in js to import to MongoDB
2. models folder -> MongoDBschema for each type, create a schema and import data into MongoDB with code in index.js
3. routes folder -> separate routing file for separate use cases
4. controllers folder -> code to interact with DB, make logical operations to data, send response

## Frontend file structure and changes needed to implement new page/feature:
1. state folder -> api.js using redux toolkit to get data from backend
2. App.js -> Add a route to display a page from scene folder
3. scenes folder -> React page to display the content (rafce to generate boiler code)
4. components folder -> a reusuable react component with custom display format (rafce to generate boiler code)
