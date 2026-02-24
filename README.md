# Github Explorer

Github Explorer is a ReactJS application developed during the Rocketseat
Ignite Bootcamp.\
The application allows users to search and explore public GitHub
repositories using the GitHub API.

------------------------------------------------------------------------

## 🚀 Technologies Used

This project was built using the following technologies:

-   ReactJS -- UI library for building component-based interfaces
-   TypeScript -- Static typing for JavaScript
-   Webpack -- Module bundler for development and production builds
-   Babel -- JavaScript transpiler for modern syntax compatibility
-   SCSS -- CSS preprocessor for styling
-   HTML5 & CSS3
-   GitHub REST API -- For fetching public repository data

------------------------------------------------------------------------

## 📦 Project Setup

### Prerequisites

Make sure you have the following installed:

-   Node.js (version 14 or higher recommended)
-   npm or yarn

------------------------------------------------------------------------

## 🔧 Installation

Clone the repository:

``` bash
git clone https://github.com/threis/github-explorer-rockeatseat-ignite.git
```

Navigate into the project directory:

``` bash
cd github-explorer-rockeatseat-ignite
```

Install dependencies:

Using npm:

``` bash
npm install
```

Using yarn:

``` bash
yarn
```

------------------------------------------------------------------------

## ▶️ Running the Project

To start the development server:

Using npm:

``` bash
npm start
```

Using yarn:

``` bash
yarn start
```

The application should open automatically in your browser at:

http://localhost:3000

If it does not open automatically, check the terminal output for the
correct URL.

------------------------------------------------------------------------

## 🏗️ Production Build

To generate a production-ready build:

Using npm:

``` bash
npm run build
```

Using yarn:

``` bash
yarn build
```

The optimized files will be generated inside the `dist/` folder.

------------------------------------------------------------------------

## 🔐 Environment Variables

This project does not require any mandatory environment variables to run
locally.

Since it consumes the public GitHub API, authentication is not required
for basic usage.

However, if you decide to use authenticated GitHub API requests (to
avoid rate limits), you may create a `.env` file and add:

REACT_APP_GITHUB_TOKEN=your_github_token_here

Then restart the development server.

------------------------------------------------------------------------

## 📚 Project Purpose

This project was developed as part of the Rocketseat Ignite ReactJS
track to reinforce concepts such as:

-   Component-based architecture
-   State management with hooks
-   API consumption
-   Webpack configuration
-   TypeScript integration

------------------------------------------------------------------------

## 📄 License

This project is for educational purposes.
