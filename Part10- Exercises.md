# Part 10: React Native — Exercises 10.19–10.26

This folder contains my completed exercises for **Full Stack Open Part 10**.  
I completed all tasks on my **Connex Serenity Tablet 1055 (Android)** using **GitHub Mobile** and **Expo Go**.

---

## 📱 Overview

These exercises continue the development of a React Native app that interacts with a GraphQL backend.  
The goal is to implement views, navigation, and testing for a mobile version of the Full Stack application.

---

## 🧩 Exercises Breakdown

### 🧠 **10.19 — Single Repository View**
- Implemented a **view for a single repository** showing details such as name, rating, stars, and forks.
- Used `useParams()` from React Router Native to get the repository ID.
- Created a **button** that opens the repository on GitHub using `Linking.openURL()` from the Expo Linking API.
- Reused the `RepositoryItem` component and added a `showGithubButton` prop to toggle the button display.

### ⚡ **10.20 — Repository Reviews**
- Displayed a list of **reviews** for each repository.
- Created a new GraphQL query `GET_REPOSITORY` to fetch repository details and reviews.
- Used `FlatList` to render all reviews neatly with proper styling.

### ✍️ **10.21 — Create a Review**
- Implemented a **ReviewForm** screen for users to add a new review.
- Used **Formik** and **Yup** for form handling and validation.
- Submitted new reviews through a `CREATE_REVIEW` mutation.

### 🔁 **10.22 — Navigation to Repository View**
- Configured React Navigation to allow users to open repository details by tapping an item from the repository list.
- Verified smooth navigation between screens using `useNavigate()` and React Native Navigation Stack.

### 🧭 **10.23 — My Reviews View**
- Implemented a new screen to show the currently logged-in user’s reviews.
- Added functionality to **delete reviews** with a confirmation dialog.

### 🧹 **10.24 — Deleting a Review**
- Added a `DELETE_REVIEW` mutation.
- Displayed a confirmation prompt before deletion and updated the list after removing a review.

### 🧑‍🔬 **10.25 — Testing the Application**
- Wrote basic tests using **React Native Testing Library** for:
  - Repository list rendering
  - Review form validation
  - Navigation functionality

### 🚀 **10.26 — Final Polishing**
- Cleaned up all code and styling.
- Verified app works on both **Android (Expo Go)** and emulator.
- Confirmed that all queries, mutations, and navigation paths function correctly.

---

## 🧠 Technologies Used
- **React Native**
- **Expo**
- **Apollo Client**
- **GraphQL**
- **Formik + Yup**
- **React Navigation**
- **React Native Testing Library**

---

## 💡 Notes
- Completed and tested using **Connex Serenity Tablet 1055 (Android)**.
- Used **Expo Go app** for live preview and testing.
- Committed each exercise to GitHub with descriptive commit messages.

---

## 📎 Submission Info
**Submitted for:** University of Helsinki — Full Stack Open  
**Part:** 10  
**Exercises:** 10.19–10.26  
**Completed by:** *Gladys Masia*  
**Device Used:** Connex Serenity Tablet 1055  
**Repository Link:** *(---

## 📎 Submission Info
**Submitted for:** University of Helsinki — Full Stack Open  
**Part:** 10  
**Exercises:** 10.19–10.26  
**Completed by:** *Gladys Masia*  
**Device Used:** Connex Serenity Tablet 1055 (Android)  
**Repository Link:** ([https://github.com/Gladys334/Full-Stack-Open-Part-10])
