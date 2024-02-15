# 11_Web_Scraping_Project

This project involves 2 parts/deliverables related to Mars News/Table information scraped from the Mars Exploration Program website. 

Part 1 scrapes and stores news article information (title and text summary/preview) from the [News Page](https://static.bc-edx.com/data/web/mars_news/index.html) and stores the information as a list of dictionary pairs, which is then saved as a JSON file. 

Part 2 scrapes the data table from the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html), and pulls out the header and all row-data from the talbe and stores that information in a pandas dataframe. Once the data is in a dataframe, data cleaning/data type conversion is completed to prepare for analysis. Finally, the data is analyzed to answer questions about temperature across the months of mars and compare days and months on Mars to those on Earth. The dataframe is also saved as a CSV file for further use. 

### Additional Analysis 

In addition to the required analysis for this module, some additonal analysis was completed in order to determine the number of Earth days in a Martian year. This involved using the solar longitude column, finding the Earth dates that had the same solar longitude reported on Mars (same solar latitude interpreted as Mars going around the sun completely/one year), and then using Datetime operation to calculate days elapsed. 

### Repository Notes

JSON file from part 1 and CSV file from part 2 are saved in the 'output' folder in the repository.  


### Code Source

 In order to output the data from part 1 as a JSON file, I utilized sample syntax and adapted from the below example:
 <https://www.geeksforgeeks.org/reading-and-writing-json-to-a-file-in-python/>
 