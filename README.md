# IPC Frontend

This project is a frontend application for simulating and visualizing Inter-Process Communication (IPC) mechanisms such as Pipes, Queues, and Memory Management.

## Project Structure

- `public/` - Static assets and the main HTML file
- `src/` - Source code
  - `components/` - React components for UI panels and managers
  - `services/` - State management and simulation logic
  - `styles/` - CSS files for styling
- `index.html` - Entry HTML file
- `vite.config.js` - Vite configuration
- `package.json` - Project dependencies and scripts

## Getting Started

### Prerequisites
- Node.js (v16 or higher recommended)
- npm or yarn

### Installation

1. Navigate to the `frontend` directory:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```

### Running the Development Server

```sh
npm run dev
# or
yarn dev
```

The app will be available at `http://localhost:5173` by default.

### Building for Production

```sh
npm run build
# or
yarn build
```

### Preview Production Build

```sh
npm run preview
# or
yarn preview
```

## Features
- Visualizes IPC mechanisms: Pipes, Queues, Memory Management
- Interactive dashboard and analysis panels
- Notification center for simulation events

## License

This project is licensed under the MIT License.
