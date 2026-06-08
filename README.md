# API Automation Testing Project

This project aims to automate API testing for the "Automation Exercise" project, ensuring high-quality performance and quick bug detection.

## 🛠 Tools & Technologies
* **Postman**: For designing and developing test scenarios.
* **Newman**: For running tests via the command line.
* **GitHub Actions**: For automating continuous testing (CI/CD Pipeline).
* **Git**: For version control.

## 📁 Project Structure
- `My Collection.postman_collection.json`: The collection file containing all test cases.
- `Local.postman_environment.json`: The environment variables file for connection settings.
- `.github/workflows/`: Contains the pipeline file to automate tests on every code push.

## 🚀 How to Run Tests Locally
To run tests on your local machine, ensure `Newman` is installed, then run the following command in your terminal:

```bash
newman run "My Collection.postman_collection.json" -e "Local.postman_environment.json" -r cli,htmlextra

## Project Demo
You can watch the project demonstration video here: [Watch Demo](https://drive.google.com/file/d/1c6-BrXzETdSyUEjftCWrETmnOoDKABmg/view?usp=drivesdk)


