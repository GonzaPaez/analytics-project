# Analytics Portfolio Project 📊
A data analytics project based on **Part II** of the book "Hands-On APIs for AI and Data Science" by Ryan Day.


## 📖 Description
This repository contains the source code and practical examples developed as part of learning APIs for AI and Data Science. The project focuses on implementing data analysis techniques, API consumption, and information visualization following the methodologies presented in the reference book.

## 🎯 Project Objectives

Implement RESTful APIs for data analysis. 
Apply data processing and cleaning techniques. 
Develop interactive visualizations.  
Create scalable data pipelines.

## 🛠️ Technologies Used

Python 3.8+
FastAPI - Framework for creating APIs
Pandas - Data manipulation and analysis
NumPy - Numerical operations
Matplotlib/Plotly - Data visualization
SQLAlchemy - Database ORM
Docker - Containerization
Apache Airflow - Apache Airflow - Workflow orchestration


## 🚀 Installation and Setup

### Prerequisites

Python 3.8 or higher
pip (Python package manager)
Docker (optional, for containerization)

### Local Installation

1. **Clone the repository:**
```bash
git clone https://github.com/GonzaPaez/analytics-project.git
cd analytics-project
```

2. **Create virtual environment:**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies:**
```bash
pip install -r requirements.txt
```

4. **Configure environment variables:**
```bash
cp .env.example .env
# Edit .env with your configurations
```

### Docker Installation
```bash
docker-compose up --build
```

## 💻 Usage

### Running the API

```bash
# Development
fastapi dev api/main.py --port 8000


# Production
fastapi run api/main.py --host 0.0.0.0 --port 8000

```

The API will be available at: http://localhost:8000

### API Documentation

- **Swagger UI:** http://localhost:8000/docs
- **ReDoc:** http://localhost:8000/redoc

## Running Data Analysis
```bash
# Run Jupyter notebooks
jupyter notebook notebooks/

# Run analysis scripts
python src/analysis/data_analysis.py
```
