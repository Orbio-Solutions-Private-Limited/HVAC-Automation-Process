# HVAC-Automated Data Scraping, Mapping, and Comparison
1. Objective:
   
The objective of this process is to automate the extraction of data from the ENERGY STAR Certified Product Data Sets and APIs webpage, map the raw data according to customer requirements, create formatted UP files, convert them into JSON files, and compare them with the previous month's UP files to identify any new columns.

2. Steps:
   
  Step 1: Data Scraping:
    Utilize Python and relevant libraries (e.g., BeautifulSoup, requests) to scrape data from the ENERGY STAR webpage. Identify and scrape data under the "Heating & Cooling" header and its 12 subcategories. Handle cases where direct scraping is not possible by using HTML code. Store the scraped data in Excel files (Raw files).

  Step 2: Data Mapping:
    Based on customer requirements, map the raw Excel files to create formatted UP files. Perform necessary data manipulation, cleaning, and formatting during the mapping process.
  
  Step 3: JSON File Creation
    Convert the formatted UP files into JSON files using Python. Ensure the JSON files adhere to the specified structure and contain all necessary data fields.
  
  Step 4: Comparison with Previous Month: 
    Retrieve the UP files from the previous month. Automatically compare the current formatted UP files with the previous month's UP files. Identify any new columns added in the current files compared to the previous month.
  
  Step 5: Automated Execution: 
    Develop a Python script to automate the entire process. Use Anaconda Prompt to execute the script, providing all required file paths as inputs. Implement error handling and logging mechanisms to ensure smooth execution and troubleshooting.
  
3. Tools and Resources:
Python programming language
BeautifulSoup, requests libraries for web scraping
Pandas library for data manipulation and Excel handling
JSON conversion tools/libraries
Anaconda environment for script execution and package management

4. Continuous Improvement:
   Encourage feedback from stakeholders and team members to identify areas for process improvement. Implement changes based on feedback and lessons learned to enhance efficiency and effectiveness.

5. Documentation:
     Maintain comprehensive documentation covering all aspects of the automated process, including setup instructions, code documentation, and user guides.
Document any updates, changes, or issues encountered during the process for future reference.
