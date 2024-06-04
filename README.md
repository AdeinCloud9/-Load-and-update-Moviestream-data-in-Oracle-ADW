# -Load-and-update-Moviestream-data-in-Oracle-ADW

## Objective
Gain practical knowledge of Oracle Cloud and the unique capabilities of Oracle's Autonomous Data Warehouse in other to support the types of everyday business operations that are needed for real-world data analysis e.g. Oracle MovieStream.

  
### Skills Learned

- Techniques for loading data into an Autonomous Data Warehouse.
- Enabling data integrity features to effectively address data quality challenges.
- Updating existing data by merging new updates.
- In-depth understanding of how an Autonomous Data Warehouse stores and manages data.

### Tools Used

OCI Services Used:

Oracle Cloud Infrastructure | SQL | Data Studio | Autonomous Data Warehouse | Object Storage

## Steps

### 1. Provision an Autonomous Database
- Provisioned a new Autonomous Data Warehouse database.

  *Ref 1: New Autonomous Data Warehouse database created*
  ![Screenshot (613)](https://github.com/AdeinCloud9/-Load-and-update-Moviestream-data-in-Oracle-ADW/assets/170884766/45905957-5453-4e5c-9c7e-1d25ff9e3812)

![Screenshot (614)](https://github.com/AdeinCloud9/-Load-and-update-Moviestream-data-in-Oracle-ADW/assets/170884766/5efde34e-ab9f-47f3-b3df-fcfad6325a9d)

 
### 2. Load Movie Sales Data
- Populated a new data warehouse using the built-in Data Load tool.
  
*Ref 2: Loaded and update MovieStream data in Oracle Autonomous Data Warehouse using Data Studio with Movie Sales Data*
![Screenshot (615)](https://github.com/AdeinCloud9/-Load-and-update-Moviestream-data-in-Oracle-ADW/assets/170884766/da003114-347e-4768-aec7-15b72a05cbfd)
![Screenshot (616)](https://github.com/AdeinCloud9/-Load-and-update-Moviestream-data-in-Oracle-ADW/assets/170884766/205d29da-9861-4283-8216-e044ab70cf5e)

*Ref 3: Success*
![Screenshot (617)](https://github.com/AdeinCloud9/-Load-and-update-Moviestream-data-in-Oracle-ADW/assets/170884766/8fab837e-b489-4e58-b804-ed5d2436636b)

### 3. Enabled Data Integrity
- Added a constraint.
- Tested the new constraint to verify it works.

*Ref 4: Constarints*
  ![Screenshot (619)](https://github.com/AdeinCloud9/-Load-and-update-Moviestream-data-in-Oracle-ADW/assets/170884766/ab5680d4-647a-4227-ae12-73bd02c4736c)
  ![Screenshot (620)](https://github.com/AdeinCloud9/-Load-and-update-Moviestream-data-in-Oracle-ADW/assets/170884766/24c4a185-f9be-4f6d-8afd-ccb77e2bed5c)
  ![Screenshot (621)](https://github.com/AdeinCloud9/-Load-and-update-Moviestream-data-in-Oracle-ADW/assets/170884766/1fe27f50-955c-4c80-9ad0-620e200eff49)


### 4. Updated Sales Data
- Updated the movie sales data using the Data Load tool to merge in a number of adjustment files
- Determined how much space the movie sales table is consuming.
- Updated the movie sales data using Data Studio to merge in data from adjustment files.
- Confirmed the very small increase in space usage after updating the data.
  
*Ref 5: Found out the space usage of the Movie Sales data, Merge in the adjustments from files, Verify the results*

![Screenshot (622)](https://github.com/AdeinCloud9/-Load-and-update-Moviestream-data-in-Oracle-ADW/assets/170884766/b2bce62c-e192-4c65-8cba-ebfefad2bb8e)
![Screenshot (623)](https://github.com/AdeinCloud9/-Load-and-update-Moviestream-data-in-Oracle-ADW/assets/170884766/9e934f30-7ab3-499b-91d4-1ef40de307f7)
![Screenshot (624)](https://github.com/AdeinCloud9/-Load-and-update-Moviestream-data-in-Oracle-ADW/assets/170884766/74c8fa6b-18c4-4914-9621-ac5368c6127c)
![Screenshot (625)](https://github.com/AdeinCloud9/-Load-and-update-Moviestream-data-in-Oracle-ADW/assets/170884766/9e8221c3-b320-45b2-bb96-0f5cb22acd77)

From the project I created using the OCI Warehouse Database, I learned several key points:

- The lab's importance stems from its relevance to real-world data warehouse scenarios, where efficient data management and storage are crucial.
- Oracle Database is designed to handle data updates efficiently, a critical requirement for most data management projects.
- Oracle Autonomous Database automates the data storage process, eliminating the need for manual monitoring or adjustments.
- With Autonomous Database, the process is simplified: you load your data, update it as needed, and the database efficiently manages its storage.
