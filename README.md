# ubd-prototype

Need a Neo4j database running:

1. If using Docker:

`$ docker run -d -e NEO4J_AUTH=neo4j/ubdprototype -p 7687:7687 -p 7474:7474 --name neo4j --rm neo4j`

(To stop Neo4j, `docker stop neo4j`. The docker container will be automatically removed.)

2. Using Neo4J Desktop

- Install Neo4j Desktop application

- Create a new project and database (using a local database for now)

- Set a password for the local database; username should be 'neo4j'

- Start the database

3. Install the required python packages

`$ pip install -r requirements`

4. Run the application

`$ python app.py`

5. Browse to http://localhost:5000


