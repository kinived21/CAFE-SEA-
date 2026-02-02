# CafeSea - Food Delivery App 🍔☕

![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase&logoColor=white)

CafeSea is a modern Android application built with **Kotlin** and **Firebase** that allows users to browse a cafe menu, manage a cart, and place orders seamlessly.

---

## ✨ Features
* **Real-time Menu:** Fetches food items and categories directly from Firebase Realtime Database.
* **Smart Cart:** Add, remove, or update quantities with instant price calculation.
* **Hybrid Payments:** * **Cash on Delivery (COD):** Fast one-tap checkout.
    * **Online Payment:** Integrated **UPI Intent** (GPay, Paytm, etc.) with automatic order placement upon success.
* **Shimmer Loading:** Professional skeleton screens to show loading states.
* **Profile Management:** Stores user address, order history, and contact details.

## 🛠️ Tech Stack
* **Language:** Kotlin
* **Database:** Firebase Realtime Database
* **Auth:** Firebase Authentication
* **UI:** Material Design 3, XML, Facebook Shimmer Effect
* **Image Loading:** Glide

---

## 📸 Screenshots

### 🛒 Ordering Flow
| Login | Home Screen | My Favourite | My Cart | Payment |
| :---: | :---: | :---: | :---: | :---: |
| ![Login](https://github.com/user-attachments/assets/c6437680-6297-4b0a-9022-9611af3c9f3b) | ![Home](https://github.com/user-attachments/assets/75eef807-0392-4679-ba82-8e1217f48ab5) | ![Fav](https://github.com/user-attachments/assets/3503a889-3f3d-4e7c-b0df-eec44a667689) | ![Cart](https://github.com/user-attachments/assets/d723fe53-f029-4e35-85af-a4d4cfc67237) | ![Pay](https://github.com/user-attachments/assets/38ec42e1-b4c8-4165-9ef4-32a6b9db6c3e) |

### 👤 Profile & Support
| Profile | Edit Profile | Address | My Orders | Feedback |
| :---: | :---: | :---: | :---: | :---: |
| ![Profile](https://github.com/user-attachments/assets/7e1834ba-89f2-4153-bf39-0754648bd503) | ![Edit](https://github.com/user-attachments/assets/22639659-ed3a-4fcc-9a86-67431fdea2a9) | ![Address](https://github.com/user-attachments/assets/65359c23-3004-497b-90ad-907a9a4e3194) | ![Orders](https://github.com/user-attachments/assets/8176ac45-0a02-4ab7-ac5c-6eff1469df82) | ![Feed](https://github.com/user-attachments/assets/70910d17-8eeb-4a9a-89f0-cc52541ee34a) |

| Support | Settings |
| :---: | :---: |
| ![Support](https://github.com/user-attachments/assets/2f7249d1-d794-45bd-b660-d2fcabf43abb) | ![Settings](https://github.com/user-attachments/assets/3c8a6c99-96b6-44ef-a4da-1a1e922b01f6) |

---

## 🧠 Technical Challenges & Solutions
* **UPI Intent Integration:** Implemented deep-linking to interact with external payment apps. Handled Android 11+ package visibility requirements by adding proper `<queries>` in the Manifest.
* **Real-time Synchronization:** Used Firebase `ValueEventListener` to ensure that item quantity changes in the cart instantly reflect in the final price calculation.
* **UI Polish:** Integrated **ShimmerFrameLayout** to provide a smooth user experience while data is being fetched from the cloud.

## 🚀 How to Run
1. Clone this repository.
2. Add your `google-services.json` file from Firebase to the `app/` folder.
3. Enable **Realtime Database** and **Email Auth** in your Firebase console.
4. Run the app on a physical Android device to test UPI payments.

---
Developed by **Ved Narayan Kini**
