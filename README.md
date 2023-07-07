# Personalize POC
This infrastructure implementation instantiates the AWS personalize dataset and solution.   

## Building the stack
There are 2 separate deployments required for the recommender stack:

### 1. Datasets
The CloudFormation template `recommender-dataset-stack.yaml` will build/update the dataset stack.   

### 2. Solution stack
All other components are built through the python notebook `solution-stack.py.ipnb`.  

To build this stack you will need a functioning Python environent (3.9 or higher):
1. cd to the project directory
2. create a virtual environment `python -m venv venv `
3. activate virtual environment `source venv/bin/activate`
4. install requirements `pip install -r requirements.txt`
4. start jupyter `jupyter notebook`
5. a web browser will now launch, open the `solution-stack.py.ipnb` notebook and run cell by cell.







