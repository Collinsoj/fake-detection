# fake-detection

🛡️ AI-Powered Fake Social Media Account Detection System
An AI-based web application that detects fake social media accounts using a multimodal learning approach — combining Natural Language Processing (NLP) and Computer Vision (CV) to analyze both profile bios and profile pictures.

📂 Project Structure
csharp
Copy
Edit
├── app/                    # Flask backend
│   ├── static/             # CSS, images
│   ├── templates/          # HTML files (e.g., index.html)
│   ├── model/              # Trained ML/DL models (BERT, CNN, etc.)
│   └── app.py              # Main Flask app
├── dataset/                # Collected text/image data
├── requirements.txt        # Python dependencies
├── README.md               # You’re here
└── .gitignore
🚀 Features
🤖 Detects fake social media accounts using AI

📝 Uses BERT for textual bio analysis

🖼️ Uses ResNet or ViT for profile image analysis

🔀 Combines results via cross-modal attention fusion

📊 Outputs prediction result: Real or Fake

🧪 Evaluated with accuracy, precision, recall & F1-score

⚙️ Tech Stack
Frontend: HTML5, CSS3, JavaScript, jQuery

Backend: Python 3, Flask

AI Models: BERT, ResNet50, Vision Transformers

Libraries: PyTorch, Hugging Face Transformers, OpenCV, Pillow

Development Tools: Google Colab, Jupyter, VS Code

🛠️ Installation & Setup
Clone the Repository

bash
Copy
Edit
git clone https://github.com/collinsoj/fake-detecton.git
cd fake-account-detector
Create & Activate a Virtual Environment

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Flask App

bash
Copy
Edit
python app.py
Access the App
Visit: http://127.0.0.1:5000 in your browser.

📥 How to Use
Enter an Instagram username in the input field.

The system will:

Fetch and analyze profile bio and image.

Process them using pretrained AI models.

Return a prediction: Fake or Genuine.

📈 Model Performance
Model Type	Accuracy	F1-Score
BERT (NLP)	81.3%	0.79
ResNet (CV)	76.5%	0.74
Hybrid Model	89.6%	0.88

🔐 Ethical Considerations
All datasets used were public or anonymized.

Results are interpretable using attention maps.

This project is for research & academic use only — not for public deployment without safeguards.

🧪 Future Improvements
Real-time detection pipeline

Multilingual NLP capabilities

Integration with Twitter/Instagram APIs

Enhanced datasets with more diversity

👨‍💻 Author
Odejimi Oluwaseyi Collins
Computer Science, Caleb University
Supervised by Prof. M.K. Aregbesola

📄 License
This project is licensed for academic use. For commercial use, please contact the author.
