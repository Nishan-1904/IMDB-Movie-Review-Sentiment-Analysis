
# 🎬 IMDb Movie Review Sentiment Analysis

This project performs **Sentiment Analysis** on IMDb movie reviews using a **Simple RNN model** built with **TensorFlow** and **Keras**. The goal is to classify movie reviews as either **positive** or **negative**, helping automate opinion mining from large volumes of text data.

Achieved **~94% accuracy** on the test dataset.

## 📌 Features

- Pre-trained on the IMDb dataset from `keras.datasets`.
- Simple yet effective **Recurrent Neural Network (RNN)** architecture.
- Streamlit-based web application for live user input and sentiment prediction.
- Integrated preprocessing pipeline for raw text input.
- Interactive demo using `Streamlit`.

---

## 🧠 Model Architecture

- Embedding Layer
- Simple RNN Layer
- Dense Output Layer with Sigmoid activation

> The model was trained on 25,000 reviews (IMDb dataset) and tested on 25,000 reviews, achieving ~94% accuracy.

---

## 📁 Project Structure

```

├── simplernn.ipynb        # Model training and evaluation notebook
├── prediction.ipynb       # Model testing and predictions notebook
├── main.py                # Streamlit web app for real-time prediction
├── simple\_rnn\_imdb.h5     # Trained model file (load externally)

````

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/imdb-sentiment-analysis.git
cd imdb-sentiment-analysis
````

### 2. Install Dependencies

Create a virtual environment and install required packages:

```bash
pip install -r requirements.txt
```

<sub>*If `requirements.txt` is not available, install manually:*</sub>

```bash
pip install tensorflow keras numpy streamlit
```

### 3. Run the Streamlit App

```bash
streamlit run main.py
```

Then, open the provided URL (typically `http://localhost:8501`) in your browser.

---

## 📊 Example

Input:

> "The movie was absolutely fantastic and full of suspense!"

Output:

> Sentiment: **Positive**
> Prediction Score: `0.93`

---

## 📚 Dataset

* IMDb movie review dataset
* Available via:

  ```python
  from tensorflow.keras.datasets import imdb
  ```

The dataset contains **50,000 labeled reviews**, split equally for training and testing.

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Streamlit
* Jupyter Notebook

---

## 📈 Results

| Metric     | Value      |
| ---------- | ---------- |
| Accuracy   | \~94%      |
| Model Type | Simple RNN |

---

## 🧪 Notebooks

* `simplernn.ipynb` – Model creation and training
* `prediction.ipynb` – Prediction and evaluation examples

---

## 📥 Future Improvements

* Add LSTM or GRU for enhanced performance
* Deploy app using Streamlit Cloud or HuggingFace Spaces
* Visualize attention weights for interpretability

---

## 🙌 Acknowledgements

* [Keras IMDb dataset](https://keras.io/api/datasets/imdb/)
* TensorFlow & Streamlit documentation

---

## 🧑‍💻 Author

**Nishan Chakraborty**

Feel free to ⭐ the repo and reach out for suggestions or collaboration!

```

Let me know if you’d like a `requirements.txt` file or deployment guide as well.
```
