# Captcha Solver Demo

This project provides a simple, client-side demonstration of a Captcha solver interface built with HTML, Tailwind CSS, and JavaScript. It allows users to input solutions for displayed Captcha images, defaulting to a local sample image or loading one from a provided URL.

## Features

- **Responsive Design:** Utilizes Tailwind CSS for a mobile-first, responsive user interface.
- **Dynamic Image Loading:** Loads Captcha images from a `url` query parameter or defaults to `sample.png`.
- **Client-Side Validation:** A basic JavaScript logic checks the user's input against a hardcoded solution for known images (e.g., `sample.png`).
- **Interactive Feedback:** Provides immediate feedback to the user on whether their solution is correct or incorrect.

## How to Use

1.  **Clone the Repository (or save files locally):**
    Save `index.html`, `README.md`, and `LICENSE` in the same directory. Ensure `sample.png` is also in the same directory.

2.  **Open `index.html`:**
    Simply open the `index.html` file in your web browser.

3.  **Default Captcha:**
    By default, the page will display the `sample.png` image. The expected solution for this image is `ADQR3`.

4.  **Load Custom Captcha (via URL):**
    You can specify a custom Captcha image URL by appending a `?url=` query parameter to the `index.html` path.
    Example:
    `file:///path/to/your/project/index.html?url=https://example.com/another-captcha.png`

    *Note: For demonstration purposes, only `sample.png` has a hardcoded solution (`ADQR3`). If you provide a different image URL, the solver will indicate it's unable to solve it, as a real captcha solver would require a backend processing or a more advanced client-side AI model.* 

5.  **Enter Solution and Submit:**
    Type your solution into the input field and click the "Submit" button or press Enter.

## Technologies Used

-   **HTML5:** Structure of the web page.
-   **Tailwind CSS:** For styling and responsiveness.
-   **JavaScript (ES6):** For dynamic behavior and client-side logic.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.
