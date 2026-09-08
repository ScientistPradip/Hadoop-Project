# Hadoop Environment Setup and HDFS Data Management

## Project Overview
This project demonstrates the setup and basic usage of a Hadoop
environment using Docker. It includes starting Hadoop services,
creating directories in HDFS, and working with data inside HDFS.

## Technologies Used
- Hadoop
- HDFS
- Docker
- Linux
- VS Code

## Project Steps
### Step 1: Set Up the Hadoop Environment
Started the Hadoop environment inside the Docker container to initialize the required Hadoop services and prepare the environment for HDFS operations.
![Step 1 - Hadoop Environment](Images/Step1_Screenshot.png)

### Step 2: Validate the Hadoop Environment
Verified the Hadoop environment by checking the active Java processes to ensure the required Hadoop services were running successfully.

![Step 2 - Hadoop Services](Images/Step2_Screenshot.png)

### Step 3: Creatre an HDFS Directory
Created a directory in HDFS to provide a dedicated location for storing and managing project data. Also verifying its successful creation.


![Step3 - HDFS Directory](Images/Step3_Screenshot.png)

### Step 4: Prepare the local Data Directory
Created and accessed a local data directory inside the Docker container to prepare the dataset for upload to Hadoop File System (HDFS).


![Step 4 - Prepare Local](Images/Step4_Screenshot.png)

### Step 5: Create a Dataset File
Created the zipcodes.csv file in the local data directory to prepare the dataset for upload to HDFS.
![Step 5 - File Dataset](Images/Step5_Screenshot.png)

