# Vehicle Builder

A command-line application built using TypeScript that allows users to create, select, and interact with various types of vehicles. The application provides options for cars, trucks, and motorbikes, with unique properties and actions for each vehicle type.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Available Commands](#available-commands)
- [Walkthrough Video](#walkthrough-video)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Description

The Vehicle Builder is a TypeScript command-line application that allows users to create new vehicles (cars, trucks, and motorbikes) or select existing ones to perform a variety of actions. This application demonstrates the use of Object-Oriented Programming (OOP) in TypeScript, including class inheritance and interfaces. The primary aim is to extend the codebase to introduce new vehicle types and actions, providing a comprehensive understanding of working with TypeScript classes.

## Features

- **Create and Manage Vehicles**: Create cars, trucks, and motorbikes, each with unique properties.
- **Select Existing Vehicles**: Choose from the list of created vehicles to perform actions.
- **Perform Actions**: Execute specific actions based on the vehicle type, such as towing for trucks and wheelies for motorbikes.
- **Interactive CLI**: Uses the `Inquirer` package to collect user input and provide a user-friendly command-line interface.

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/vehicle-builder.git
    ```

2. Navigate to the project directory:

    ```bash
    cd vehicle-builder
    ```

3. Install the necessary dependencies:

    ```bash
    npm install
    ```

4. Compile the TypeScript files:

    ```bash
    npm run build
    ```

## Usage

To start the application, run the following command:

```bash
npm start
```

### Available Commands

- **Create New Vehicle**: Allows the user to create a new car, truck, or motorbike.
- **Select Existing Vehicle**: Select a previously created vehicle from the list.
- **Perform Actions**: Execute specific actions for the selected vehicle.
- **Exit**: Ends the session and exits the application.

## Walkthrough Video

To demonstrate the full functionality of the application, a walkthrough video has been created. The video covers:

- How to invoke the application using `npm start`.
- How to create a car, truck, and motorbike.
- Entering details for each vehicle type.
- Performing actions such as towing (for trucks) and wheelies (for motorbikes).

[Watch the Walkthrough Video](#) <!-- Replace this link with the actual video link -->

## Technologies Used

- **TypeScript**: For building a strongly-typed command-line application.
- **Node.js**: To run the application.
- **Inquirer**: For handling command-line prompts and user input.

## Project Structure
- **`classes`**: Contains the classes for `Car`, `Motorbike`, `Truck`, `Vehicle`, and `Cli`.
- **`interfaces`**: Includes TypeScript interfaces (`AbleToTow`, `Driveable`) for defining the structure of vehicle behaviors.
- **`index.ts`**: Entry point for the application.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
    ```bash
    git checkout -b feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature-name
    ```
5. Open a pull request to the main branch.

## License

This project is licensed under the MIT License.
