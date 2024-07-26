# Face Recognition Attendance System

This project is a face recognition-based attendance system using OpenCV, face_recognition library, and Firebase.

## Features
- Register and store student data
- Encode faces from images and store encodings
- Real-time face recognition to mark attendance

## Setup Instructions

1. **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/facerec-attendance.git
    cd facerec-attendance
    ```

2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Firebase Setup**
    - Place your `serviceAccountKey.json` in the project root.
    - Update the `databaseURL` and `storageBucket` in the respective scripts.

4. **Running the Application**
    - Run `addDataToDatabase.py` to add student data.
    - Run `EncodeGenerator.py` to generate face encodings.
    - Run `main.py` to start the attendance system.

## Contributing
Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.
