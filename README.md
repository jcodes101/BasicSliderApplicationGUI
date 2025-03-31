# BasicSlideApplicationGUI

## Overview
BasicSlideApplicationGUI is a simple JavaFX-based graphical user interface (GUI) application featuring a sliding sidebar menu. It is implemented using JavaFX, FXML, and Maven for dependency management.

## Features
- Animated sliding menu controlled by clicking "Menu" and "MenuClose" labels.
- Smooth transition effects using JavaFX `TranslateTransition`.
- Draggable window for a modern, undecorated UI.
- Exit button functionality to close the application.
- Styled UI elements using CSS.

## Technologies Used
- Java 17
- JavaFX 17.0.6
- Maven for dependency management
- SceneBuilder for UI design
- JFoenix for enhanced UI components
- JUnit 5 for testing

## Installation and Setup
### Prerequisites
Ensure you have the following installed:
- Java Development Kit (JDK) 17 or later
- Maven
- JavaFX SDK 17.0.6

### Clone the Repository
```sh
git clone https://github.com/your-repo/BasicSlideApplicationGUI.git
cd BasicSlideApplicationGUI
```

### Build and Run with Maven
1. Compile the project:
   ```sh
   mvn clean install
   ```
2. Run the application:
   ```sh
   mvn javafx:run
   ```

## Project Structure
```
BasicSlideApplicationGUI/
│-- src/main/java/sample/
│   │-- Main.java
│   │-- MainController.java
│-- src/main/resources/sample/
│   │-- sample.fxml
│   │-- styles.css
│-- pom.xml
│-- README.md
```

## Usage
- Click the **Menu** label to open the sidebar.
- Click the **MenuClose** label to close the sidebar.
- Click the **Exit** button to close the application.
- Drag the window to reposition it.

## Dependencies
```xml
<dependencies>
    <dependency>
        <groupId>org.openjfx</groupId>
        <artifactId>javafx-controls</artifactId>
        <version>17.0.6</version>
    </dependency>
    <dependency>
        <groupId>org.openjfx</groupId>
        <artifactId>javafx-fxml</artifactId>
        <version>17.0.6</version>
    </dependency>
    <dependency>
        <groupId>com.jfoenix</groupId>
        <artifactId>jfoenix</artifactId>
        <version>9.0.10</version>
        <scope>system</scope>
        <systemPath>${project.basedir}/libs/jfoenix-9.0.10.jar</systemPath>
    </dependency>
</dependencies>
```

## Notes
- The project was designed using **SceneBuilder** for easier FXML-based UI design.
- Ensure your **JavaFX SDK** version matches the project's requirements.
- Update `pom.xml` configurations if necessary.

## License
This project is licensed under the MIT License.

## Author
Developed by [Jcodes101]

