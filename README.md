# Webcam Filter Application

## Project Overview
This is a web application that lets you use your computer's webcam to take photos and videos with cool filters, just like popular social media apps. You can access it through your web browser without installing any special software.

## Tools and Technologies Used

### 1. Java 8
- **What it is**: The main programming language used to write the application
- **Why we use it**: 
  - It's reliable and works on any computer
  - Has great tools for handling webcam and image processing
  - Many developers know it, making it easy to find help

### 2. Spring Boot 2.7.0
- **What it is**: A framework that makes it easy to create web applications
- **Why we use it**:
  - Makes the application start quickly
  - Handles all the complicated web server setup
  - Provides ready-to-use features for web development
  - Makes the code organized and easy to maintain

### 3. Maven
- **What it is**: A tool that helps manage the project and its parts
- **Why we use it**:
  - Automatically downloads all the needed parts (libraries) for the project
  - Makes sure everyone working on the project has the same setup
  - Makes it easy to build and run the application
  - Keeps track of all the project's requirements

### 4. Key Parts of the Application

#### a) Spring Boot Starter Web
- **What it is**: The basic web functionality package
- **Why we use it**:
  - Handles web requests and responses
  - Manages the web server
  - Makes the application accessible through a web browser

#### b) Thymeleaf
- **What it is**: A tool for creating web pages
- **Why we use it**:
  - Makes it easy to create the user interface
  - Helps show the webcam feed on the webpage
  - Makes the pages look good and work smoothly

#### c) Lombok
- **What it is**: A tool that reduces repetitive code
- **Why we use it**:
  - Makes the code shorter and cleaner
  - Reduces the chance of errors
  - Makes the code easier to read and maintain

## How to Use the Application

### What You Need
1. A computer with:
   - Java 8 or newer installed
   - A webcam
   - A modern web browser (Chrome, Firefox, or Edge)

### How to Start
1. Download the project
2. Open a command prompt in the project folder
3. Run the command: `mvn spring-boot:run`
4. Open your web browser and go to: `http://localhost:8080`

## What the Application Does

### Main Features
1. **Webcam Access**
   - Connects to your computer's webcam
   - Shows the live video feed in your browser
   - Works with most standard webcams

2. **Filter Application**
   - Applies different effects to your webcam feed
   - Changes can be seen in real-time
   - Easy to switch between different filters

3. **User Interface**
   - Simple and easy to use
   - Works on both desktop and mobile browsers
   - Clear buttons and controls

## Technical Details (For Developers)

### Project Structure
```
webcam-filter/
├── src/
│   ├── main/
│   │   ├── java/        # Program code
│   │   └── resources/   # Web pages and settings
│   └── test/            # Test files
└── pom.xml              # Project configuration
```

### Performance
- Starts up in about 1.3 seconds
- Works smoothly with most webcams
- Handles video processing efficiently

### Security
- Asks for permission before using your webcam
- Keeps all processing on your computer
- Doesn't send your video to any servers

## Future Improvements
1. More filter options
2. Better mobile support
3. Ability to save filtered photos
4. More customization options
5. Better performance on slower computers

## Need Help?
If you have any problems:
1. Check if your webcam is working
2. Make sure you have Java installed
3. Try using a different web browser
4. Check the error messages in the command prompt

## Contact
[Your contact information] 
