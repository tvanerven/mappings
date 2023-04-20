# Mappings
This repository contains a collection of mapping files that are to be used with the [dataverse-mapper](https://github.com/odissei-data/dataverse-mapper).

# Create Mappings
You can either create the mappings by hand or use the spreadsheet that does most of the work for you.
In either case it is important to double check that your paths work. The [JMESPath](https://jmespath.org/tutorial.html) website is a useful tool for this.
Simply paste your JSON source and test the paths.

## Mapping Generator
The spreadsheet does most of the work for you by using a couple of formulas.

Columns you need to fill in by hand:
- Metadata Block
- System Name
- Base Path 
  - **must contain `REPLACE_ME`** 

The `JMESPath Corrected` column is a special case. Incorrect paths are usually generated when dealing with multiple compound values like `authorName`.
These paths need to be manually corrected as shown in the spreadsheet.
