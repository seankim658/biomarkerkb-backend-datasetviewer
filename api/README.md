# API Setup 

## Directory Structure 

| Directory/File                |                                                                   |
|-------------------------------|-------------------------------------------------------------------|
| `biomarkerkb/`                | The biomarkerkb data api.                                         |
| `config.json`                 | Config file for the api setup.                                    |
| `create_api_container.py`     | Creates the api container.                                        |                                           
| `create_mongodb_container.py` | Creates the initial MongoDB container.                            |
| `Dockerfile`                  | Dockerfile for the api image (used in `create_api_container.py`)                                     | 
| `init_mongodb.py`             | Creates the database user scoped to the biomarkerkbdb.            |
| `load_data.py`                | Loads the MongoDB collection (`biomarker_collection`) with the seed data (from a csv file).           |
| `requirements.txt`            | Requirements file for the api image.                              | 
| `setup.py`                    | Setup script for packaging the biomarkerkb project.               |     