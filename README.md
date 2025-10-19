## End to End ML Project


# Project Structure:
# 1.Setup.py file: responsible for creating the machine learning pipeline as a package. It can be installed or used and even be deployed in PyPI. It can search and find packages in the folder too.

# 2. -e .(in requirements.txt) : triggers the setup.py to build

# 3.Components(in src): all the modules which are being created (data ingestion, data tranformation, model training)

# 4.Pipeline(in src): 2 pipelines: 1 for training, 1 for prediction

# 5.logger.py: in src

# 6.exception.py: in src

# 7.utils.py: in src: any functionality written in common way which can be used anywhere in the project. All the evaluation techniques for different models.

# 8. Pipeline folder: This is aimed to connect a web application file(app.py) to interact with all the pkl files(in artifacts), to get the input data and make predictions

# 9. predict_pipeline.py: CustomData class is responsible for mapping all the inputs given in html to the backend

# Business problem:Student Performance Indicator (Regression Problem Statement)