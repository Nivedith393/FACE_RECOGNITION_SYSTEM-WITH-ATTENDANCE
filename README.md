

# Face Recognition Attendance System

This project is a basic face recognition attendance system built using Python, Streamlit, OpenCV, and face_recognition. The system captures an image using a webcam, recognizes faces, and logs attendance in a CSV file.

## Features

- **Face Recognition**: Identifies faces from the webcam feed using pre-trained encodings.
- **Attendance Logging**: Records attendance with timestamps in a CSV file.
- **Email Notification**: Sends an email with the attendance report.
- **Streamlit Interface**: Provides a simple web interface for capturing images and displaying results.

## Installation

### Prerequisites

- Python 3.7 or higher
- Streamlit
- OpenCV
- face_recognition
- NumPy
- Pillow


## Usage

1. Open the Streamlit application in your browser.
2. Click the "Capture" button to start the webcam and capture an image.
3. The system will recognize faces in the captured image and log attendance in `attendance1.csv`.
4. To send the attendance report via email, ensure the `send_mail` function is configured correctly with your email credentials and recipients.

## Configuration

### Email Notification

To enable email notifications, update the `send_mail` function with your email credentials:

```python
sender = "youremail@example.com"
login = "yourapppassword"
server = smtplib.SMTP("smtp.gmail.com", 587)
server.starttls()
server.login(sender, login)
```



## Contributing

Contributions are welcome! Please fork this repository and submit pull requests for any enhancements or bug fixes.


## Contact

For any inquiries or further information, please contact:
- **Prathik Boppudi** - [prathik3110@gmail.com](mailto:prathik3110@gmail.com)

---
ails.
