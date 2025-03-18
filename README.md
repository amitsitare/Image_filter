# Image Filtering Web Application

## Overview
This is a simple web application built using Flask and PIL (Pillow) that allows users to upload an image and apply various filters such as rotation, blur, contrast adjustment, cropping, grayscale conversion, and text overlay. The processed image can then be downloaded.

## Features
- Upload an image
- Rotate the image by a specified angle
- Apply Gaussian blur with a chosen radius
- Adjust contrast using a contrast factor
- Crop the image using given coordinates
- Convert the image to grayscale
- Overlay custom text on the image
- View the edited image
- Download the processed image

## Technologies Used
- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS (Bootstrap)
- **Image Processing**: PIL (Pillow)

## Installation and Setup
### Prerequisites
Ensure you have Python installed (preferably Python 3.x) and install the required dependencies:

```bash
pip install flask pillow
```

### Running the Application
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/image-filtering-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd image-filtering-app
   ```
3. Run the Flask application:
   ```bash
   python app.py
   ```
4. Open your web browser and go to `http://127.0.0.1:5000/`.

## File Structure
```
image-filtering-app/
│-- static/        # CSS and JavaScript files (if any)
│-- templates/     # HTML templates
│   │-- index6.html  # Upload page
│   │-- edit6.html   # Processed image display page
│-- app.py         # Flask application
│-- README.md      # Project documentation
```

## Usage
1. Upload an image via the provided form.
2. Select the filters and parameters you wish to apply.
3. Click "Submit" to apply the changes.
4. View the edited image and download it if needed.

## Contributing
Feel free to fork this repository and submit pull requests with improvements or additional features!

## License
This project is licensed under the MIT License.

