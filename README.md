# React TimePlanner

**React TimePlanner** is a React.js application built to demonstrate how to handle complex **form validations** for time-based inputs in a real-world scenario. This app enables barbers (or similar professionals) to configure their **weekly working schedule** including shop hours, working periods, and break times—on a day-by-day basis.

## 🚀 Project Overview

This project focuses on solving real-life scheduling problems using **React Hook Form** and **Yup**, making it ideal for developers looking to learn advanced form validation techniques in React.

Users can input:

- Shop Open/Close times
- Working Start/End times
- Break Start/End times

All input is validated with custom logic and schema validation, and the resulting schedule is displayed in the console for review.

## ✨ Features

-✅ **Daily Schedule Configuration**: Define shop, working, and break hours for each day of the week.

- ✅ **Advanced Validation with Yup**: Custom validation rules ensure time sequences are logical (e.g., working hours fall within shop hours, breaks within working hours).

- ✅ **Real-Time Data Logging**: Submitted schedule data is printed to the browser console for further use.

- ✅ **Clean & Responsive UI**: Built using **Material UI v5** and **Tailwind CSS** for a modern and responsive design.

- ✅ **Phone Number Validation**: International phone input with validation via `google-libphonenumber`.

## 🛠️ Tech Stack

- **React.js** – Core UI framework
- **Material UI v5** – UI component library
- **Tailwind CSS** – Utility-first CSS framework
- **React Hook Form** – Powerful and performant form handling
- **Yup** – Schema validation for complex rules
- **google-libphonenumber** – International phone number validation
- **react-international-phone** – Stylish and functional phone input component

## 📦 Requirements

- **Node.js ≥ 20.9.0**

## 🧪 Getting Started

Follow these steps to clone and run the project locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/amandeeptherockstar/react-time-planner.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd react-time-planner
   ```

3. **Install the dependencies:**

   ```bash
   npm install
   ```

4. **Start the development server:**

   ```bash
   npm run dev
   ```

5. **Open your browser and go to:**

   ```
   http://localhost:3000
   ```

## ✅ Use Cases

- Schedule management for barbers, freelancers, or service professionals
- A template for validating complex nested forms with time ranges
- Learning resource for developers using React Hook Form with Yup

## Conclusion

**React TimePlanner** serves as a practical guide to managing and validating complex time-based inputs in a React application. It integrates modern libraries and best practices, providing a clean UI and robust logic suitable for real-world use.
