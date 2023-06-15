# PapyrusNebulae 2023 Document Cloud Hackathon: Round 1

<b>Name:</b> Varun Nagpal <br>
<b>Branch:</b> Mehta Family School of Data Science and Artificial Intelligence <br>
<b>College:</b> IIT Guwahati <br>

## Problem Statement
- The problem is Extracting information from PDF invoices using Adobe PDF Services Extract API.
- ```InvoicesData``` provided here has two folders:
     - ```SampleInvoicesAndData``` folder has two invoices, and the Extracted Data folder contains the ```ExtractedData.csv``` file which contains the data extracted from these invoices. This CSV represents the format in which data needs to be extracted from the invoices. 
     - ```TestDataSet``` folder contains 100 sample invoices and participants are expected to extract data from these 100 invoices in the same form as ExtractedData.csv file.

## Submission/ Deliverables
- ```extract.py``` is the python file containing the code/ solution for the problem statement.
- ```InvoicesData/TestOutput``` folder has the ouput csv's corresponding to the test data invoices.


## Steps to run/ reproduce

1. Clone the project

```bash
  git clone https://github.com/SpyzzVVarun/Adobe-Hackathon-Round-1.git
```

2. Replace the ```private.key``` and ```pdfservices-api-credentials.json``` files with your own credentials. You can get your credentials by following the steps given here: https://developer.adobe.com/document-services/docs/overview/pdf-extract-api/quickstarts/python/#step-one-getting-credentials .

3. Run the extract.py file

```bash
  python3 extract.py
```
