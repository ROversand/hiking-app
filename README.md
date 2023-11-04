# Hiking App Project Documentation

Welcome to the documentation for the Hiking App project. This application is designed for hiking enthusiasts to share their adventures and discover new trails through the experiences of others. Users can post details about their hikes, rate them, and interact with the hiking community by liking the hikes posted by others.

## Table of Contents

- [Technologies](#technologies)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Technologies

This application is built with a modern tech stack to ensure a seamless user experience and easy maintainability:

- **[Next.js](https://nextjs.org/)**: A React framework for production.
- **[TypeScript](https://www.typescriptlang.org/)**: A typed superset of JavaScript that compiles to plain JavaScript.
- **[Firebase](https://firebase.google.com/)**: A platform developed by Google for creating mobile and web applications.
- **[npm](https://www.npmjs.com/)**: A package manager for JavaScript and the world's largest software registry.
- **[TailwindCSS](https://tailwindcss.com/)**: A utility-first CSS framework for rapid UI development.
- **[DaisyUI](https://daisyui.com/)**: A plugin for TailwindCSS that provides component classes.

## Project Structure

The application's codebase is organized as follows:

- `components/`: Contains all reusable UI components.
- `context/`: Holds the authentication functionality for user sessions.
- `firebase/`: Includes all logic related to the Firebase connection and services.
- `hooks/`: Features hooks for fetching user data, posts, and images.
- `pages/`: Comprises all the different pages of the web application.
- `public/`: Stores static files like images and icons used in the application.
- `styles/`: Contains global styles that are not related to the DaisyUI plugin.

## Getting Started

To set up the project locally on your machine, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/hiking-app.git
   cd hiking-app
    ```
2. **Install Dependencies:**

   ```bash
   npm install
   ```
3. **Set Up Firebase:**

   - Create a new project in the [Firebase Console](https://console.firebase.google.com/).
   - Enable the **Authentication** and **Firestore** services.
   - Create a web app and copy the configuration object.
   - Create a `.env.local` file in the root directory of the project and add the following environment variables:

     ```bash
     NEXT_PUBLIC_FIREBASE_API_KEY=YOUR_API_KEY
     NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=YOUR_AUTH_DOMAIN
     NEXT_PUBLIC_FIREBASE_PROJECT_ID=YOUR_PROJECT_ID
     NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=YOUR_STORAGE_BUCKET
     NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=YOUR_MESSAGING_SENDER_ID
     NEXT_PUBLIC_FIREBASE_APP_ID=YOUR_APP_ID
     NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID=YOUR_MEASUREMENT_ID
     ```
4. **Run the Application:**

   ```bash
   npm run dev
   ```
5. **Open the Application:**

   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Contributing
Contributions are always welcome! Please open an issue or submit a pull request with your ideas.
Please make sure to update tests as appropriate.

## License
Distributed under the MIT License. See `LICENSE` for more information.