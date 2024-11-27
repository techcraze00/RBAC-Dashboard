# Role Based Access Control (RBAC) Dashboard



[**Project working demonstration**](https://www.youtube.com/watch?v=Pn_RWrchAII)


A minimal, efficient, and user-friendly admin dashboard to manage users, roles, and permissions using Role-Based Access Control (RBAC). Built with **CSS** for the frontend and **Express.js** for the backend.

This is a Role Based Access Control application using Nodejs, Express, Passport Js, etc.
You can use this application as the starting point for whatever project you are going to build which needs authentication and authorization.

For authentication we have only Email & Password option but other authentication options using OAuth/OAuth2.0 like Google, Facebook, Apple, GitHub, etc, can be easily incorporated.

The application is based on the **MVC pattern** i.e. Model View Controller.

**Mongoose** is used as an ORM for MongoDB for storing Users in Database.

**Passport JS** is used for local(email, password) authentication.


---




## To start setting up the project

Step 1: Clone the repo

```bash
git clone https://github.com/trulymittal/role-based-access-control
```

Step 2: cd into the cloned repo and run:

```bash
npm install
```

Step 3: Put your credentials in the .env file.

```bash
PORT=3000
MONGODB_URI=YOUR_MONGODB_URI(example: mongodb://localhost:27017)
DB_NAME=YOUR_DB_NAME
```

Step 4: Install MongoDB (Linux Ubuntu)

See <https://docs.mongodb.com/manual/installation/> for more infos

Step 5: Run Mongo daemon

```bash
sudo service mongod start
```

Step 6: Start the app by

```bash
npm start
```
---

### **Prerequisites**
Ensure you have the following installed on your machine:
- [Node.js](https://nodejs.org/) (v16 or later)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)

---

## Author

- [**TechCraze**](https://github.com/techcraze00)

## Contribute

You can fork this repo and send me a PR.

## License

This project is licensed under the MIT License.

---

#### This project is inspired from [**Truly Mittal**](https://trulymittal.com)

---

## Contact

If you have any questions or suggestions, feel free to reach out:

Email: techcraze00@gmail.com

