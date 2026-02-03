Project Title: Crop Recommendation System

Overview: The Crop Recommendation System is a machine learning-based web application that predicts the optimal crop to grow based on environmental inputs. It’s built using Python with a Flask backend, a Random Forest model for predictions, and HTML/CSS for a user-friendly interface.

Workflow Outline : Project Setup Model Training and Saving Building the Flask App Frontend Development Testing Locally

Step 1: Project Setup -> Install Python and Libraries: Set up necessary libraries: pip install pandas scikit-learn flask joblib -> Create a Virtual Environment: python -m venv venv ,Activate the virtual environment: venv\Scripts\activate

Step 2: Model Training and Saving -> Train the Model and Save the trained model as crop_model.pkl within a model/ folder.

step 3: Building the Flask App -> Folder Structure: Structure your project directory as follows: CropRecommendation/ ├── app.py ├── model/ │ └── crop_model.pkl ├── static/ │ └── style.css └── templates/ └── index.html

Step 4: Frontend Development

Step 5: Testing Locally --- Run the Flask App: Start the Flask application from the command line: python app.py Access the App: Open your web browser and go to http://127.0.0.1:5000 to access the app. Check Functionality: Enter sample values for the inputs and verify that the app predicts a crop based on the input data.

Screen Shorts :