# Setup development environment
Install required Python packages

Open a new terminal, by clicking on the menu bar and selecting Terminal->New Terminal, as in the image below.

Install python packages required to run the application.

python3.8 -m pip install pandas dash


## Download a skeleton dashboard application and dataset
First, let’s get the SpaceX Launch dataset for this lab:

Run the following wget command line in the terminal to download dataset as spacex_launch_dash.csv:
wget "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DS0321EN-SkillsNetwork/datasets/spacex_launch_dash.csv"

Download a skeleton Dash app to be completed in this lab:
wget "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DS0321EN-SkillsNetwork/labs/module_3/spacex_dash_app.py"

Test the skeleton app by running the following command in the terminal:
python3.8 spacex_dash_app.py
