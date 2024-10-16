
# Three.js + Vite + TypeScript Starter

This project is a boilerplate for creating 3D applications with **Three.js**, **Vite**, and **TypeScript**. It also includes **ESLint** for linting and **Prettier** for code formatting.

## Project Setup

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or higher)

### Install Dependencies

After cloning the repository, install the necessary dependencies:

```bash
npm install
```

### Development Server

To start the development server with hot-reload, run:

```bash
npm run dev
```

This will start Vite and serve the project at `http://localhost:5173`.

### Linting & Formatting

This project is configured with **ESLint** and **Prettier** to ensure code quality and consistency.

- **Lint** your code with:

  ```bash
  npm run lint
  ```

- **Format** your code with Prettier:

  ```bash
  npm run format
  ```

### Build for Production

To build the project for production:

```bash
npm run build
```

The production build will be located in the `dist` directory.

## Project Structure

```bash
.
├── public               # Static assets (favicon, etc.)
├── src
│   ├── app              # Main application files
│   │   └── main.ts      # Entry point of the app
│   └── style.css        # Optional CSS for styling
├── .eslintrc.json       # ESLint configuration file
├── .prettierrc          # Prettier configuration file
├── index.html           # Main HTML file
├── package.json         # Node.js dependencies and scripts
├── tsconfig.json        # TypeScript configuration file
├── vite.config.ts       # Vite configuration file
└── README.md            # Project readme
```

### Key Technologies

- **Vite**: Build tool for fast, modern web development with hot-reload.
- **Three.js**: A lightweight, cross-browser, general-purpose 3D library.
- **TypeScript**: Static type checking to reduce errors and improve code quality.
- **ESLint**: JavaScript/TypeScript linter to maintain code quality.
- **Prettier**: Code formatter to enforce consistent style.

### Customize Configuration

See [Vite Configuration Reference](https://vitejs.dev/config/) for more details.

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```

2. Navigate into the project directory:

   ```bash
   cd your-repo-name
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open `http://localhost:5173` in your browser to see the app in action.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.