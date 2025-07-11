# virtual-doctor
**Description**
Virtual Doctor is an AI-powered web application that predicts diseases based on user-reported symptoms and provides personalized medical advice. Designed to improve healthcare accessibility—especially in areas with limited resources—it offers quick, reliable guidance without the need for accounts or subscriptions.

**Key Features**

Symptom-Based Disease Prediction: Uses a Random Forest Classifier to predict diseases based on selected symptoms.

Personalized Recommendations: Delivers tailored advice for medications, diet plans, workout routines, and safety precautions.

Hospital Locator: Helps users find nearby hospitals via Google Maps integration.

Medical Assistant Chatbot: Provides instant health-related guidance and clarifications.

User-Friendly Interface: Supports multi-symptom selection (up to 4 symptoms) via dropdowns and checkboxes.

Additional Pages: Includes About, Contact, Developer, Blog (for recent health news), Feedback, and Emergency sections.

** Tech Stack**
Backend: Flask (Python)

Frontend: HTML, CSS, JavaScript

Machine Learning: Random Forest Classifier (132 estimators, trained on preprocessed medical dataset)

Maps Integration: Google Maps for hospital locator

** How It Works**
Homepage: User chooses "Start Diagnosis" or "Hospital Locator."

Hospital Locator: Displays nearby hospitals on Google Maps.

Start Diagnosis: User selects up to 4 symptoms via dropdowns and checkboxes.

Prediction: Random Forest Classifier analyzes input to predict the disease.

Results Page: Displays predicted disease along with detailed description, recommended medications, diet plans, workouts, and precautions.

Chatbot: Offers interactive medical assistance.

** Algorithm Details**
Dataset is cleaned and preprocessed.

Split 80% for training, 20% for testing.

Random Forest with 132 estimators trained via bootstrap sampling.

Hyperparameter tuning performed to optimize accuracy.

Model deployed using Flask to serve predictions to the web app.

** Results and Benefits**
Accurate disease prediction using Random Forest Classifier.

Personalized recommendations improve user understanding and self-care.

Simple, intuitive UI reduces barriers to entry, even for non-technical users.

No login or subscription required—ensuring broad accessibility.

Helps bridge healthcare gaps in under-served areas.

**Limitations**
Not a replacement for professional medical consultations.

Limited to symptom-based analysis; no medical history, lab reports, or genetic data.

Dependent on accurate symptom input from the user.

No physical examination capabilities (e.g. vitals).

Potential for misdiagnosis in complex cases with overlapping symptoms.

**Future Scope**
Improve AI accuracy with larger and more diverse datasets.

Add voice-based or chatbot-based symptom input.

Support multiple languages for broader accessibility.

Integrate live doctor consultations for expert advice.

Build a mobile app with real-time updates and offline support.

Enhance AI to detect rare and emerging diseases.



