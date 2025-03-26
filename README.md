# NutriBharat: Smart Diet Planner

## Overview
NutriBharat is a diet planning application designed to provide **personalized, culturally relevant, and nutritionally balanced** meal recommendations. It caters specifically to Indian users, considering regional food habits, dietary preferences, and health conditions. By leveraging a machine learning-based approach, NutriBharat generates meal plans that align with user-specific health goals.

## Features
- **Personalized Meal Plans:** Recommendations based on age, gender, activity level, and health objectives.
- **Culturally Relevant Cuisine:** Incorporates diverse Indian regional food choices.
- **Health-Focused Nutrition:** Supports balanced diets, including diabetic-friendly and specialized meal plans.
- **Seamless User Experience:** Intuitive UI for easy navigation and meal tracking.
- **Data-Driven Recommendations:** Uses the K-Nearest Neighbors (KNN) algorithm for optimal meal suggestions.

## Technologies Used
### **Frontend:**
- Kotlin (Android Development)
- XML for UI Design

### **Backend:**
- Python (Flask Framework)
- Scikit-learn for Machine Learning (KNN Algorithm)
- Pandas & NumPy for data processing

### **Database:**
- CSV files for food and nutritional data storage

## Installation & Setup
### **Prerequisites:**
- Android Studio (for frontend development)
- Python 3.8+ (for backend development)
- Flask and required Python libraries:
  ```bash
  pip install flask pandas numpy scikit-learn
  ```

### **Steps to Run the Application:**
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ishansaxena012/SmartDietPlannerApp.git
   cd NutriBharat
   ```
2. **Backend Setup:**
   ```bash
   cd backend
   python app.py
   ```
3. **Frontend Setup:**
   - Open the Android project in **Android Studio**.
   - Build and run the application on an emulator or a physical device.
   - 
## Screenshots
Here are some visuals of NutriBharat in action:

<img src="https://github.com/user-attachments/assets/8aaadc9b-9c7e-4386-af52-f7728e818947" width="300">
<img src="https://github.com/user-attachments/assets/39c98a88-fa34-40e5-9fb4-1e57a8217381" width="300">
<img src="https://github.com/user-attachments/assets/e995c8e4-9458-404b-8767-c3e169fe8fba" width="300">
<img src="https://github.com/user-attachments/assets/aea9641e-a921-4bf2-a454-6a3873506499" width="300">




## How It Works
1. Users input personal details (age, gender, health conditions, dietary preferences, etc.).
2. The system calculates **Total Daily Energy Expenditure (TDEE)**.
3. The KNN algorithm recommends meals matching user requirements.
4. Users receive **optimized, culturally appropriate** meal plans.

## Future Enhancements
- **Real-time meal tracking and updates**
- **Integration with fitness apps and wearables**
- **Cloud-based database for scalability**
- **Cross-platform availability (iOS & Web)**



## License
This project is licensed under the **MIT License**.

---
**NutriBharat – Transforming Nutrition with Smart Technology!**
