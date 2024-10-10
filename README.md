# Kanye Quote Generator

This simple GUI application retrieves random quotes from Kanye West using the Kanye REST API and displays them in a visually appealing interface created with Tkinter.

## Features

- Fetches random quotes from the Kanye REST API.
- Displays the quote in a graphical user interface (GUI).
- Includes custom background and button images.

## Setup Instructions

### 1. Clone the GitHub Repository

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/Selorme/kanye_quotes_app.git
```

Navigate into the project directory:

```bash
cd kanye-quote-generator
```

### 2. Install Dependencies

Make sure you have Python 3.x installed. You can check your version using:

```bash
python --version
```

You will need the `requests` library to run this script. You can install it using pip:

```bash
pip install requests
```

### 3. Prepare Assets

This application requires two image files for the GUI:

- `background.png`: A background image for the canvas.
- `kanye.png`: An image for the button.

Make sure these images are in the same directory as your script.

### 4. Run the Script

Run the application using Python:

```bash
python main.py
```

When the application starts, click the button to fetch a new quote from Kanye West and display it in the application window.

## Code Explanation

1. **Imports**: The script imports necessary libraries for creating the GUI and making API requests.
2. **Quote Fetching**: The `get_quote()` function makes a GET request to the Kanye REST API, retrieves a random quote, and updates the text in the GUI.
3. **Tkinter Window**: The application creates a Tkinter window with a canvas for displaying the background image and the quote.
4. **Button**: A button is provided to fetch new quotes when clicked.

## License

This project is licensed under the MIT License.