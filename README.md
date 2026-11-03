# Jorge Lituma Terán

### Computer Science Engineer · Backend · Computer Vision · AI/ML

I’m a Computer Science Engineer from Ecuador. My work brings together backend development, computer vision, and machine learning. I’ve applied these areas to projects in healthcare, education, and financial data, and I’m especially interested in how a trained model can become part of a working service.

## What I work on

### Backend engineering

- Build APIs and services with Python, Flask, and .NET.
- Connect model inference with application logic and business rules.
- Work with SQL, Docker, microservices, and cloud computing.
- Use C and C++ for low-level tasks where performance matters.

One example is a local Flask API that runs computer vision models on refurbished computers, making the project usable without relying on high-end hardware.

### Computer vision

- Prepare image data and train classification and object detection models.
- Work with CNNs, Ultralytics/YOLO, OpenCV, and TensorFlow.
- Explore image enhancement and model interpretability in research settings.

My computer vision work ranges from classifying brain MRI scans to running object detection locally on older computers.

### Artificial intelligence & machine learning

- Build data preparation workflows with Python, Pandas, and PySpark.
- Train supervised and unsupervised models with PyTorch, Keras, and scikit-learn.
- Explore fraud classification and transaction anomaly detection.
- Evaluate models with metrics such as precision, recall, F1, and ROC-AUC.

## Selected work

### Transaction fraud classification

I explored two modeling approaches in separate notebooks. The PyTorch notebook prepares transaction features such as amount, time, device, and transaction velocity, then trains a feed-forward neural network with batch normalization and dropout. The XGBoost notebook uses a separate synthetic dataset and evaluates predictions with classification metrics.

The XGBoost notebook derives its fraud label from an amount threshold, so it is a classification exercise rather than evidence of performance on real fraud cases. I keep that distinction explicit when presenting the work.

**Tools:** Python, PyTorch, XGBoost, Pandas, scikit-learn  
**Notebooks:** [View the project on my portfolio](https://my-portafolio-ec.web.app/#proyectos)

### Alzheimer’s classification from brain MRI scans

Research on deep learning architectures for classifying Alzheimer’s disease from MRI scans. The work includes image preprocessing with OpenCV and analysis of model predictions using Integrated Gradients to make the classification process easier to interpret.

- [Source code and training service](https://github.com/Chris-Liter/ServicioWeb-para-Modelo-Alzheimer)
- [Springer chapter](https://link.springer.com/chapter/10.1007/978-981-96-6438-2_45)
- ICICT 2025 · London, UK

### AI access in public education

A pilot project exploring how refurbished computers can support access to AI in schools. The system used Ultralytics object detection models, local inference with ONNX Runtime, and a locally run LLM through Ollama. A Flask API connected the components and allowed the system to run on older hardware.

- [API and model repository](https://github.com/Chris-Liter/API-With-IA)
- [Springer chapter](https://link.springer.com/chapter/10.1007/978-3-032-09911-2_18)
- ICOMTA 2025 · Valdivia, Chile

### Robertiño: AI for early education

Research on a low-cost educational robot that combines large language models and convolutional networks to support learning in underserved communities.

- [Springer chapter](https://link.springer.com/chapter/10.1007/978-3-032-09911-2_5)
- ICOMTA 2025 · Valdivia, Chile

## Technologies

| Area | Tools |
| --- | --- |
| Languages | Python, Java, C, C++ |
| Backend | Flask, .NET, APIs, SQL, Docker, microservices |
| Machine learning | PyTorch, Keras, TensorFlow, scikit-learn, XGBoost, PySpark |
| Computer vision | OpenCV, Ultralytics/YOLO, CNNs |

## More

- [Portfolio](https://my-portafolio-ec.web.app/)
- [GitHub](https://github.com/Chris-Liter)
- [LinkedIn](https://www.linkedin.com/in/jorge-lituma-teran/)
