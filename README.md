
# Nxt Watch

Nxt Watch is a YouTube-like video streaming platform built with React. It allows users to explore various video categories, switch between dark and light themes, and perform authenticated actions using JWT tokens. The application is modeled to provide a seamless and user-friendly video browsing experience.

---

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features

- **User Authentication**: Secure login functionality with JWT token-based authentication.
- **Dark/Light Theme**: Toggle between dark and light modes for a personalized user experience.
- **Trending Videos**: Browse videos that are currently trending.
- **Gaming Videos**: Explore gaming-related videos in a dedicated section.
- **Saved Videos**: Save videos to your personalized list and view them later.
- **Video Details**: View individual video details along with related recommendations.
- **Responsive Design**: Works seamlessly across desktop, tablet, and mobile devices.

---

## Demo

[Live Demo](#) (Add your live link here)

---

## Installation

### Prerequisites

Ensure you have the following installed on your system:
- **Node.js** (v16 or later recommended)
- **npm** (Package Manager)

### Steps to Install

1. Clone the repository:

   ```bash
   git clone https://github.com/Waghraj1699/nxtWatch.git
   cd nxtWatch
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open your browser and navigate to:

   ```
   http://localhost:3000
   ```

---

## Usage

### Login
1. Use the login page to access the application. Provide valid credentials to log in.
2. Once logged in, your session is managed via a JWT token.

### Explore Videos
- Navigate through Trending, Gaming, and Saved Video sections using the sidebar menu.
- Click on any video thumbnail to view its details.

### Save Videos
- Save any video to your "Saved Videos" list for easy access later.

### Toggle Theme
- Switch between dark and light modes using the theme toggle button in the header.

---

## Technologies Used

- **React.js**: For building the user interface.
- **React Router**: For managing navigation and routing.
- **JWT**: For secure authentication and session management.
- **CRACO**: To override Create React App configurations.
- **CSS/SCSS**: For styling components.
- **npm**: As the package manager for faster dependency management.

---

## Environment Variables

Create a `.env` file in the root directory and configure the following variables:

```plaintext
REACT_APP_BASE_URL=https://your-api-url.com
REACT_APP_JWT_SECRET=your-jwt-secret
```

---

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature/fix.
3. Commit your changes.
4. Push the branch to your forked repository.
5. Create a Pull Request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Contact

If you have any questions or suggestions, feel free to contact:

- **Name**: Waghraj
- **GitHub**: [Waghraj1699](https://github.com/Waghraj1699)
- **Email**: (waghrajpatil1699@gmail.com)

---

Happy coding!
