# Data Ingestion from APIs to Azure Data Lake Storage (ADLS)

## 📌 Project Overview

This project demonstrates how to:

1. Extract data from REST APIs.
2. Convert the response into a DataFrame using `pandas`.
3. Save the data to a CSV file.
4. Upload the CSV file to Azure Data Lake Storage using the Azure Storage SDK.

## 🚀 Project Goals

* Automate data ingestion from multiple REST APIs.
* Store the processed data in Azure Data Lake Storage for further analytics or pipeline processing.
* Learn the basic principles of cloud-based data engineering workflows using Python.

## 🛠️ Technologies Used

* Python
* Pandas
* Requests
* Azure Storage Blob SDK
* Azure Data Lake Storage (ADLS)
* Git & GitHub

## 📁 Project Structure

```bash
project-root/
├── config.py                    # Configuration file with API URLs and Azure keys
├── API _to_ADLS.ipynb              # Script to extract data from APIs and convert to DataFrame         # List of Python dependencies
└── README.md                    # Project documentation
```

## ⚙️ Usage

1. Configure your Azure Storage credentials in `config.py`.
2. Run the data extraction script & Upload the resulting CSV to ADLS:

   ```bash
   python API _to_ADLS.ipynb
   ```

## 🔐 Azure Configuration

* Go to your Azure Storage account.
* Navigate to **Access Keys** and copy **key1**.
* Set it in your `config.py` like so:

```python
AZURE_STORAGE_ACCOUNT_NAME = "your_account_name"
AZURE_STORAGE_ACCOUNT_KEY = "your_account_key"
CONTAINER_NAME = "your_container_name"
```

## ✍️ Author

Ravina Babal

## 📜 License

This project is for educational purposes only.
