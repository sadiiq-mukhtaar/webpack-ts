# Webpack + ts 

This is a starter project for Redux using TypeScript and Webpack. The project is structured to compile TypeScript files from the `dist-ts/` directory and output the compiled JavaScript files into the `src/` directory. Webpack is used to bundle the application and serve it using `webpack-dev-server`.

# Project Setup

This project involves compiling TypeScript files and starting a Webpack development server to serve the application.

## Directory Structure
- ├── dist-ts/ # Contains TypeScript source files
  │ └── index.ts # Main TypeScript entry point
- ├── src/ # Contains compiled JavaScript files
  │ └── index.js # Compiled JavaScript output
- ├── webpack.config.js # Webpack configuration file
- ├── package.json # Project dependencies and scripts
- ├── tsconfig.json # TypeScript configuration file
- └── README.md # Project documentation



## Steps to Run the Application

1. **Compile the TypeScript files**:
   - The TypeScript files will be compiled automatically when you start the development server.

2. **Start the Webpack development server**:
   - Run the following command to start the server:
     ```bash
     npm start
     ```

3. **Access the Application**:
   - Open your browser and navigate to `http://localhost:8080` (or the port specified in your Webpack configuration).

## Configuration Files

### `tsconfig.json`
This file configures the TypeScript compiler. Key settings include:

- **rootDir**: Specifies the source directory (`dist-ts/`).
- **outDir**: Specifies the output directory (`src/`).
- **target**: Specifies the ECMAScript version for the compiled JavaScript.

### `webpack.config.js`
This file configures Webpack. Key settings include:

- **entry**: Specifies the entry point (`src/index.js`).
- **output**: Specifies the output bundle location.
- **devServer**: Configures the development server.

### `package.json`
This file defines project dependencies and scripts. Key scripts include:

- **start**: Compiles TypeScript and starts the Webpack development server.

## Dependencies

- **TypeScript**: For compiling TypeScript code.
- **Webpack**: For bundling the application.
- **Webpack Dev Server**: For serving the application during development.

## Author

This project was created by **[Sadiiq Mukhtaar](https://github.com/sadiiq-mukhtaar)**.
