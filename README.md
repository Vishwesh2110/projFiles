This project uses **Git LFS (Large File Storage)** to manage large data files.  
Follow the steps below carefully to run the project on your local machine.
use python 3.10 or 3.11
---

## Prerequisites

Make sure you have the following installed:

* **Git**
* **Git LFS**
* **Python 3.9+**
* **pip**

---


## Step 1: Install Git LFS

Git LFS is required to download large files used in this project.

```
git lfs install
```

### Step 2: Clone the Repository

Clone the project from GitHub:

```
git clone https://github.com/Vishwesh2110/projFiles.git
```
Move into the project directory:

cd projFiles


### Step 3: Install Required Python Packages

Install all required dependencies using pip:
```
pip install fastapi uvicorn sqlalchemy jinja2 python-multipart chromadb sentence-transformers groq sounddevice numpy openai-whisper
```


### Step 4: Run the Application

Start the FastAPI server using Uvicorn:
```
python -m uvicorn app.main:app --reload
```

### Step 5: Access the Application

Once the server starts, open your browser and go to:
```
http://127.0.0.1:8000
```
