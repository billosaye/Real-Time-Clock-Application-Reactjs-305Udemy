# Real-Time Clock Application

This is a simple React application that displays the current time and allows you to update it manually or automatically every second. 

## Features

1. **Display Current Time**: Shows the current time in the `<h1>` element.
2. **Update Time Manually**: You can click the "Get Time" button to refresh the time.
3. **Automatic Time Update**: The time updates automatically every second.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd your-repo-name
   ```

3. **Install Dependencies**

   Ensure you have Node.js and npm installed. Then run:

   ```bash
   npm install
   ```

4. **Start the Development Server**

   ```bash
   npm start
   ```

   This will start the development server and open the application in your default browser.

## Usage

1. **Automatic Time Update**: The time displayed in the `<h1>` element will automatically update every second.
2. **Manual Time Update**: Click the "Get Time" button to manually update the time.

## Code Overview

### `App.js`

- **Imports**: Imports React and `useState` from React.
- **State**: Uses `useState` to manage the current time.
- **updateTime Function**: Updates the time state to the current time.
- **setInterval**: Sets an interval to automatically call `updateTime` every second.
- **Rendering**: Displays the current time and a button to manually update the time.

### `index.js`

- **Imports**: Imports React, ReactDOM, the main `App` component, and the CSS file.
- **Rendering**: Renders the `App` component into the root element of the HTML.

## Challenges

1. **Manual Time Update**: Ensure the `<h1>` updates when the "Get Time" button is pressed.
2. **Automatic Time Update**: Implement `setInterval` to update the time every second.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

If you have suggestions or improvements, feel free to open an issue or submit a pull request.

---

Feel free to modify this README to fit any additional details or instructions specific to your project.
