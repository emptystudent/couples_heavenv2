#couples_heavenv2

# Poetry Bot Application

## Overview
This is a Streamlit-based web application that allows users to upload an image and then generates poetry based on that image using three different language models (LLMs). The application uses the JamAI SDK to interact with the LLM models and aggregates the generated outputs to provide a rich poetic experience.

## Features
- **Upload Image**: Users can upload an image in various formats (jpg, jpeg, png).
- **Generative Poetry**: The uploaded image is used to inspire three different LLMs to generate poetry.
- **Aggregated Outputs**: The application aggregates the generated poems from the LLMs and displays them in a clear, aesthetically pleasing format.

## Requirements
- Python 3.10 or later
- The following Python packages (specified in `requirements.txt`):
  - streamlit
  - jamaibase
  - Pillow
  - base64



## How It Works
- **Image Upload**: The user uploads an image file through the Streamlit UI.
- **Image Processing**: The uploaded image is converted to JPEG format and then uploaded to JamAI.
- **LLM Generations**: The image serves as the input for three different LLMs. Each LLM generates a unique piece of poetry based on the content or visual aspects of the image.
- **Display**: The generated poetry from each LLM is displayed in an easy-to-read card format, with distinct styling for each model's output to facilitate comparison.

## Technologies Used
- **Streamlit**: For building the web interface.
- **JamAI SDK**: For interacting with LLM models to generate the poetry.
- **Pillow**: For handling image conversion.
- **Python**: The core language used for backend logic and scripting.

## Notes
- The LLM models used are integrated using the JamAI SDK, and they provide unique poetic interpretations based on the image content.
- The background color of the UI and text styling have been designed for better readability in a dark-themed environment.

## Contributing
If you would like to contribute to the project, feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License.

## Acknowledgments
- Thanks to the JamAI team for providing access to their SDK and LLM models.

