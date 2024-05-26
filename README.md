# Development Environment Setup with dotenv and TypeScript

This repository provides a template for setting up a development environment using dotenv for environment variables management and TypeScript for type-safe JavaScript development.

## Features

- **dotenv**: Load environment variables from a `.env` file into `process.env`.
- **TypeScript**: Strongly typed JavaScript for better code quality and maintainability.
- **Node.js**: JavaScript runtime environment.
- **ts-node**: TypeScript execution environment for Node.js, allowing you to run TypeScript code directly.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Node.js**: Install [Node.js](https://nodejs.org/) (v20.x or later).
- **pnpm**: Node package manager, which comes with Node.js.


## Getting Started

1. **Clone the repository**:
    ```sh
    git clone git@github.com:roy-aaissk/test-ts-env.git
    cd test-ts-env
    ```

2. **Install dependencies**:
    ```sh
    pnpm install
    pnpm install dotenv -D
    pnpm install -D typescript ts-node @types/node
    ```

3. **Set up environment variables**:
    - Create a `.env` file in the root of your project.
    - Add your environment-specific variables to the `.env` file. For example:
      ```env
      MESSAGE=''
      ```

4. **Compile TypeScript**:
    ```sh
    pnpm run build
    ```

5. **Run the project**:
    ```sh
    pnpm run dev
    ```


