# Geospatial Data as a Service Tool for Analysts: A Streamlit App for Downloading and Visualizing NOA Satellite Datasets
## Assignment 1

[Streamlit App](https://mi6daas.streamlit.app) <br>
[Codelabs](https://codelabs-preview.appspot.com/?file_id=1LlSUQF9Ixa4IFk45f9_GD6jMIE73DX39n7bGfjhB7JY#0) <br>

## Summary 
The project is for a geospatial startup, building a data ETL tool to make it easier for data analysts to access and download publicly available data from the NOA website. The tool is built using Streamlit and the datasets chosen for exploration are the NexRad and GOES satellite datasets.

The project was split into three parts:

Exploration of the GEOS dataset

Exploration of the NexRad dataset:

Plotting of NexRad locations:

## Architecture

<img src="https://raw.githubusercontent.com/BigDataIA-Spring2023-Team06/Documentation/main/pasted%20image%200.png" width="500">


## File Structure
#### 🚀 Production Master Branch
```
.
├── Book.csv
├── Home.py
├── README.md
├── State_StationCode_Mapping.csv
├── helper_functions                  # Logging & other functions for operations on S3
│   ├── cw_logs.py
│   ├── date_converter.py
│   ├── goes_module.py
│   ├── helper.py
│   └── noes_module.py
├── images
│   └── cover.png
├── metadata_db                       #Metadata DB
│   ├── data_viz.ipynb
│   ├── s3_metadata_goes.db
│   ├── s3_metadata_noes.db
│   └── to_csv.ipynb
├── metadata_scraping                 #Metadata Scraping Scripts
│   ├── goes_metadata_scrapper.py
│   └── test.ipynb
├── pages                             #Streamlit App Pages
│   ├── Book.xlsx
│   ├── GOES.py
│   ├── Nexrad Locations.py
│   ├── Nexrad.py
│   └── nexrad.xlsx
├── query_test_ui.py
├── requirements.txt
├── statecodes.csv
└── unit_testing                      # Unit Tests
    ├── goes_link_validation.py
    ├── goes_module_test.py
    ├── noes_unit_test.py
    ├── test_cases_goes.py
    └── test_cases_noes.py
```
#### 🎚️ Great Expectations

Switch to the ```great_expectations``` branch

## Running the project

#### Create a Virtual Environment
```
python3 -m venv venv
```
#### Installing the requirements
```
pip3 install -r requirements.txt      #available in the root directory of the project
```
#### Running the Streamlit App
```
streamlit run Home.py
```

#### WE ATTEST THAT WE HAVEN’T USED ANY OTHER STUDENTS’ WORK IN OUR ASSIGNMENT
AND ABIDE BY THE POLICIES LISTED IN THE STUDENT HANDBOOK
#### Contribution: <br>
● Midhun Mohan Kudayattutharayil: 25% <br>
● Sanjay Kashyap: 25% <br>
● Snehil Aryan: 25% <br>
● Vikash Singh: 25% <br>


