# WiFi Device Management System

A Java console application that demonstrates core object-oriented programming principles through a simulated WiFi device management system. Users can connect devices, view device info, update firmware, and install apps through a menu-driven interface.

## How to Run

1. Clone the repository
2. Open the project in your preferred Java IDE (Eclipse, IntelliJ, etc.)
3. Run `WifiDeviceDemo.java`

## Features

- Connect a Router and Smartphone to WiFi
- Display device information
- Update router firmware
- Install apps on the smartphone

## Project Structure

| File | Description |
|------|-------------|
| `WifiDeviceDemo.java` | Entry point; handles the menu loop and user input |
| `WifiDevice.java` | Abstract parent class with shared device attributes and an abstract `connectToWifi()` method |
| `Router.java` | Extends `WifiDevice`; adds firmware version and update functionality |
| `Smartphone.java` | Extends `WifiDevice`; adds operating system and app installation functionality |

## Concepts Used

- Abstract classes and methods
- Inheritance and method overriding (`@Override`)
- Encapsulation with getters and setters
- Polymorphism through subclass-specific behavior
- Menu-driven user interface with Scanner

## Author

Mariam — [@mariamlikes2code](https://github.com/mariamlikes2code)
