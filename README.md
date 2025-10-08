# SignSpeak

**Bridging the Communication Gap with AI‑Powered Sign Language Translation**

SignSpeak is an open‑source initiative aimed at translating Indian Sign Language (ISL) gestures into spoken language using time‑series classification models. By leveraging low‑cost flex sensors and advanced machine learning techniques, SignSpeak aspires to make communication more accessible for the hearing and speech‑impaired communities.

---

## 🧠 Features

* **Real‑Time Translation**: Converts ISL gestures to text in real time with tkinter based GUI.
* **Robust Dataset**: Utilizes the [INCLUDE 50](https://www.kaggle.com/datasets/yuvrajjoshi1110/include-50) which have data in form of adjectives, pronouns, greetings, etc.
* **High Accuracy**: Achieved up to 63% accuracy with models like LSTMs.
* **Cost‑Effective Hardware**: Designed to work with minimum load on hardware.

---

## 📁 Project Structure

```bash
SignSpeak/
├── models/                 # Pre-trained models
├── app.py                  # Main application script for real-time translation
├── build_notebook_kaggle/  # Jupyter notebook for data processing and model training
├── requirements.txt        # Project dependencies
├── .gitignore              # Specifies files to ignore in version control
└── README.md               # Project documentation (you are here)
```

---

## 🚀 Getting Started

### Prerequisites

* Python 3.7 or higher
* pip

### Installing Dependencies

```bash
pip install -r requirements.txt
```

### Running the Application

1. **Clone the repository**:

```bash

git clone https://github.com/Mridul-23/SignSpeak.git
cd SignSpeak
```

2. **Launch the app**:
```bash
python app.py
```

This will start the real‑time ISL‑to‑speech translation interface.

---

## 🧪 Dataset

The dataset is quite huge and this project is made on subset of the dataset of 27 common words and phrases. Original Dataset link: https://www.kaggle.com/datasets/yuvrajjoshi1110/include-50

## 🤖 Model Training

The `build_notebook_kaggle` directory contains a comprehensive Jupyter notebook that walks through:

1. Data preprocessing and augmentation
2. Model architecture setup
3. Training and validation loops
4. Performance evaluation and visualization

Feel free to experiment with architectures or hyperparameters to further improve accuracy.

---

## 📈 Results

* **Top Accuracy**: 60%+ (LSTM‑based model)
* **Metrics Reported**: Accuracy score, Multilabel Confusion Matrix, Graphs between Training and Validation Accuracy and same for Loss.

These results demonstrate the effectiveness of combining time‑series data with advanced sequence models for ISL translation.

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m "Add some feature"`)
4. Push to your branch (`git push origin feature/YourFeature`)
5. Open a pull request

Please ensure your code follows the existing style and includes tests where applicable.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

For questions or collaborations, reach out to **Mridul**:

* Email: [mail here](mridulnarula23@gmail.com)
* GitHub: [Mridul-23](https://github.com/Mridul-23)
