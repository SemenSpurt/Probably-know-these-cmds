# Containerize
docker build ./path/to/Dockerfile -t tag \
docker run --name name (-d|-it) tag \
docker exec -it tag bash -c "one command && and another" \

# Networking
docker network ls \
docker network inspect network
docker network connect network container

# Remove by name pattern
docker images | grep 'pattern' | awk 'BEGIN {FS=" "}; {print $3}'
