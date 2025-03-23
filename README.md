# crime_prediction_by_ai

fastapi-auth/
├── main.py                 # Main FastAPI app setup
├── auth.py                 # Authentication routes
├── model.py                # Prediction and home routes
├── config.py               # Centralized templates config
├── db.py                   # Database setup (SQLAlchemy)
├── models.py               # SQLAlchemy User model
├── templates/
│   ├── auth/
│   │   ├── login.html      # Login page
│   │   ├── register.html   # Registration page
│   │   ├── home.html       # Home page with form and back button
│   ├── result.html         # (Optional) Result page if used
│   ├── error.html          # Error page
├── static/
│   ├── auth/
│   │   ├── home.css        # CSS for home.html
├── decision_tree.h5        # Trained Decision Tree model
├── random_forest.h5        # Trained Random Forest model
├── svm.h5                  # Trained SVM model
├── preprocessor.pkl        # Preprocessor for model input
├── .gitignore              # Git ignore file
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies

