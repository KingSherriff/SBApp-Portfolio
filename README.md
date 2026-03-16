# Small Business Product Management App – Flutter Portfolio Project

A fully functional product management application built with Flutter, designed for small business owners to track inventory efficiently. This repository serves as a portfolio showcase – the source code is private but can be shared upon request.

## ✨ Features
- **Product Catalog** – List, search, and filter products
- **Invoice & Receipt Generation** – *In development* (coming soon)
- **CRUD Operations** – Add, edit, delete products with validation
- **Inventory Tracking** – Real-time stock levels with low-stock indicators
- **Persistent Data** – Firebase Firestore (with local emulator for development)
- **Clean Architecture** – Transitioning fully to MVVM architecture with Riverpod for state management
- **CI/CD** – Automated builds and linting via GitHub Actions
- **Dockerized Development** – Firebase emulator suite running in Docker for consistent setup

## 📈 Future Improvements
- **Invoice/Receipt generation** – Currently implementing PDF generation and emailing receipts to customers.
- Add unit and widget tests
- Barcode scanning for quick product entry
- Multi-user support with roles (admin, cashier, employee)

## 🛠️ Tech Stack
- **Flutter** – Cross-platform UI
- **Riverpod** – State management
- **Firebase** – Firestore, Authentication (emulator for local dev)
- **Docker** – Containerized emulator environment
- **GitHub Actions** – Continuous integration

## 🏗️ Architecture Overview
The app follows the **MVVM** pattern with Riverpod providers acting as the ViewModel layer. Data is fetched from a repository that abstracts the Firebase/Firestore implementation. This separation ensures testability and maintainability.

## 📦 Running Locally (for reviewers)
If you’d like to inspect the source code, please [contact me](mailto:sherriff.kadiri@outlook.com) to request access to the private repository. The project includes:

- Complete Flutter source code
- Docker setup for Firebase emulators
- GitHub Actions workflow
- Step-by-step setup instructions

## 🚀 CI/CD
The private repository uses GitHub Actions to run `flutter analyze` and `flutter test` on every push. The workflow is configured to ensure code quality before merging.

## 📈 Future Improvements
- Add unit and widget tests
- Implement barcode scanning
- Deploy to production Firebase with security rules
- Add multi-user support

## 📬 Contact
- **Email**: ysherriff.kadiri@outlook.com
- **LinkedIn**: [linkedin.com/in/sherriff-kadiri/](https://www.linkedin.com/in/sherriff-kadiri/)
- **GitHub**: [https://github.com/KingSherriff](https://github.com/KingSherriff)

---

*This project is part of my portfolio. The source code is available upon request for recruitment purposes.*
