## 3MTT Showcase Update

I recently shared my **#3MTT** showcase on LinkedIn, but unfortunately, my account was restricted shortly after posting.  
Please don’t be alarmed — I had to fill out the 3MTT form **twice**, and that might have triggered the restriction.  
I’ve already submitted the appeal and I’m hoping my account will be restored soon.

---

### 🎥 Watch on YouTube  
[https://youtu.be/1vF65j13GsA](https://youtu.be/1vF65j13GsA)

### 🔗 View LinkedIn Post (once account is restored)  
[https://www.linkedin.com/posts/suleiman-abdulkadir-10067b365_3mttlearningcommunity-my3mtt-3mttnigeria-activity-7328860167016501251-dJPR](https://www.linkedin.com/posts/suleiman-abdulkadir-10067b365_3mttlearningcommunity-my3mtt-3mttnigeria-activity-7328860167016501251-dJPR)

---

**Thanks for your understanding and support!**

---


# AI Image Classification

This repository contains the code for an **AI-powered image classification application**. The project uses **PyTorch**, **Flask**, and a pre-trained **ResNet50** model for image classification. It is designed to run locally using Docker.

---

## ✨ Features

- **Image Classification**: Classifies images (e.g., cats vs. dogs) using a pre-trained ResNet50 model.
- **Containerization**: The application is packaged in a Docker container for consistent deployment.
- **Simple Frontend**: A web interface allows users to upload images for classification.

---

## 🏗️ Project Architecture

1. **Frontend**: A simple HTML interface (`upload.html`) allows users to upload images for classification.
2. **Backend**: A Flask application (`app.py`) handles image uploads and routes requests to the image processing logic.
3. **Image Processing**: A Python script (`image_processor.py`) uses PyTorch and ResNet50 to classify uploaded images.
4. **Containerization**: Docker is used to package the application for consistent deployment.

---

## 🧰 Prerequisites

To run this application locally, ensure you have the following installed:

- Python 3.8+
- Pip
- Docker
- Git

---

## 🚀 Local Setup and Usage

Follow these steps to run the application locally:

1. Clone this repository:

   ```bash
   git clone https://github.com/suletete/ai-image-classification-devops.git

2. Build the Docker container:

   ```bash
   docker build -t ai-image-classification -f docker/Dockerfile .
   ```

3. Run the Docker container:

   ```bash
   docker run -p 4000:5000 ai-image-classification
   ```

4. Open your browser and navigate to:

   ```
   http://localhost:4000
   ```

5. Upload a `.png` or `.jpeg` image to see the classification result.

---

## 📂 Folder Structure

```
ai-image-classification/
│
├── app.py                  # Flask application
├── image_processor.py      # Image classification logic using PyTorch and ResNet50
├── templates/
│   └── upload.html         # Simple HTML frontend
├── docker/
│   └── Dockerfile          # Docker configuration
└── README.md               # Project documentation
```

---

## 📜 Credits

This project is by

```

By Suleiman Abdulkadir | Fellow ID: FE/23/22599501 | Cohort 3

```
