# **Predictive Modeling Using Decision Trees and Random Forests**  

## **Overview**  
This project explores the use of **decision trees** and **random forests** to build predictive models across multiple domains. By leveraging machine learning techniques, we aim to analyze and optimize **football player position prediction, music genre classification, and mobile phone price prediction**. The study highlights the effectiveness of feature engineering and model selection in generating **highly accurate and competitive results**.

## **Datasets & Applications**  
We implemented and evaluated decision tree and random forest models across three real-world datasets:  

1. **Football Player Position Prediction**  
   - Predicts a football player’s position based on attributes such as crossing, finishing, ball control, and shot power.  
   - **Applications:** Used by coaches, managers, and sports analysts for player selection and performance optimization.  

2. **Music Genre Classification**  
   - Classifies songs into genres using audio features like acousticness, danceability, energy, and loudness.  
   - **Applications:** Can enhance recommendation systems in platforms like Spotify, Apple Music, and YouTube Music.  

3. **Mobile Phone Price Prediction**  
   - Predicts a mobile phone’s price range based on features like brand, battery power, internal memory, and RAM.  
   - **Applications:** Helps consumers make informed purchasing decisions and assists manufacturers in pricing strategies.  

## **Methodology**  
- **Data Preprocessing:** Feature selection, normalization, and handling missing values.  
- **Machine Learning Models:** Implemented **Decision Trees** and **Random Forests** using Scikit-Learn, XGBoost, and LightGBM.  
- **Evaluation Metrics:** Models were compared based on **accuracy** and **F1-score** to determine performance.  
- **Results:**  
  - **Random Forest consistently outperformed Decision Trees** in all three case studies.  
  - **XGBoost and LightGBM improved model accuracy** through advanced boosting techniques.  

## **Results & Findings**  
- **Football Player Prediction:** LightGBM achieved the highest accuracy of **85.63%**.  
- **Music Genre Classification:** LightGBM provided the best performance with **57.94% accuracy**.  
- **Mobile Phone Price Prediction:** XGBoost outperformed all models with **90.75% accuracy**.  

## **Installation & Usage**  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/predictive-modeling.git
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Run the model training script:  
   ```bash
   python train_model.py
   ```  
