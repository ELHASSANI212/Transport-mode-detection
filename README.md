## 🛰️ Transport Mode Detection from GPS Data Using Deep Learning

This project focuses on the **automatic detection of transportation modes** from **raw GPS trajectories** using **deep learning techniques**. The goal is to build accurate models that can classify user trips into categories such as walking, biking, driving, motorcycling, taking a bus, train, or airplane, based solely on spatial-temporal patterns extracted from GPS data.

### 🎯 Main Objective

Develop and evaluate deep learning models capable of **recognizing the transport mode** used in a given trajectory, using the open **GeoLife dataset** as a benchmark.

### 🗺️ Dataset

We use the **GeoLife GPS dataset** released by Microsoft Research, which contains over 17,000 trajectories annotated with transport modes and collected by 182 users over several years.
Each trajectory includes:

* GPS coordinates (latitude, longitude, altitude)
* Timestamps
* Transport mode labels

### 🧠 Approach

* Preprocessing and cleaning of GPS data
* Feature engineering (speed, acceleration, etc.)
* Sequence segmentation and padding
* Global normalization
* Model training (CNN, LSTM, hybrid architectures)
* Evaluation using standard classification metrics

### 🛠️ Tools & Technologies

* Python
* TensorFlow / Keras
* NumPy, pandas, scikit-learn
* MongoDB (optional: for trajectory storage and preprocessing)
* Matplotlib / seaborn for analysis and visualization

### 🌍 Applications

While the primary goal is **transportation mode classification**, the results can be leveraged for a variety of applications, such as:

* **Carbon footprint estimation** for mobility tracking
* Smart mobility services and recommendations
* Travel behavior analysis
* Urban planning and mobility optimization


