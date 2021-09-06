# austin_incidents
In this project, the following will be done:

1. Creation of an ETL responsible for reading multiple data points in a Google Cloud Storage bucket and placing them in BigQuery.
2. Development of an exploratory analysis using this data.

Our code will be responsible for:
- Receiving a string date as an input
- Reading data according to the input
- Inserting this data in a BigQuery table

Unfortunately, you won't be able to run this code in your machine due to the GBQ data privacy policies. 
In general terms, to setup your GCP environment, you would do the following in your terminal:

1. Install gcloud (https://cloud.google.com/sdk/docs/install)
2. Authenticate using the command "gcloud auth login".
3. Set up your default desired project with "gcloud config set project your_project"
4. Acquire your credentials with "gcloud application-default login".

One of the visuals included in the notebook is a Map, and notebooks uploaded to github apparently can't handle map visuals. To visualize the heatmap, you can access the following nbviewer link:
https://nbviewer.jupyter.org/github/samyrhn/austin_incidents/blob/main/austin_incidents_notebook.ipynb
