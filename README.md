# Budget Bunny

## 👥 Team Members
| Name | Student Number |
|:----------------------|:---------------|
| Ebrahim Seedat | ST10257926 |
| Gabriella Delgado | ST10401920 |
| Jashan Chetty | ST10312554 |
| Rishka Rajhunee | ST10314285 |
| Tafadzwa Phiri | ST10029491 |
| Warona Phale | ST10271625 |

---

## 🎥 Youtube Video
Check out our Budget Bunny project walkthrough here:  
👉 [Watch the YouTube Video](https://youtu.be/juXMgUIHil4)

---

## 🔗 GitHub Repo Link
👉 https://github.com/VCSTDN2024/prog7313-part3-poe-budgetbunnies-poe.git

---

## 📱 About the App
**Budget Bunny** is a personal finance mobile application built with **Android Studio** using **Kotlin**.  
It is designed to help users **efficiently manage their budgets** by tracking expenses across customizable categories.  
Users can create accounts, log in securely, manage spending categories, record expenses with detailed information, and upload receipt images for better expense tracking.

---

## 🎮 Custom Features 
- **Budget Summary Report (PDF Generator)**  
  - Users are able to download a PDF report of their monthly budget summary.
  - The report includes a graph to indicate total expenditure for each category as well as a table detailing each categories’ goals, amount spent and whether the user is within or over their 
    budget. The report also clarifies the total amount spent and how much the user has left to spend based on their budget. 
- **Educational Resources**  
  - Users are able to access a pool of educational resources aligned with budgeting. 
  - The educational space offers a wide range of resources for all users to engage with in order to utilise the application to its fullest potential. 

---

## ✨ Core Features
- **User Authentication**  
  - Create an account and login securely using **email** and **password** (via **Firebase Authentication**).
- **Category Management**  
  - Create spending categories by specifying:
    - Category Name
    - Minimum Spending Goal
    - Maximum Spending Goal
- **Expense Management**  
  - Add expenses by selecting a category and providing:
    - Expense Name
    - Amount
    - Date of Expense
    - Description
    - Receipt Image (Capture using Camera or Select from Gallery)
- **Filtering**  
  - Filter Categories and Expenses based on a **selected time period**.
- **Cloud Integration**  
  - User data is stored in **Firebase Realtime Database** ensuring fast and reliable access across devices.

---

## 🛠️ Design Considerations
- **User-Centric Design**  
  - Simple and intuitive user interface (UI) for easy budgeting.
  - Clear navigation between categories, expenses, and filters.
- **Security & Privacy**  
  - Secure login and data storage using Firebase.
- **Scalability**  
  - Firebase Realtime Database allows scalable real-time data updates.
- **Device Compatibility**  
  - Designed for a wide range of Android devices.
- **Performance**  
  - Efficient image handling and optimized database operations.

---

## 🔗 Utilization of GitHub and GitHub Actions
### GitHub
- Used for:
  - Source code management (commits, branches, pull requests)
  - Collaboration (issues, code reviews)
  - Documentation (README)


### GitHub Actions
- **Continuous Integration (CI):**
  - Automatic project builds on every push or pull request.
- **Automated Testing:**
  - (Optional) Integration of unit tests.


---

## 📦 Technologies Used
- Android Studio (IDE)
- Kotlin (Programming Language)
- Firebase Authentication (Login/Signup)
- Firebase Realtime Database (Data Storage)
- GitHub (Version Control)
- GitHub Actions (CI/CD Automation)

---

## 🚀 Getting Started
To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/VCSTDN2024/prog7313-part3-poe-budgetbunnies-poe.git
2. Open the project in Android Studio.
3. Build and Run the project on an emulator or Android device.
