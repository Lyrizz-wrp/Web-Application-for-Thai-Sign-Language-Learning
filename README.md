# 🖐 Thai Sign Language Learning Web App

A web application that helps users learn **Thai Sign Language (TSL)** by typing Thai sentences and getting matching sign language videos.  
This app uses **PyThaiNLP** to intelligently segment Thai words and match them with a video database.

---

## 📌 Project Goals

- Promote inclusive education and communication for deaf and hearing-impaired individuals
- Provide an accessible tool to learn and practice Thai Sign Language
- Support text-based input in Thai and match relevant signs using NLP

---

## 🔍 Features

- 🧠 **Thai Word Segmentation** using PyThaiNLP
- 🎥 **Video Display** for each word or phrase in Thai Sign Language
- 🔎 **Search and Learn** Thai signs from any input sentence
- 📱 **Responsive UI** for both desktop and mobile
- 🌐 Frontend-Backend Integration (Optional with Flask/FastAPI)

---

## 🛠 Tech Stack

| Layer       | Technology             |
|-------------|------------------------|
| Frontend    | HTML, CSS, JavaScript  |
| Backend     | Python (Flask / FastAPI) |
| NLP         | [PyThaiNLP](https://github.com/PyThaiNLP/pythainlp) |
| Media       | MP4 videos for each sign |
| Data        | JSON-based sign database |

---

## 🚀 Getting Started

### ⚙️ Prerequisites

- Python 3.8+
- Node.js (optional, for frontend server)
- pip

### 📥 Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/thai-sign-language-webapp.git
cd thai-sign-language-webapp

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install Python dependencies
pip install -r requirements.txt

# Run the Flask backend
python backend/server.py
