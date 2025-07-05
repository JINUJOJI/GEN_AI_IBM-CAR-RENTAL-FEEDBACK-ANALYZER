# 🚗 Car Rental Customer Feedback Analyzer

This project analyzes customer feedback from a car rental service using IBM Watsonx and foundation models like FLAN-UL2. The analysis includes sentiment prediction and business area classification to help identify customer satisfaction and key service issues.

---

## 📂 Project Structure

File/Folder                | Description                                                                 
---------------------------|-----------------------------------------------------------------------------|
 car_rental_notebook.ipynb  | Main notebook developed in IBM Watsonx and Watson Studio for data analysis. 
 car_rental_train.csv       | Training data collected from Google Form responses.                         
 car_rental_test.csv        | Test data (new feedback) collected from the same survey.                    
 FLOWCHART_CAR_FEEDBACK.pdf | Visual flowchart showing the step-by-step methodology of the project.        

---

## 🛠️ Key Technologies

- **IBM Watsonx**
- **Watson Studio**
- **Python (pandas, scikit-learn)**
- **FLAN-UL2 Foundation Model**
- **IBM Cloud Object Storage**

---

## 🔍 What the Project Does

1. **Loads feedback data** from CSV files stored in IBM Cloud Object Storage.
2. **Preprocesses the text** using pandas.
3. **Performs sentiment analysis** using FLAN-UL2 on Watsonx.
4. **Classifies feedback** into business areas like:
   - Product: Pricing and Billing
   - Service: Accessibility
   - Service: Attitude, etc.
5. **Displays results** for further insights and reporting.

---

## 📊 Dataset

- Data was collected via **Google Form** filled by users of a car rental service.
- CSV files include real customer responses with open-text feedback.

---

## 📌 Note

This project was created as part of an academic exercise during the certification of IBM GEN AI course by IBM SKILLS BUILD WITH ADROIT TECHNOLOGIES CHENNAI 
IBM Cloud services to demonstrate real-world applications of Natural Language Processing in customer experience analysis.

---
## 📎 License

This project is licensed under the [MIT License](LICENSE).

