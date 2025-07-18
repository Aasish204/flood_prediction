# flood_prediction
Flood_Prediction

This project implements a real-time machine learning model to predict floods based on environmental factors such as rainfall, humidity, and cloud coverage. The model uses a publicly available dataset, originally published in a research paper, which was preprocessed using techniques like label encoding, scaling, and SMOTE to balance the class distribution.
Exploratory Data Analysis (EDA) helped identify key features and uncover patterns related to flood occurrences. A Random Forest classifier was trained to predict flood incidents, achieving high accuracy.
To improve efficiency, parallel processing techniques were employed, significantly reducing training time. The system supports multi-core inference, enabling faster, real-time predictions. The model's performance was evaluated based on training time, accuracy, and latency across both single-core and multi-core configurations.
