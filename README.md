# RoboFriends

Welcome to **RoboFriends**, a fun React application that displays a list of robot friends fetched from a public API. Users can search through the list of robots by name. This project is built using React, showcasing components, state management, and API integration.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [Performance Monitoring](#performance-monitoring)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- Fetch and display a list of robots from a public API.
- Search functionality to filter robots by name.
- Responsive and styled cards for each robot.
- Scrollable container for a large number of robots.
- Custom font styling for a unique look.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/RealFace-24/robofriends.git
   ```
2. Navigate to the project directory:
   ```bash
   cd robofriends
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
   The app will be available at `http://localhost:3000`.

## Usage
- Once the app is running, you will see a list of robot friends.
- Use the search box to filter the robots by typing their names.
- The list is scrollable, and each robot card includes an image, name, and email.

## Project Structure
- `public/`: Contains static assets like the favicon and index.html.
- `src/`: Contains the source code.
  - `components/`: React components like `Card`, `CardList`, `SearchBox`, and `Scroll`.
  - `containers/`: Contains the main `App.js` component.
  - `App.css`: Styles for the application, including a custom font.
  - `index.css`: Global styles for the body, including a gradient background.
  - `index.js`: Entry point for the React application.
  - `reportWebVitals.js`: Utility for measuring web performance metrics.
  - `setupTests.js`: Configuration for Jest testing with jest-dom.
  - `robots.js`: Local array of robot data (used as a fallback or example).
- `package.json`: Project configuration and dependencies.
- `package-lock.json`: Lock file for dependency versions.

## Technologies Used
- **React**: For building the user interface.
- **React Scripts**: For development and build tools.
- **Tachyons**: CSS framework for styling.
- **JSONPlaceholder API**: Public API for fetching robot data.
- **Jest & Testing Library**: For unit testing.
- **Web Vitals**: For performance monitoring.

## Testing
This project includes a basic testing setup with Jest and `@testing-library/jest-dom`. To run tests, use:
```bash
npm test
```
You can extend the tests by adding more test cases in the `src` directory.

## Performance Monitoring
The `reportWebVitals.js` file allows you to measure performance metrics (e.g., CLS, FID, LCP, FCP, TTFB). To log results to the console, modify `index.js` to include:
```javascript
reportWebVitals(console.log);
```
For analytics, you can send the data to an endpoint—see [CRA-vitals](https://bit.ly/CRA-vitals) for more details.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit: `git commit -m "Add feature-name"`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contact
For questions or feedback, please reach out to [RealFace-24](https://github.com/RealFace-24) on GitHub.