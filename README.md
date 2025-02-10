# Education with AI 🎓

![Python-3 8+-blue](https://github.com/user-attachments/assets/83b181ff-9424-431c-89cb-7879b6be0724)
![Flask-2 0+-green](https://github.com/user-attachments/assets/30b3e76e-dcf6-4ce4-9703-404322acf7f3)

An innovative peer-to-peer learning platform connecting students from grades 5-9 with mentors from grades 10-12, powered by Flask and OpenAI's GPT technology.

## 🌟 Features
### For Students
- Create personalized learning session requests
- Access comprehensive study materials across multiple subjects
- Connect with experienced peer mentors
- Join scheduled online conferences
- Take AI-powered adaptive tests

### For Mentors
- Review and accept session requests
- Schedule and manage learning sessions
- Share conference links directly through the platform
- Contribute to the learning community


## Educational Resources
### 📚 Comprehensive materials available for:
- ICT
- English
- Mathematics
- Physics
- Chemistry


## 🛠️ Technology Stack
- Backend: Flask (Python)
- Database: MySQL (with SQLAlchemy ORM)
- Authentication: Flask-Login
- AI Integration: OpenAI GPT
- Security: Flask-WTF, CSRF Protection
- Email: Flask-Mail

## 🚀 Installation
#### 1. Clone the repository
    git clone https://github.com/Ge5pi/education_with_ai.git
    cd education_with_ai
#### 2. Set up virtual environment
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
#### 3. Install dependencies
    pip install -r requirements.txt
#### 4. Set up environment variables
    export API_KEY='your_openai_api_key'
    # Add other necessary environment variables
#### 5. Run the application
    python main.py

## 💡 Key Components
- User Management
- Secure registration and login system
- Role-based access control (student/mentor)
- Password hashing for security
