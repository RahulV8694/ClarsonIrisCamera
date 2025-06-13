🌟 ClarsonIrisCamera



ClarsonIrisCamera is an Android application built using Kotlin that enables users to capture eye images using their mobile camera, extract the iris region using a pre-trained machine learning model, and render the extracted iris in high-definition. This project is part of an ongoing research initiative at Clarkson University focused on biometric authentication.


🚀 Features
📸 Capture High-Resolution Eye Images

🧠 Run ML Model Locally to Extract Iris Region

🖼️ Display Extracted Iris in High-Definition

🔍 Real-Time Processing on Device

💾 Optional Save Functionality for Extracted Iris Data

🛡️ Privacy Focused – No Data Leaves Device

🛠️ Tech Stack
Language: Kotlin

ML Framework: TensorFlow Lite

Model Input: Eye image (captured using Android CameraX)

Output: Cropped, high-definition iris region

IDE: Android Studio

Target Platform: Android 10+

🧠 How It Works
User opens the app and aligns their eye within the camera preview box.

Taps the Capture button.

The app runs a TensorFlow Lite model to detect and isolate the iris region from the image.

The extracted iris is displayed with enhanced resolution using post-processing filters.

📷 Screenshots
Capture Screen	Iris Extraction	High-Definition Iris

📌 Replace the above image URLs with actual screenshots after uploading them to GitHub or another image hosting service.

🔧 Installation
Clone the repository

bash
Copy
Edit
git clone https://github.com/RahulV8694/ClarsonIrisCamera.git
cd ClarsonIrisCamera
Open in Android Studio

Open the folder using Android Studio.

Let Gradle sync complete.

Connect an Android Device or start an emulator.

Run the app from Android Studio.

🧪 Model Information
The model used is a custom TensorFlow Lite model trained to detect the iris region from eye images.

Model is optimized for mobile performance.

Input: RGB image (128x128 or higher)

Output: Bounding box or segmented iris region

✅ Requirements
Android Studio Chipmunk or later

Kotlin 1.8+

TensorFlow Lite library

Android 10 or above

Camera permissions enabled

📂 Folder Structure
css
Copy
Edit

ClarsonIrisCamera/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/clarson/iriscamera/
│   │   │   │   ├── MainActivity.kt
│   │   │   │   ├── CameraUtils.kt
│   │   │   │   └── IrisProcessor.kt
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   └── drawable/
│   │   ├── assets/
│   │   │   └── iris_model.tflite

🔒 Permissions Used
CAMERA: To capture the user's eye image.

WRITE_EXTERNAL_STORAGE (Optional): To save iris data locally.

📚 Future Work
Add liveness detection to prevent spoofing.

Integrate cloud-based comparison API.

Improve low-light iris capture using enhancement filters.

🤝 Contributing
If you'd like to contribute, fork the repository and use a feature branch. Pull requests are warmly welcome.

🧑‍🎓 Author
Rahul Vijaykumar
🔗 LinkedIn
✉️ raulnair013@gmail.com

