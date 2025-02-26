# React Light Bulb Project

This is a simple React project demonstrating the use of `useState` to toggle a light bulb on and off. The project does not require a build step and runs directly in the browser using Babel.

## Prerequisites

- **Node.js** must be installed on your system. You can download it from [nodejs.org](https://nodejs.org/).
- `npx` (comes with Node.js) to run `live-server`.

## Installation & Running the Project

1. Clone or download this repository.
2. Open a terminal and navigate to the project directory.
3. Run the following command to start a local development server:

   ```sh
   npx live-server
   ```

4. The project will open automatically in your default web browser. If not, navigate to `http://127.0.0.1:8080/` (or the port specified by `live-server`).

## How It Works

- The `App` component manages the light bulb's `on` state.
- The `Bulb` component receives the state and functions as a presentational component.
- Clicking the button toggles the state using `useState`.

## Dependencies

- React (via CDN)
- ReactDOM (via CDN)
- Babel (for JSX transformation in the browser)
- `live-server` (for local development, installed via `npx`)

## License

This project is for educational purposes and is free to use and modify.
