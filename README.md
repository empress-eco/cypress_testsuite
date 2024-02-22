<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Project Logo">
  <h1 align="center">Cypress Testsuite: Streamline Your Testing Processes</h1>
  <p align="center">
    A powerful and efficient testing tool for developers, simplifying user interface testing and driving productivity.
    <br />
    <a href="https://empress.eco/"><strong>Explore the Docs »</strong></a>
    <br />
    <a href="https://github.com/empress-eco/cypress_testsuite/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/cypress_testsuite/issues">Request Feature</a>
  </p>
</div>

## About The Project

### Overview
Cypress Testsuite is a comprehensive testing tool designed to streamline user interface testing for developers. It provides a robust and efficient solution to ensure the reliability and performance of your web applications. This tool is a perfect fit for developers and testers who need to perform extensive UI testing in a streamlined manner.

### Key Features
- Comprehensive UI testing: Covers all aspects of your application's user interface.
- Streamlined processes: Makes testing faster and more efficient.
- Robust and reliable: Delivers consistent and dependable results.

### Built With
Cypress Testsuite leverages the power of Cypress, a robust testing framework known for its efficiency and reliability. 

## Technical Stack and Setup Instructions

### Prerequisites
Ensure you have a working instance of your web application running.

### Installation

1. Delete the existing cypress folder within your application directory.

2. Clone this repository in the application directory

```sh
$ git clone https://github.com/empress-eco/cypress_testsuite.git cypress
```

3. Create a cypress.json file within the application directory, an example config for it would go as follows:

```json
{
  "baseUrl": "http://<instance-url>:<port>",
  "projectId": "92odwv",
  "adminPassword": "Empress",
  "viewportHeight": 1080,
  "viewportWidth": 1920
}
```

4. Checkout the [commands.js](support/commands.js) for available commands, and some [example ui tests](integration/) for guidelines.

## Usage
To utilize Cypress Testsuite, follow the installation instructions and refer to the provided commands and test examples. The tool allows you to perform comprehensive UI tests on your web application, ensuring a smooth and efficient testing process.

## Contribution Guidelines
We invite and appreciate community contributions! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

We look forward to your contributions and together enhancing the capabilities of Cypress Testsuite!

## License and Acknowledgements

### License
This project is under the MIT License. Your contributions are also licensed under the MIT License.

### Acknowledgements
Special thanks to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.

We also extend our gratitude to all our contributors who help improve Cypress Testsuite. Your efforts are highly appreciated!
