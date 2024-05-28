### Basketball Player Identification using Azure ML, Azure Face and Azure AI Vision

This repo provides 3 example notebooks to build a player detection and jersey recognition pipeline using Azure services including Azure Machine Learning, Azure Face and Azure AI Vision.


### 1. Install dependencies

Python libraries required for both notebooks

```pip install -r requirements.txt```

### 2. Provide your Azure credentials
Create a `.env` file based on the [.env.example](./.env.example) file, replace the placeholders with your account information.

### 3. Add your images to the `images` folder
### 4. Execute the [segmentation.ipynb](./segmentation.ipynb) notebook
### 5. Execute the [faces_person.ipynb](./faces_person.ipynb) notebook
### 6. Add your jersey reference images to the [jersey folder](./images/jerseys) and execute the [jersey_recognition.ipynb](./jersey_recognition.ipynb) notebook
