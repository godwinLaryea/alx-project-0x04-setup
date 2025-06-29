# Reactify TS: Mastering Advanced TypeScript in React

This project is part of the ALX React curriculum and focuses on building a well-structured, TypeScript-powered React application using Next.js and Tailwind CSS. It demonstrates how to apply shared layouts, imperative routing, reusable components, and organized interface management.

## 🗂 Project Structure

    Framework: Next.js
    Styling: Tailwind CSS
    Language: TypeScript
    Icons: React Icons

## 📁 Key Features

✅ Shared Layouts

    Header, Footer, and Layout components built for reusability.
    Automatically wraps pages with a consistent UI structure.

## ✅ Reusable Components

    Button component supporting custom labels, colors, and actions.

## ✅ Custom Styling

    Integrated Google Font: Montserrat via global Tailwind setup.

## ✅ Imperative Routing

    Used useRouter for dynamic, programmatic navigation across pages.

## ✅ Organized Interfaces

    All TypeScript interfaces are centralized in the interface/index.ts file for maintainability.

## ✅ Custom 404 Page

    Provides a user-friendly and humorous error page when routes are not found.

## 📂 Project Setup

    npx create-next-app@latest --ts alx-project-0x03
    cd alx-project-0x03
    npm install react-icons
    npm install
    npm run dev

## 📁 Directory Structure

    alx-project-0x03/
    ├── components/
    │   ├── common/
    │   │   └── Button.tsx
    │   └── layouts/
    │       ├── Header.tsx
    │       ├── Footer.tsx
    │       └── Layout.tsx
    ├── interface/
    │   └── index.ts
    ├── pages/
    │   ├── index.tsx
    │   └── 404.tsx
    ├── styles/
    │   └── globals.css

## 🧪 How to Test

#### Run the project:

    npm run dev

    Open your browser to http://localhost:3000

#### Try the navigation buttons to test imperative routing.

    Navigate to a non-existent route like /unknown to see the custom 404 page.
