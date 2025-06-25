## 📄 Dataset Description – Sonar Rock vs Mine 🪨💣

This dataset contains sonar signal returns collected by bouncing sound waves off different objects.  
The primary goal is to **classify** whether the object is a **Rock (🪨)** or a **Mine (💣)** based on the characteristics of the reflected sonar signals.

---

### 📦 Content

- 📊 **Features:** 60 numerical attributes (🧪), each representing the **strength of a sonar return signal** at a particular frequency  
- 🎚️ **Range:** All feature values are normalized between **0 and 1**  
- 🔁 **Target Variable:**  
  - `"R"` = Rock 🪨  
  - `"M"` = Mine 💣  

- 📈 **Samples:** 208  
- 🧪 **Type:** Binary Classification

---

### 🧠 Model Used – Logistic Regression (📈➡️📉)

To classify the sonar signals, I implemented **Logistic Regression**, a probabilistic linear model that is well-suited for **binary classification** tasks.  
It learns patterns in the frequency-based signal data to estimate the likelihood that a sonar return corresponds to a **mine (💣)** or a **rock (🪨)**.

✅ Logistic Regression provided interpretable results and performed well on this dataset due to its ability to model binary decision boundaries.

---

This project demonstrates how signal data can be analyzed using machine learning to assist in **object detection and classification** in real-world environments s
