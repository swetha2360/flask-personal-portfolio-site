# Personal Site – Flask Project 🌐✨

This is a simple personal website built using Python and the Flask framework. It includes basic routing and uses HTML and CSS for the frontend design.

## 📌 What It Does

- Renders a homepage with an introduction and navigation.
- Includes an About page with personal information.
- Demonstrates how to use templates and static files in Flask.

## 🛠 Technologies Used

- Python
- Flask
- HTML
- CSS


flask-personal-site/
│
├── static/
│   └── style.css                # CSS file for styling
│
├── templates/
│   ├── index.html               # Home page template
│   └── about.html               # About page template
│
├── app.py                       # Main Flask application
├── requirements.txt             # Project dependencies
└── README.md                    # Project documentation


## 🚀 How to Run the Project

```bash
git clone https://github.com/your-username/flask-personal-site.git
cd flask-personal-site
python -m venv venv
source venv/bin/activate   # On Windows use venv\Scripts\activate
pip install -r requirements.txt
python app.py
