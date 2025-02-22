# WELCOME TO LUNCH BUDDIES!!!
### _An application that lets you find and match with like-minded students on campus to study, have a meal with, and more!_
---
# 📖 Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Install](#install)
4. [Usage](#usage)
6. [Contributing](#contributing)
7. [Resources](#resources)

---


## 💡 Introduction
- Lunch Buddies is a mobile application that helps students on campus connect with like-minded peers to study, share meals, and hang out. The app uses React Native for the front end, Golang for the API, and MySQL for database management.

---

## ✅ Prerequisites
- Before installing Lunch Buddies, ensure you have the following installed:
1. [Node.js](https://nodejs.org/en/)
2. [Golang](https://go.dev/dl/)
3. [MySQL](https://dev.mysql.com/downloads/windows/installer/8.0.html)

---

## 🛠️ Install

### 1. Clone the Repository

```bash
git clone https://github.com/ufosc/Lunch_Buddies.git
cd Lunch_Buddies
```

### 2. Install Node.js
- [Download Node.js (v16.18.0)](https://nodejs.org/en/)
- Verify installation:

```bash
node --version
npm --version
```

### 3. Install Golang

- [Download Golang](https://go.dev/dl/)
- Verify installation:

```bash
go version
```

### 4. Set Up MySQL

- [Download MySQL](https://dev.mysql.com/downloads/windows/installer/8.0.html)
- Create a new MySQL user.
- Run the following SQL commands in your MySQL terminal:

```sql
-- Paste contents from api/database.sql here
```

### 5. Install Dependencies

- **For Front-End:**

```bash
cd client
npm install
npm i expo-cli
```

- **For Back-End:**

```bash
cd ../api
go get
```

---
## Usage
- Before running the application, copy the `.env.example` file into a file called `.env` and fill in the corresponding credentials.
- To run the front-end, use the command `npm run start` in the client folder.
- To run the server, enter the api folder and run `go build`, and then run the executable that is created.

- Download the "Expo Go" app in order to emulate the current version of your app.
    - You need to create an Expo account
    - NOTE: Make sure your dev machine(desktop, laptop, etc.) and your smartphone are on the same wi-fi network
    - After running `npm run start` in the client folder, a QR code should be generated  
    - For iOS: scan QR code with iPhone camera
    - For Android: use the Expo Go app to scan the QR code
    
---    
## 🐛 Debugging
- Expo provides tools to debug the app
- Error messages are displayed on your phone, any speccific errors can be searched online or discussed with tech leads
- Shaking the device will open the developer menu, which allows you to refresh the app
- Remote JS debugging is available in a browser, and the element inspector will list the characteristics of a given component.

---
## Contributing
- All contributions are welcome and appreciated!!
    - Programming Languages: JavaScript, Go
    - UI software framework: React Native
    
#### Tech Used

- **Frontend:** React Native
- **Backend:** Golang
- **Database:** MySQL

### How to Contribute

1. **Fork the repo** and create a new branch:
```bash
git checkout -b feature/your-feature-name
```

2. **Make changes** and commit:
```bash
git commit -m "Add your feature"
```

3. **Push to GitHub** and open a pull request. 

## Resources:
- You can use these links to get familiar with programming languages/frameworks/libraries we will be using:
    - [React Native Getting Started](https://reactnative.dev/docs/environment-setup)
    - [React Native App Tutorial](https://www.youtube.com/watch?v=0-S5a0eXPoc)
    - [Beginners JavaScript Tutorial](https://www.youtube.com/watch?v=PkZNo7MFNFg&t=2783s)
    - [Expo Documentation](https://docs.expo.dev/)
    - [Golang Documentation](https://go.dev/doc/)
   
   
