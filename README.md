# Notes App

A simple, responsive, and user-friendly Notes App built with **React** and **Tailwind CSS**. Create and manage your notes easily with a clean interface, while notes are automatically saved in the browser using **localStorage**.

## Features

* Create new notes with a title and detailed content
* Delete notes when they are no longer needed
* Automatically saves notes using browser `localStorage`
* Notes persist even after refreshing or reopening the browser
* Responsive design for different screen sizes
* Clean and modern UI using Tailwind CSS
* Fast and lightweight React application

## Tech Stack

* **React.js** – Frontend library
* **Tailwind CSS** – Styling and responsive design
* **JavaScript (ES6+)** – Application logic
* **LocalStorage** – Persistent browser-based data storage
* **Vite** – Development and build tool

## Project Structure

```text
Notes_App/
│
├── src/
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
│
├── .gitignore
├── .oxlintrc.json
├── index.html
├── package-lock.json
├── package.json
├── README.md
└── vite.config.js
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/harsh-17114/Notes_App.git
```

### 2. Navigate to the project directory

```bash
cd Notes_App
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

The application will be available at the local development URL provided by Vite.

## How It Works

The application uses React's `useState` and `useEffect` hooks to manage notes.

* `useState` manages the note title, details, and notes list.
* `localStorage` stores the notes directly in the browser.
* `useEffect` automatically updates `localStorage` whenever the notes change.
* Notes can be added through the form and removed using the Delete button.

## Main Components

### App.jsx

Contains the main application logic, including:

* Note creation
* Note deletion
* State management
* localStorage integration
* Rendering note cards

### index.css

Contains the Tailwind CSS import:

```css
@import "tailwindcss";
```

### main.jsx

The application entry point that renders the `App` component using React's `createRoot` and `StrictMode`.

## Conclusion

NoteVault is a simple and practical Notes App designed to demonstrate the fundamentals of modern React development. It provides an easy way to create, view, and delete notes while using localStorage for persistent data storage. The project demonstrates React hooks, component-based development, event handling, and responsive UI design with Tailwind CSS. It also provides a strong foundation for future improvements such as editing, searching, authentication, and backend integration.