# agile-project-dataset
The dataset contains anonymized project data from Jira.


## Data

The dataset is located in the data directory and consists of one csv file:
- [jira.csv](data/jira.csv) contains a subset of anonymized data from Jira.

### Attribute Information (jira.csv)


| Attribute  |  Description | 
|---|---|
|id|  unique id for the task (combined project and task id) |
| project  |  categorical variable |
| task  |  task id |
| created_date  |  date when the task was created in jira |
| finished_date  |  date when the task was closed in jira |
| cycle_times  |  days between created_date and finished_date |

> __Note__: Some of the observation may be garbage. For example there are observations with a cycle time -1. During a “migration or cleanup session” this may resulted in some cases where finished date is before the created date.

## R-Notebook Analysis
For more details have a look at the R-Notebook output [details_dataset.md](details_dataset.md).
