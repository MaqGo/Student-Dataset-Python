# Student-Dataset-Python
📊 Pandas Day 3 - Hands-On Notebook
Welcome! This repository contains my Day 3 practice notebook for learning Pandas, the powerful Python library for data analysis. This notebook demonstrates how to install Pandas, check the version, and create simple DataFrames from dictionaries.

🗂️ Contents
✅ Installing Pandas

✅ Checking the version

✅ Creating DataFrames from a dictionary

✅ Basic DataFrame operations

🚀 Getting Started
Clone this repository

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install dependencies

bash
Copy
Edit
pip install pandas
Run the notebook
You can open the notebook in Google Colab, Jupyter Notebook, or VSCode.

📝 Example
python
Copy
Edit
import pandas as pd

# Check version
print(pd.__version__)

# Create a DataFrame from a dictionary
data = {
    "calories": [420, 380, 390],
    "duration": [50, 40, 45]
}

df = pd.DataFrame(data)
print(df)
📚 Requirements
Python 3.x

pandas >= 2.2.2

numpy >= 1.23.2

🤝 Contributing
This is just my learning notebook for practice, but feel free to fork it and make it your own!

📄 License
This project is licensed under the MIT License.
