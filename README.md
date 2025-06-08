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
├── API _to_ADLS.ipynb              # Script to extract data from APIs and convert to DataFrame AND upload to ADLS
└── README.md                    # Project documentation
```

## ⚙️ Usage

1. Configure your Azure Storage credentials in `config.py`.
2. Run the data extraction script & Upload the resulting CSV to ADLS:

   ```bash
   python API _to_ADLS.ipynb
   ```


## ✍️ Author

Ravina Babal

## 📜 License

This project is for educational purposes only.
