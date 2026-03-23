#🪪 AI Passport Generator Web

An AI-powered web application built with Flutter Web and a Python backend that enables users to generate passport-size photos instantly — with automatic background removal, formatting, and printable PDF export.

# ✨ Features
🧹 Automatic Background Removal
  1.Upload any portrait image
  2.AI model removes background with high accuracy
  3.No manual editing required
# 📸 Passport Photo Generation
  1.Converts uploaded image into standard passport dimensions
  2.Auto alignment and face positioning
  3.Ready-to-use format
🎨 Background Customization
  Choose between:
    1.White background
    2.Blue background
🔢 Multiple Copies
  1.Select number of photos
  2.Auto-arranged layout for printing
📄 PDF Export
  1.Generates print-ready PDF
  2.Standard page formatting (A4/Letter)
No additional tools needed

#🏗️ Tech Stack
Frontend
  1.Flutter Web
  2.Compiled to HTML / JavaScript
Backend
  1.Python (FastAPI)
  2.AI background removal models (e.g., U²-Net / rembg)
Deployment
  1.Frontend: Vercel
  2.Backend:  Railway

#📁 Project Structure
ai-passport-generator-web/
│
├── assets/                      # Static assets
├── canvaskit/                   # Flutter web rendering engine
├── index.html                   # Entry point
├── main.dart.js                 # Compiled Flutter code
├── flutter.js                   # Flutter runtime
├── flutter_bootstrap.js         # Bootstrap script
├── flutter_service_worker.js    # PWA service worker
├── manifest.json                # PWA configuration
├── version.json
├── favicon.png
└── README.md


⚙️ How It Works
  1.User uploads a portrait image
  2.Image is sent to the Python backend
  3.AI removes the background
  4.User selects:
  5.Background color
  6.Number of copies
  7.App formats image into passport size
  8.Final output is exported as a printable PDF

#🧑‍💻 Installation & Setup

1. Clone the Repository
  git clone https://github.com/your-username/ai-passport-generator-web.git
  cd ai-passport-generator-web
2. Run Frontend (Flutter Web)
   flutter pub get
   flutter run -d chrome
3. Backend Setup (Python)
   cd backend
   python -m venv venv

  # Activate virtual environment
  # Windows:
    venv\Scripts\activate
  # macOS/Linux:
    source venv/bin/activate

  pip install -r requirements.txt
  uvicorn main:app --reload

#🌐 Deployment
Frontend
  Deploy using Vercel
Backend Options
  1.Render
  2.Railway
  3.AWS (EC2 / Lambda)
  4.Google Cloud (Cloud Run)
📌 Use Cases
  1.Passport photo creation at home
  2.Visa application photos
  3.ID card generation
  4.Quick background editing
#🎯 Advantages
⚡ Fast and fully automated
🧠 AI-powered processing
🖨️ Print-ready output
🌐 Works directly in browser
💻 No software installation required

#🔮 Future Improvements
Support for additional background colors
Country-specific passport formats
Mobile application (Flutter Android/iOS)
Advanced AI face alignment
Batch photo processing

#🤝 Contributing

Contributions are welcome!

  1.Fork the repository
  2.Create a feature branch
  3.Commit your changes
  4.Open a pull request
  
