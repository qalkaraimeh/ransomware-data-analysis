# Ransomware Data Analysis 

a project to practice Data analytics skills using python and for Data Anaytics in Cybersecurity subject for my Academic degree.

Dataset Link [Here](https://www.kaggle.com/datasets/joebeachcapital/ransomware-attacks/data)

## Project Overview:
* Understand the impact of ransomware attacks across sectors and locations.
* Discover attack groups.
* Show attacks analysis over time.
* Discover attack frequency across organization size

## Dataset Details:
* Rows: 360
* Columns: 29
### Key variables:
* sector, location, cost, ransom_cost, revenue_usd_million, ransom_paid, year

## Data Cleaning and preproccessing: 
* Remove columns with >80% missing values.
* Standardize column names.
* Fill missing values for categorical and numerical columns.
* Defined a dictionary to map in values to correct ones.

## Libraries used:
* Pandas
* Numpy
* Seaborn
* LabelEncoder from Sklearn

## Visualizations:

### Most Affected Sectors
![image](https://github.com/user-attachments/assets/992d5859-2847-4554-86ae-ba8d71d685b9)

### Average cost by sector
![image](https://github.com/user-attachments/assets/87aaebf4-a3e1-4773-b207-ad7fb5c830e5)

### Ransom paid status by sector
![image](https://github.com/user-attachments/assets/f116eb6c-1cd9-4a2c-8044-6c3c166e6fd6)

### Relationship Between Ransom Cost, Revenue, and Ransom Paid
![image](https://github.com/user-attachments/assets/2ed39975-8412-4ec8-8ec8-1394c82b21ec)

### Attack Locations
![image](https://github.com/user-attachments/assets/d1c35a0e-a5a6-4a16-a78e-0d9e149c4540)

### Percentage of Ransom Paid, Refused, or Unknown
![image](https://github.com/user-attachments/assets/f34dd1af-3212-4bc7-a1df-362b318050c3)

### Trend of ransomware attacks over years
![image](https://github.com/user-attachments/assets/a3e69fe4-f3d3-4c41-af48-86695b48e3d2)

### Heatmap of correlations
![image](https://github.com/user-attachments/assets/b8700331-8a7c-48ab-89e3-fa4bc2b52ba5)

### Organization size distribution of attacks
![image](https://github.com/user-attachments/assets/c1037053-6549-45ee-bb22-f96bf548180e)

### Pairplot for numerical relationships
![image](https://github.com/user-attachments/assets/826be751-fde9-4742-a5cf-13b20ee799e3)

### Top ransomware groups
![image](https://github.com/user-attachments/assets/7a929c55-389b-4c3c-af4b-12894515b3b9)








