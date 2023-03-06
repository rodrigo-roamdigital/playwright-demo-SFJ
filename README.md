# playwright-demo-SFJ

This repository provides a starting point for a Playwright project that can be used for demonstration purposes. Playwright is a Node.js library that allows you to automate web browsers and create automated tests for web applications.

This project includes a basic setup with the necessary dependencies and configuration files to run a sample test using Playwright.

## Before you start

Dont forget to run: `yarn install` and `npx playwright install`

## Getting Started

To use this repository, you should have Node.js and Yarn installed on your machine. Once you have those installed, follow these steps:

## Clone this repository onto your local machine.

- Navigate to the project directory in your terminal or command prompt.
- Run `yarn` to install the necessary dependencies.
- Run `yarn test` to run the sample test.
- If everything is set up correctly, you should see a browser window open and the test will run automatically.

## Run tests

Run all tests in parallel (it uses headless browser config and unlimited workers): `yarn test`

Run all tests in serial mode: `yarn test:serial`

Run all tests using debug mode: `yarn test:debug`

Run and open HTML report locally: `yarn report`

## Configuration
The configuration file for Playwright is located in `playwright.config.ts`. This file includes settings for the browser, context, and other options.

## Learn More
To learn more about Playwright, check out the official documentation or the Playwright GitHub repository.

Happy testing!
