# agile-project-dataset
This dataset was exported from jira from two projects I was part of as ScrumMaster.


## Data

The dataset is located in data directory, it consists of two csv files:
- [jira.csv](data/jira.csv)
- timeseries.csv

### Attribute Information (jira.csv)

| Attribute  |  Description | 
|---|---|
|id|  unique id for the task (combined project and task id) |
| project  |  categorial variable |
| task  |  task id |
| created_date  |  date when the taks was created in jira |
| finished_date  |  date when the taks was closed in jira |
| cycle_times  |  days between created_date and finished_date |

### Attribute Information (timeseries.csv)