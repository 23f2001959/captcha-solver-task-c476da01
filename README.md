# Captcha Solver Task

## Summary:

The Captcha Solver Task project aims to develop a robust captcha solver that can recognize and solve text-based captchas from images using basic OCR techniques. The system should accept base64 encoded image inputs, accurately extract the captcha text, and return the decoded answer as plain text. In addition, error handling for unclear or noisy images will be implemented using Python with commonly used OCR libraries like Tesseract.

## Setup:

1. Install Python on your system if you haven't already.
2. Clone the repository to your local machine.
3. Install the required dependencies by running `pip install -r requirements.txt`.

## Usage:

To use the Captcha Solver Task, follow these steps:

1. Encode the captcha image to base64 format.
2. Use the provided Python script to submit the base64 encoded image.
3. Receive the decoded answer as plain text.

Example usage:
```
$ python solve_captcha.py <encoded_image>
```

## Code Explanation:

- `solve_captcha.py`: Python script to solve captchas using OCR techniques.
- `requirements.txt`: List of required dependencies for the project.
- `images/`: Placeholder folder for captcha images.

## License:

This project is licensed under the MIT License.