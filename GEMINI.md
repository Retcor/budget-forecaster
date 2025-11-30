# Project: Budget Forecaster

## Project Overview

This project is a client-side budget and debt projection tool. It's a single-page web application that allows users to input their income, bills, and debts to visualize their financial forecast on a calendar. The application is built entirely with HTML, vanilla JavaScript, and is styled using the Tailwind CSS framework. It also uses Font Awesome for icons. All data is stored locally in the user's browser using `localStorage`, meaning there is no backend server component.

## Building and Running

There are no build steps required to run this application.

### Running the Application

To run the budget forecaster, simply open the `budget-forecaster.html` file in any modern web browser.

## Development Conventions

- **Single-File Structure:** The entire application—HTML, CSS, and JavaScript—is contained within the `budget-forecaster.html` file.
- **Styling:** The project uses [Tailwind CSS](https://tailwindcss.com/) for styling, included via a CDN. Some custom inline styles are also present for minor aesthetic tweaks.
- **JavaScript:** All logic is written in vanilla JavaScript and is located in a `<script>` tag at the end of the `<body>`.
- **State Management:** The application state (income, bills, debts) is managed in a simple JavaScript object (`appState`) and is persisted to the browser's `localStorage`.
- **Templates:** HTML `<template>` tags are used to dynamically generate new rows for bills and debts in the UI.
