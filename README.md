# Databases
## MongoDB
- docker run --name test-mongo -dit -p 27017:27017 --rm mongo:4.4.1.
- docker exec -it test-mongo mongo

## SQL
- docker run --name my-postgres -e POSTGRES_PASSWORD=mysecretpassword -p 5432:5432 -d --rm postgres:13.0.
- docker exec -it -u postgres my-postgres psql.

## Neo4j
- docker run -dit --rm --name=my-neo4j -p 7474:7474 -p 7687:7687 --env=NEO4J_AUTH=none neo4j:4.1.3.
- docker exec -it my-neo4j cypher-shell.
## Redis
- docker run -dit --rm --name=my-redis -p 6379:6379 redis:6.0.8.
- docker exec -it my-redis redis-cli.
##Link:https://btholt.github.io/complete-intro-to-databases/
