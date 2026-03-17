# RiskRadar: Radar for At-Risk Students

A comprehensive full-stack application designed to predict and monitor student dropout rates and academic success using machine learning.

## 📋 Project Overview

RiskRadar is an intelligent system that leverages machine learning to identify at-risk students and predict their academic performance. The application provides both a powerful backend API and an intuitive frontend interface for educators and institutions to monitor student success rates.

## 🏗️ Project Structure

```
RiskRadar/
├── backend/                    # FastAPI backend
│   ├── main.py                # Main application entry point
│   ├── requirements.txt        # Python dependencies
│   ├── data.csv               # Training data
│   ├── README.md              # Backend documentation
│   └── predict_student_dropout_and_academic_success.ipynb  # Model notebook
│
└── frontend/                   # React frontend
    ├── src/
    │   ├── components/        # Reusable React components
    │   ├── pages/            # Page components
    │   ├── redux/            # Redux state management
    │   ├── assets/           # Static assets
    │   └── App.jsx
    ├── public/               # Public assets
    ├── package.json          # Node dependencies
    └── README.md             # Frontend documentation
```

## 🚀 Quick Start

### Prerequisites
- Python 3.8+ (for backend)
- Node.js 14+ & npm/yarn (for frontend)
- Git

### Backend Setup

1. **Navigate to backend directory:**
   ```bash
   cd backend
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the server:**
   ```bash
   python main.py
   ```
   The API will be available at `http://localhost:8000`

### Frontend Setup

1. **Navigate to frontend directory:**
   ```bash
   cd frontend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server:**
   ```bash
   npm start
   # or
   yarn start
   ```
   The application will open at `http://localhost:3000`

## 🌟 Features

- **Student Prediction Model**: Accurate ML model for predicting student dropout and success rates
- **Interactive Dashboard**: User-friendly interface to view analytics and predictions
- **Authentication**: Secure login and registration system
- **Student Form**: Comprehensive form to input student data for predictions
- **Real-time Analysis**: Dynamic calculations and insights
- **Responsive Design**: Mobile and desktop compatible interface

## 💻 Technology Stack

### Backend
- **FastAPI**: Modern, fast web framework for building APIs
- **Python**: Core programming language
- **Scikit-learn/TensorFlow**: Machine learning algorithms
- **Pandas**: Data manipulation and analysis

### Frontend
- **React**: JavaScript library for building user interfaces
- **Redux**: State management
- **Tailwind CSS**: Utility-first CSS framework
- **React Router**: Client-side routing

## 📊 API Endpoints

The backend provides the following key endpoints:

- `POST /predict` - Submit student data for prediction
- `GET /students` - Retrieve student data
- `POST /login` - User authentication
- `POST /register` - User registration

For detailed API documentation, refer to [backend/README.md](./backend/README.md)

## 🔐 Environment Variables

Create a `.env` file in the frontend directory (see `.env.example`):
```
REACT_APP_API_URL=http://localhost:8000
```

## 📝 Model Performance

The machine learning model is trained on historical student data and provides predictions for:
- Student dropout probability
- Academic success likelihood
- Risk assessment score

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the MIT License.

## 👥 Contact

For questions or support, please contact the development team or open an issue in the repository.

## 🔗 Repository

- **GitHub**: https://github.com/Dakshh-Agarwal/RiskRadar-radar-for-at-risk-students
- **Owner**: Dakshh-Agarwal

---

**Last Updated**: March 17, 2026
