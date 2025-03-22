# Project Readme

## Sub_Search Chatbot

### Tech Stack
This project is a Retrieval-Augmented Generation (RAG) system built using LangChain for natural language processing and big data handling. It leverages Python for scripting and automation. Key dependencies include `pandas` for data manipulation, `numpy` for numerical operations, and `sqlite3` for database management. Refer to the `requirements.txt` file for a complete list of dependencies.

## Getting Started

Follow the steps below to set up and run the project:

### 1. Clone the Repository
```bash
git clone https://github.com/MiruthyanJayanS/Sub_Search.git
cd Sub_Search
```

### 2. Save the Dataset
Place the `.db` file in the `Dataset` folder.

### 3. Run Data Preprocessing
Execute the `Data_Preprocessing.py` script to create the entire pipeline:
```bash
python Data_Preprocessing.py
```

### 4. Run the Main Script
Run the `main.py` file using Streamlit to start the project:
```bash
streamlit run main.py
```

Follow the instructions above to ensure proper setup and execution.