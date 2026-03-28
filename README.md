# Face-recognition-controlled-file-and-attendance-system/

## Description

A Python-based system that combines face recognition, passcode security, and file management. Users must verify identity (via face recognition or record matching) to access, create, and view stored personal data.

## Features

* Face recognition-based authentication
* Passcode-protected image upload
* Attendance logging (CSV with timestamp)
* Secure access to user-created text files
* User profile creation (name, age, contact, socioeconomic status)
* File viewer with access control
* Image upload with automatic RGB conversion
* Error handling for invalid inputs and missing files

## Tech Stack

* Python
* OpenCV (`cv2`)
* face_recognition
* Tkinter (GUI file upload)
* CSV handling
* OS & file system utilities

## Installation

```bash
# Install required dependencies
pip install opencv-python
pip install face-recognition
pip install numpy

# Run the program
python main.py
```

## Usage

* Run the program
* Choose from menu:

  * Upload image (secured by passcode)
  * Run face recognition (logs attendance)
  * Create/edit text file (user profile)
  * View files (requires verification)

## Project Structure

* main.py → Core program logic (authentication, file handling, face recognition)
* /attendance_images → Stored user images for recognition
* Attendance.csv → Logs user attendance (name, time)
* *.txt → User-created profile files

## Author

Carl Sebastian E. Barcelona
