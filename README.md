# austin_incidents
In this project, the following will be done:

1. Creation of an ETL responsible for reading multiple data points in a Google Cloud Storage bucket and placing them in BigQuery.
2. Development of an exploratory analysis using this data.

Our code will be responsible for:
- Receiving a string date as an input
- Read data according to the input
- Insert this data in a BigQuery table

Unfortunately, you won't be able to run this code in your machine able due to the GCQ privacy policies. 
In general terms, to setup your GCP environment, you would do the following in your terminal:

1. Install gcloud (https://cloud.google.com/sdk/docs/install)
2. Authenticate using the command "gcloud auth login".
3. Set up your default desired project with "gcloud config set project your_project"
4. Acquire your credentials with "gcloud application-default login".

This work is still in progress, and will be finished, at the worst case scenario, at 05/09/2021.
