# udc_capstone
Udacity Data Engineering Nanodegree Capstone Project

## Project summary
This project develops a data model based on data for immigration into the US. The purpose is to develop tables to be used for analysis.

## Data
The following 3 datasets are used:
- [I94 immigration data](https://www.trade.gov/i-94-arrivals-historical-data)
- [US cities demographic data](https://public.opendatasoft.com/explore/dataset/us-cities-demographics/information/?dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6InVzLWNpdGllcy1kZW1vZ3JhcGhpY3MiLCJvcHRpb25zIjp7fX0sImNoYXJ0cyI6W3siYWxpZ25Nb250aCI6dHJ1ZSwidHlwZSI6ImNvbHVtbiIsImZ1bmMiOiJBVkciLCJ5QXhpcyI6Im1lZGlhbl9hZ2UiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiIjRkY1MTVBIn1dLCJ4QXhpcyI6ImNpdHkiLCJtYXhwb2ludHMiOjUwLCJzb3J0IjoiIn1dLCJ0aW1lc2NhbGUiOiIiLCJkaXNwbGF5TGVnZW5kIjp0cnVlLCJhbGlnbk1vbnRoIjp0cnVlfQ%3D%3D)
- State code mapping data: data > state_code.json

## Workflow
**Step 1**: Scope the Project and Gather Data  
**Step 2**: Explore and Assess the Data  
**Step 3**: Define the Data Model  
**Step 4**: Run ETL to Model the Data  
**Step 5**: Complete Project Write Up  

## Pipeline steps
1. Calculate median age of visitors to US
2. Add median age of visitors column to city demographic dataframe
3. Calculate total count of visitors to each state
4. Add total count of visitors column to immigration data dataframe
5. Get full state names from state code mapping data and join to immigration data dataframe

## Testing
Tests are completed to check for presence of data and expected column names. 
