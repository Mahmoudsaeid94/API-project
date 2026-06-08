# Notes API Automation Project

This project contains automated API tests for the **Notes API** (https://practice.expandtesting.com/notes/api/). It covers end-to-end testing for user authentication and CRUD operations for notes.

## 🛠 Tech Stack
* **Postman**: Used for designing and executing API requests.
* **Newman**: Command-line tool to run the Postman collection.
* **GitHub Actions**: Automated CI/CD pipeline to trigger tests on every push.
* **Git**: Version control.

## 📁 Project Structure
- `My Collection.postman_collection.json`: Contains all test scenarios (Health, User, Notes).
- `Local.postman_environment.json`: Environment variables (URL, Auth Token, etc.).
- `.github/workflows/`: Automated test workflow configuration.

## 🚀 How to Run Locally
Ensure you have **Newman** installed, then run the following command in the project folder:

```bash
newman run "My Collection.postman_collection.json" -e "Local.postman_environment.json" -r cli,htmlextra

## Project Demo
You can watch the project demonstration video here: [Watch Demo](https://drive.google.com/file/d/1c6-BrXzETdSyUEjftCWrETmnOoDKABmg/view?usp=drivesdk)


