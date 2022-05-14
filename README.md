## Project: Data Modeling with Postgres
### Introduction
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

## Setting up the Environment

### Requirements:
```
postgresql>=9.5
python>=3.6
```

## How to execute this project
Execute the following command to install project dependencies:

```pip3 install -r requirements.txt```

After finishing the dependencies install, execute the `create_tables.py` to initialize sparkify database and _songs_, _artists_, _time_, _users_ and _songplays_ tables:

```python3 create_tables.py```

At least, execute `etl.py` to run the etl pipeline:


```python3 etl.py```

