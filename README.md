## ML Pipeline

Spam Classification

In this pipeline, these are the Five Components:

Data Ingestion -> Pre-processing -> Feature Engineering -> Model Training -> Model Evaluation

I am using Conda Virtual Environment : freshvenv

# 1) Data Ingestion

Logging: 
- Logging is an in-built module in python, we instantiate this module/class with a logger object. 
- Log Handler: It effectively writes/displays a log: Display it in the console (via StreamHandler), in a file (via FileHandler), or even by sending you an email via SMTPHandler, etc.
- Each log handler has 2 important fields:

    - A formatter which adds context information to a log.
    - A log level that filters out logs whose levels are inferior. So a log handler with the INFO level will not handle DEBUG logs.

- Log Formatter: It basically enriches a log message by adding context information to it. it can be useful to know when the log is sent, where and additional context such as thread and process.

-- Logging Levels
- Debug
- Info
- Warning
- Error
- Critical

# 2) Pre Processing 

- Run the data preprocessing file through the terminal
```bash
python src/data_preprocessing.py
```