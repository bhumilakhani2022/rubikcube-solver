# Rubik's Cube Web Application

A feature-rich, React-based web application for Rubik's Cube enthusiasts. This project provides tools for solving, practicing, and interacting with a virtual Rubik's Cube.

## Features

- **Interactive 3D/2D Cube**: A fully interactive representation of a Rubik's Cube.
- **Manual Solver**: Input your cube's state manually to get a solution sequence.
- **Practice Mode**: Time your solves and track your progress.
- **Pattern Library**: Apply various interesting patterns to the cube.
- **Statistics Tracking**: View your solve count, best time, and average time.
- **Move Recording**: Record, replay, and undo move sequences on the interactive cube.

## Setup and Installation

### 1. Prerequisites

- Node.js (v18 or higher)
- npm

### 2. Install Dependencies

Clone the repository and install the required packages:

```bash
npm install
```

### 3. Run the Application

Start the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or the next available port).

## How to Use

The application is divided into several tabs:

- **Home**: The main dashboard with a view of the cube and basic controls like Scramble and Reset.
- **Interactive**: A sandbox mode where you can freely manipulate the cube, apply quick moves, and record your move sequences.
- **Solver**: Manually input the colors of your physical cube's faces to receive a solution string.
- **Practice**: A dedicated mode for speed-solving. It includes a timer that starts and stops automatically.
- **Patterns**: A library of classic cube patterns that you can apply to the virtual cube.
- **Stats**: A dashboard displaying your solving statistics, including total solves, best time, and average time.

## Project Structure

```
src/
├── App.tsx                 # Main application component and router
├── Cube.ts                 # Core cube logic (state, moves)
├── cfopSolver.ts           # Logic for the CFOP solving method
├── components/
│   ├── CubeInput.tsx       # The manual solver interface
│   ├── CubeView.tsx        # 2D and 3D cube visualization
│   └── InteractiveCube.tsx # The interactive cube and pattern library
└── ...
```

## Development

### Available Scripts

- `npm run dev`: Starts the Vite development server.
- `npm run build`: Compiles the TypeScript code and builds the project for production.
- `npm run lint`: Lints the codebase using ESLint.
- `npm run preview`: Serves the production build locally for preview.
- `npm test`: Runs tests using `ts-node`.

### Contributing

1.  Fork the repository.
2.  Create a new feature branch.
3.  Make your changes.
4.  Submit a pull request.

## License

This project is licensed under the MIT License.
