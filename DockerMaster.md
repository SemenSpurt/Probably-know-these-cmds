docker build ./path/to/Dockerfile -t tag
docker run --name name (-d|-it) tag
docker exec -it tag bash -c "one command && and another"
