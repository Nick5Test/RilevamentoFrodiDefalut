AI & Machine Learning Playground 🚀

Questa repository contiene una serie di progetti pratici sviluppati per esplorare e comprendere i concetti fondamentali dell'Intelligenza Artificiale, passando dal Machine Learning (dati tabellari) al Deep Learning (serie temporali).

La repository è divisa attualmente in due progetti principali:
1. Rilevamento Frodi con Carte di Credito (fraud_detection.ipynb)

Questo progetto affronta il problema della classificazione binaria su dataset fortemente sbilanciati. L'obiettivo è identificare transazioni fraudolente all'interno di un enorme volume di transazioni lecite, minimizzando i falsi positivi per non bloccare i clienti onesti.

    Concetti chiave: Data Exploration, Train/Test Split, Confusion Matrix, Precision vs Recall, Class Weighting, Calibrazione del Setpoint (Threshold Tuning).

    Modello utilizzato: Regressione Logistica (Logistic Regression).

    Stack Tecnologico: Python, Scikit-learn, Pandas, NumPy, Matplotlib/Seaborn.

    Dataset: Credit Card Fraud Detection (Kaggle) - Dati reali di transazioni europee del 2013.

2. Predittore di Trend Azionari (stock_predictor.ipynb)

Questo progetto esplora il Deep Learning applicato alla finanza. L'obiettivo è analizzare i dati storici dei mercati finanziari (Time Series) per identificare pattern e prevedere i trend futuri utilizzando una rete neurale.

    Concetti chiave: Serie Temporali (Time Series), Normalizzazione dati, Algoritmo a "Finestra Scorrevole" (Sliding Window / Buffer Circolare) per preparare input sequenziali.

    Modello utilizzato: Rete Neurale Ricorrente con architettura LSTM (Long Short-Term Memory).

    Stack Tecnologico: Python, TensorFlow / Keras, yfinance (per il download dinamico dei dati storici).

    Dataset: Dati di mercato in tempo reale (es. Apple) scaricati tramite le API di Yahoo Finance.