# Victor Rodriguez Portfolio Project

This project is a web page developed with React.js that shows my portfolio and includes descriptions of my projects and interests about my training in Software Engineering.

## Dependencies
- Husky
Husky is a tool that allows you to define hooks in the git lifecycle, automating tasks such as testing and linting on specific events such as pre-commit or pre-push. In this React project, Husky is configured to run ESLint before each commit, thus ensuring that the code adheres to the defined style rules and maintains high quality.

- ESLint
ESLint is a linting tool for JavaScript that identifies and reports problematic patterns in code, maintaining coding style consistency and detecting common errors. In this personal portfolio, ESLint is used to ensure that JavaScript code complies with best coding practices and standards, thereby improving the readability of the code and making it easier to maintain.

- React v18.2.0
This project uses version 18.2.0 of React, specifically selected for its stability and compatibility with existing libraries and dependencies. It is recommended to maintain this version to ensure a consistent and predictable development environment, thus minimizing incompatibility risks and ensuring an optimal user experience in the personal portfolio.

## Installation of dependencies

Prerequisite: node v20.11.1 previously pnpm

1. Install with the command
```
pnpm install
```
2. Install husky
```
pnpm husky install
```
3. Install eslint
```
pnpm install eslint --save-dev
```
Additionally, you can install an extension for your text editor.

## Run

Run the project
```
pnpm run start
```


## Other commands

To start linting
```
pnpm run lint
```

## How to run the tests
- Test cases
```
pnpm run test
```

## License

The project is under the ©MIT License.

