# 📂 E-Commerce Back End 📂
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📚 Description
This is a back-end application for an e-commerce site. This application uses Express.js API and Sequelize to interact with a MySQL database. This application displays creation, reading, updating, and deletion (CRUD) operations in the database.

## 📖 Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Questions](#questions)

## 💽 Installation
To get this application up and running on your own system, follow these steps:
```bash
git clone https://github.com/Dominick-D/ORM
cd ../path/to/root/ORM
npm install
```
After the dependencies are installed, log into your MySQL server and enter the following command to set up the database:
```sql
source db/schema.sql
exit
```
Once the database is set up, seed it with some initial data (If needed) by running:
```bash
npm run seed
```
## 🎯 Usage
[Walkthrough Video 🎥](https://drive.google.com/file/d/15pGhMljzNMGSOfN_zJ3VU38aJNxPds6s/view?usp=drive_link)

Once you've successfully installed all the required dependencies, the application is ready for use. Invoke it by running the following command:

```bash
node server.js
```
You'll be able to perform CRUD operations for categories, products, and tags in your e-commerce database.

## 📜 License
This project is licensed under the **MIT** license.

## ❓ Questions
If you have any questions about the repo, open an issue or contact me directly at [Here](dominickdonn.me/contact). You can find more of my work on [my portfolio](domdonn.me).