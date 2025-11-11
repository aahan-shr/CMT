# 🎯 CMT (Conference Management Toolkit)

It ia a conference management toolkit based on a website Microsoft CMT.  
It is a well authenticate app while have email based login or signup.  
If user had forget or want to reset password it can be achive in our app.  

There are 3 different login interfaces in our app:  
1.  Author interface  
2.  Reviewer interface  
3.  Admin interfaces  
We naviagte them according to thier Role.  

---

## 🧑‍💻 Author Interface

It have an beautiful home interface which have features of update profile, reset password, help & support, and a direct feature foe logout and delete account.  
Author have features to see all conferences, then if have willing to submit a paper in his desired conference, user can select it and submit its paper in that selected conference.  
He will have to make sure during submit his paper he have to enter its paper pdf version link in that.  
After succesfully submitting his paper, he can see its join conferences on dashboard also accessible to his submitted paper and also delete, edit them.  
And see his submitted paper review by a assign reviewer through admin.  

---

## 👑 Admin Interface

Admin have all access to whole thing, he can manage All user, All reviewer within the app, restrict them to use app further in future.  
Admin is going to approve reviewer, if any user choose option as reviewer on create account interface.  
Admin have option to create conference with desired details and a pdf url also in it.  
Admin can see those conferences, with edit, delete features in it.  
Admin is going to assign verified reviewer to submited paper's and he will make sure only 3 different reviewer is going to assign those paper's.  
Admin can access those submitted paper in each conference.  

---

## 🕵️ Reviewer Interface

Anyone want to be a verified reviewer, he will need admin confirmation for that.  
He has option of to see assign paper on its home screen.  
Then review the assign paper and put a pdf verison url of it.  
He can see all conferences, their particular submitted paper but not going to review those or make changes.  
During that if he desired to review a paper which is not assign to it, he can bid for it by tick checkbox given in that paper.  
And then admin receive the list and he see then capable then assign then to that paper.  

---

## ⚙️ Backend

Its a fully functional app with firebase backend.  
If user have to create account then he have to verify its email.  

---

## 🧱 Technology Stack

- 🧩 **Flutter (Front-End Framework)** — fully built using Flutter SDK.  
- 🔥 **Firebase (Backend)** — for authentication, Firestore database, and storage.  
- ✉️ **Firebase Authentication** — handles login, signup, email verification, and password reset.  
- ☁️ **Cloud Firestore** — stores user details, conferences, paper submissions, and reviews.  
- 📦 **Firebase Storage** — stores paper and review PDF links.  
- 🎨 **Flutter UI** — role-based navigation (Author, Reviewer, Admin) with clean and modern design.  

---

## 📱 Screenshots

| Login Page | Author Dashboard | Reviewer Dashboard | Admin Panel |
|-------------|------------------|--------------------|--------------|
| ![Login](screenshots/login.jpg) | ![Author](screenshots/author_home.jpg) | ![Reviewer](screenshots/reviewer_home.jpg) | ![Admin](screenshots/admin_home.jpg) |

> 📸 *You can add your actual app screenshots in the `screenshots/` folder.*

---

## 📦 APK Download

You can download the latest version of CMD App here:  
👉 [**Download CMD.apk**](./CMD-App.apk)

> *(Place your APK file in the root directory and rename it `CMD-App.apk` before pushing to GitHub.)*

---

## 🧰 Key Features

| Role | Features |
|------|-----------|
| **Author** | See and join conferences, submit papers with PDF link, edit/delete submission, view assigned reviews |
| **Reviewer** | See assigned papers, review with PDF link, bid for papers, view all conferences |
| **Admin** | Manage all users/reviewers, approve reviewers, create/edit/delete conferences, assign reviewers to papers |

---

## 🧩 Built With

- 🧱 **Flutter SDK**  
- 🔥 **Firebase Authentication**  
- ☁️ **Cloud Firestore**  
- 📂 **Firebase Storage**  
- 💬 **Dart Programming Language**  
- 🎨 **Material Design Widgets**

---

⭐ *CMD is a conference management toolkit fully built with Flutter and Firebase backend that provides a complete platform for Authors, Reviewers, and Admins to manage conferences, papers, and reviews seamlessly.*
