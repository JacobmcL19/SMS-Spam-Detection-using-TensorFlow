# SMS Spam Detection using TensorFlow  

## Overview  
This project applies deep learning techniques to detect SMS spam, protecting users from fraudulent messages. Using TensorFlow, we develop and compare multiple models, including:  
- **Baseline Model**: Naïve Bayes with TF-IDF  
- **Custom Vectorization Model**: Embeddings with a Dense Network  
- **Bidirectional LSTM Model**: Recurrent Neural Network for sequential patterns  
- **Transfer Learning Model**: Universal Sentence Encoder (USE)  

## Dataset  
We use the SMS Spam Detection Dataset, which contains labeled SMS messages as **ham** (legitimate) or **spam**.  

## Implementation  
1. **Data Preprocessing**: Cleaning and encoding labels  
2. **Exploratory Data Analysis**: Distribution of spam vs. ham messages  
3. **Model Training**: Training and evaluating different models  
4. **Performance Evaluation**: Comparing accuracy, precision, recall, and F1-score  

## Results  
- All models achieved over **96% accuracy**, with the **USE-Transfer Learning model** performing best in terms of accuracy and F1-score.  

## Tech Stack  
- Python, TensorFlow, Keras  
- Pandas, NumPy, Matplotlib, Seaborn  
- Sklearn, TensorFlow Hub  

## Conclusion  
This project demonstrates the effectiveness of deep learning in SMS spam detection, with transfer learning providing the most robust results.  
