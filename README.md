🪪 AI Passport Generator Web

An AI-powered web application built with Flutter (Web) and a Python backend that allows users to:

🧹 Remove image backgrounds instantly

📸 Generate passport-size photos automatically

🎨 Change background color (white or blue)

🔢 Select number of copies

📄 Export final photos as a printable PDF

🚀 Features

Automatic Background Removal

Upload any portrait image

AI removes background seamlessly

Passport Photo Generator

Converts image into standard passport format

Proper alignment and cropping handled automatically

Background Customization

Choose between:

White background

Blue background

Multiple Copies

Select how many passport photos you want

Automatically arranged for printing

PDF Export

Generates a ready-to-print PDF

No manual editing required

🏗️ Tech Stack
Frontend

Flutter Web

HTML / JavaScript (generated build)

Backend

Python (FastAPI or similar)

AI background removal models

Deployment

Vercel (Frontend)

Python API (separate service)

📁 Project Structure
ai-passport-generator-web/
│
├── assets/                  # Static assets
├── canvaskit/              # Flutter web rendering engine
├── index.html              # Entry point
├── main.dart.js            # Compiled Flutter code
├── flutter.js              # Flutter runtime
├── flutter_bootstrap.js    # Bootstrap script
├── flutter_service_worker.js
├── manifest.json           # PWA config
├── version.json
├── favicon.png
└── README.md
⚙️ How It Works

User uploads an image

Image is sent to the Python backend

AI removes the background

User selects:

Background color

Number of copies

App formats images into passport size

Final output is generated as a PDF

🧑‍💻 Installation & Setup
1. Clone the repository
git clone https://github.com/your-username/ai-passport-generator-web.git
cd ai-passport-generator-web
2. Run Flutter Web (Development)
flutter run -d chrome
3. Backend Setup (Python)
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
🌐 Deployment

Frontend deployed on Vercel

Backend can be deployed on:

Render

Railway

AWS / GCP

📌 Use Cases

Passport photo creation at home

Visa photo preparation

ID card photos

Quick background editing

🎯 Advantages

No manual editing needed

Fast and automated

Print-ready output

Works directly in browser

🔮 Future Improvements

Support for more background colors

Country-specific passport formats

Mobile app version

AI face alignment enhancements

🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.
