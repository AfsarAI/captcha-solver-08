# CAPTCHA Solver Web Application

This project provides a simple, single-page web application to solve a static CAPTCHA challenge. It features a dark-themed, responsive user interface built with Tailwind CSS, where users can input text from an image and verify their input.

## Features

- **Dark Theme:** A sleek, modern dark background with light text for comfortable viewing.
- **Responsive Design:** Adapts to various screen sizes, from mobile to desktop.
- **CAPTCHA Display:** Clearly presents a static CAPTCHA image.
- **User Input:** An input field for users to type the CAPTCHA text.
- **Verification Logic:** A 'Verify' button to check the user's input against the correct CAPTCHA string.
- **Feedback System:** Displays clear success or failure messages after verification.
- **Interactive Button:** A circular 'Verify' button with a subtle hover animation.

## Technologies Used

- **HTML5:** For the page structure.
- **Tailwind CSS:** For utility-first styling and responsive design.
- **JavaScript (Vanilla):** For client-side logic and interaction.

## Setup and Running Instructions

To run this application, you only need a web browser. Follow these steps:

1.  **Save the files:**
    *   Save the HTML content provided as `index.html`.
    *   Ensure the CAPTCHA image (named `image.png` as per context) is in the same directory as `index.html`.
2.  **Open in Browser:** Double-click `index.html` in your file explorer, or open it with your preferred web browser.

The application will load, displaying the CAPTCHA challenge. You can then interact with the input field and the 'Verify' button.

## Usage

1.  Observe the text displayed within the CAPTCHA image.
2.  Type the exact text (case-insensitive) into the input field.
3.  Click the circular 'Verify' button.
4.  A message will appear below the button indicating whether your verification was successful or failed.

**Note:** The correct CAPTCHA text for this specific implementation is `V4XBG` (case-insensitive).

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.
