## Installation
1. Download and unzip the project
2. Go to command prompt and open path to project
3. Enter the following command to install the required dependencies
```
pip install -r requirements.txt
```
## Usage
1. Open Jupyter Notebook in your local machine
2. Execute the codes one by one in the same order

## Description of Files

File Name         |  Description
----------------- |--------------------------------------------------------------------------
[Code_1.ipynb]    |  Separating unique startups which are to be captured in BioHubble.  The platforms focuses only on privately held companies so publicly listed companies on various stock exchanges are removed from the list.
[Code_2.ipynb]    |  This code checks for all the patents and clinical trials listed for each private company and write to an excel template which can be uploaded in the BioHubble platform.
[Code_3.ipynb]    |  This code searches for fund raising rounds from Google News  and capture relevant source links. It also parses the  type of funding round, amount and other relevant information from the text of full article. 
[Code_4.ipynb]    |  This code captures relevant news from BioSpace.
[Code_5.ipynb]    |  This code captures relevant news from FiercePharma and FierceBiotech.
[Code_6.ipynb]    | Scrape links from BioSpace by entering any keyword search
[companies.xlsx]  |  Sample list of companies
[non-public.xlsx] | Output of Code_1. Input of Code_2 and Code_3
