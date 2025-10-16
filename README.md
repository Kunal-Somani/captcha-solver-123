# Captcha Solver UI

A simple, responsive web application designed to display captcha images and allow users to input their solutions. This tool focuses on the frontend user interface for interacting with captcha challenges, supporting dynamic image loading from URLs and providing a basic interaction for solving.

## Features

*   **Dynamic Image Loading**: Load captcha images from any specified URL via a query parameter (e.g., `?url=https://example.com/captcha.png`).
*   **Default Captcha Display**: Falls back to a local `sample.png` image if no URL is provided, with a simulated validation.
*   **Responsive Design**: Built with Tailwind CSS for a modern and adaptable user interface across various screen sizes.
*   **User Input and Submission**: Provides an input field for users to type their perceived captcha text and a submit button.
*   **Basic Feedback**: Offers immediate feedback on submission, including a simulated "correct" or "incorrect" check for the default sample image.

## Usage

1.  **Open the Application**: Simply open the `index.html` file in your web browser.
    *   By default, it will display the `sample.png` image.
2.  **Load Custom Captcha**: To load a captcha image from a specific URL, append the `?url=` query parameter to your browser's address bar.
    *   **Example**: `file:///path/to/your/index.html?url=https://www.example.com/path/to/your/image.png`
    *   *Note*: Due to browser security restrictions (CORS), loading images from certain external domains directly might be blocked. For local testing, ensure the image URL allows cross-origin requests or host your `index.html` on a web server.
3.  **Solve the Captcha**:
    *   Carefully observe the text in the displayed image.
    *   Enter your interpretation into the text input field.
    *   Click the "Submit" button or press `Enter`.
4.  **Receive Feedback**: The application will provide a message indicating the submission status. For the default `sample.png`, it checks if your input matches "ADORS" (case-insensitive). For external URLs, it acknowledges your submission as actual validation would occur on a backend server.

## Technologies Used

*   **HTML5**: For the semantic structure of the web page.
*   **Tailwind CSS**: A utility-first CSS framework for rapid and responsive UI development.
*   **JavaScript**: For handling dynamic image loading, user interactions, and providing feedback.

## Setup

No special setup is required. Just download the `index.html`, `README.md`, `LICENSE`, and `sample.png` files and keep them in the same directory. Open `index.html` in your browser.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.