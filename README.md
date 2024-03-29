# Traffic Signal Simulation

This repository contains code for a GUI application developed using C++ and OpenGL for simulating traffic scenarios. The application renders a graphical representation of a road environment where vehicles move and obey traffic signals.

## Features

- **Vehicle Animation:** The application simulates the movement of cars and buses along the road.
- **Traffic Signals:** Traffic signals are implemented with color changes to control the flow of vehicles.
- **Signal Posts:** Signal posts are displayed along the road to indicate the status of traffic signals.
- **Interactive Elements:** Users can control certain aspects of the simulation, such as starting and stopping traffic flow.

## Technologies Used

- **C++:** The core programming language used for implementing the application logic.
- **OpenGL:** The graphics library used for rendering 2D graphics and animations.
- **GLUT and GLFW:** Libraries used for setting up the OpenGL environment and handling user input.
- **Windows API:** Used for certain platform-specific functionalities.

## Code Structure

The code is organized into different functions responsible for rendering various elements of the simulation environment. Here's an overview of some key functions:

- **`car()`:** Function to draw the car with its body, bumpers, tires, and windows.
- **`brtc_bus()`:** Function to draw a bus with its body, bar, windows, and tires.
- **`road()`:** Function to draw the road with lane markings and divider lines.
- **`zebra_crossing()`:** Function to draw zebra crossings on the road.
- **`sky()`:** Function to draw the sky background.
- **`field()`:** Function to draw the field background.
- **`SignalPost()`:** Function to draw signal posts indicating traffic signals.

## Usage

To run the simulation, compile the code and execute the binary file generated. Users can interact with the simulation through the GUI interface, controlling the flow of traffic and observing different scenarios.

## Contributing

Contributions to improve the simulation or add new features are welcome. Fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
