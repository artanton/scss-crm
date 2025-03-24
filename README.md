# CAT CRM

## Overview  

**CAT CRM** is a customer relationship management (CRM) system built using **Vite** and **SCSS**. It provides a responsive and efficient user interface for managing customer interactions, tasks, and business processes. This project is optimized for performance and fast development using modern frontend tools.

## Table of Contents  
- [Features](#features)  
- [Installation](#installation)  
- [Project Structure](#project-structure)  
- [Running the Application](#running-the-application)  

## Features  
✔ Built with **Vite** for fast development and optimized builds.  
✔ Uses **SCSS** for modular and maintainable styling.  
✔ Responsive design that adapts to different screen sizes.  
✔ Organized project structure for easy scalability.  
✔ Public folder for assets and font management.  
✔ Git-ignored `node_modules` to keep the repository clean.  

## Installation  

To set up the project locally, follow these steps:  

1. Ensure **Node.js LTS version** is installed.  
   - [Download and install Node.js](https://nodejs.org/en/) if necessary.  
2. Install project dependencies:  
   ```sh
   npm install
   ```
3. Start the development server:  
   ```sh
   npm run dev
   ```
4. Open your browser and navigate to:  
   [http://localhost:5173](http://localhost:5173)  
   - The page will reload automatically whenever you save changes.  
5. To build the final CSS output, run:  
   ```sh
   npx vite build --watch
   ```
   - The processed files will be available in the `dist/assets` folder.  

## Project Structure  

```
/
├── demo                    # Folder for documentation and demo files
├── dist                    # Compiled and built project output
├── node_modules            # Node.js dependencies (ignored in Git)
├── public                  # Public assets (favicon, fonts, etc.)
├── src                     # Source code
│   ├── fonts               # Fonts used in the project
│   ├── img                 # Images and icons
│   ├── js                  # JavaScript files and business logic
│   ├── scss                # SCSS stylesheets
├── .gitignore              # Files and folders ignored by Git
├── index.html              # Main HTML file
├── LICENSE                 # License file
├── package-lock.json       # Locked dependency versions
├── package.json            # Project metadata and dependencies
├── postcss.config.cjs      # Configuration for PostCSS
├── README.md               # This documentation file
├── vite.config.js          # Vite bundler configuration
```

## Running the Application  

To start the project in development mode:  

1. Run the following command in the terminal:  
   ```sh
   npm run dev
   ```
2. Open **[http://localhost:5173](http://localhost:5173)** in your browser.  

To generate a production build:  

```sh
npm run build
```
- The optimized project files will be located in the `dist/` directory.  

For watching SCSS compilation:  

```sh
npx vite build --watch
```

Enjoy building with **CAT CRM**! 🚀
