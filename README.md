# **📌 React Native User Inf App**  
A **React Native** app built with **Expo** that fetches and displays user information from the Random Data API. It allows users to navigate through 80 different users with **Next/Previous** buttons.  

---

## **📷 Preview**  
🎥 **Watch the Demo Video** 👉 

https://github.com/user-attachments/assets/ee495a31-d6c7-4d82-8449-c6e825040a90

---

## **📜 Features**  
✅ Fetches **user data** from a public API  
✅ Displays **ID, username, email, avatar, and more**  
✅ **Next/Previous** buttons to browse users  
✅ Stores API data locally to minimize API calls  
✅ Built with **React Native & Expo**  

---

## **🏗 Folder Structure**  
```bash
📦 UserInfApp  
 ┣ 📂 assets  
 ┃ ┣ 📜 adaptive-icon.png  
 ┃ ┣ 📜 favicon.png  
 ┃ ┣ 📜 icon.png  
 ┃ ┗ 📜 splash.png  
 ┣ 📂 components  
 ┃ ┣ 📜 ProfileField.js  
 ┃ ┗ 📜 UserCard.js  
 ┣ 📂 screens  
 ┃ ┗ 📜 UserScreen.js  
 ┣ 📂 services  
 ┃ ┗ 📜 api.js  
 ┣ 📜 .gitignore  
 ┣ 📜 app.js  
 ┣ 📜 app.json  
 ┣ 📜 index.js  
 ┣ 📜 package-lock.json  
 ┣ 📜 package.json  
 ┗ 📜 README.md  
```

---

## **🛠 Installation & Setup**  

### **1️⃣ Prerequisites**  
Ensure you have the following installed:  
🔹 **Node.js** ([Download](https://nodejs.org/))  
🔹 **Expo CLI** ([Install via npm](https://docs.expo.dev/get-started/installation/)):  
```sh
npm install -g expo-cli
```

---

### **2️⃣ Clone the Repository**  
```sh
git clone https://github.com/Manishsuyal31/UserInfApp.git  
cd UserInfApp  
```

---

### **3️⃣ Install Dependencies**  
```sh
npm install  
```

---

### **4️⃣ Start the App**  
Run the app on a **mobile device or emulator**:  
```sh
npx expo start  
```
👉 **For Android:** Use the **Expo Go app** to scan the QR code.  
👉 **For iOS:** Run on **iPhone Simulator** (Mac required).  

---

## **🚀 How It Works**  
1️⃣ **Fetches 80 users** from Random Data API at startup.  
2️⃣ **Displays one user per screen** with:  
   - `id`, `uid`, `password`, `first_name`, `last_name`, `username`, `email`, `avatar`  
3️⃣ **Navigation buttons** allow browsing between users.  
4️⃣ Stores **fetched data locally** to reduce API calls.  

---

## **🔗 API Details**  
📌 **Random Data API** is used to fetch user data.  
- **Fetch one user:**  
  ```sh
  https://random-data-api.com/api/users/random_user?size=1  
  ```
- **Fetch 80 users at once:**  
  ```sh
  https://random-data-api.com/api/users/random_user?size=80  
  ```
- API responses include:  
  ```json
  {
    "id": 123,
    "uid": "abc-xyz",
    "password": "securePass",
    "first_name": "John",
    "last_name": "Doe",
    "username": "johndoe",
    "email": "john.doe@example.com",
    "avatar": "https://randomuser.me/api/portraits/men/1.jpg"
  }
  ```
---

## **🚀 Future Scope & Next Steps**

✅ **User Search & Filtering** – Allow users to search by name, email, or username.\
✅ **Favorite Users** – Save favorite profiles locally for quick access.\
✅ **Dark Mode Support** – Enhance UI with light & dark themes.\
✅ **Better Error Handling** – Improve handling of API failures & loading states.\
✅ **Pagination Instead of Preloading** – Load users dynamically instead of all at once.\
✅ **Improve UI with better styling and animations** – Enhance the app's UI with modern styling techniques and smooth animations.

---

## **📬 Contact**

🔹 **Name:** Manish Singh Suyal\
🔹 **Email:** manishsuyal951@gmail.com
