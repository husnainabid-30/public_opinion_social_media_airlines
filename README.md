# Google Colab - Upload Jupyter Notebook and CSV File

This repository contains a Jupyter Notebook that you can upload and run on [Google Colab](https://colab.research.google.com/). Follow the steps below to upload the notebook (`.ipynb` file) and CSV data (`tweets.csv`), and execute the cells within Colab.

## Steps to Use Google Colab

### 1. Upload the Jupyter Notebook to Google Colab
1. Go to [Google Colab](https://colab.research.google.com/).
2. Click on **File** > **Upload Notebook**.
3. Upload the 'ipynb' file from your local machine.
4. Once the notebook is uploaded, you can start executing cells by pressing `Shift + Enter` on each cell.

### 2. Upload the CSV File (`tweets.csv`) to Google Colab
To upload the CSV file to use in the notebook, follow these steps:

#### Option 1: Upload CSV Manually within Colab
1. In your Google Colab notebook, locate the left-hand sidebar and click on the **Files** tab.
2. Click the **Upload** button and choose the `tweets.csv` file from your local machine.
3. After the upload is complete, you can reference the file in your code like this:

```python
import pandas as pd

# Load the CSV file
df = pd.read_csv('/content/tweets.csv')

# Display the first few rows of the dataframe
df.head()
