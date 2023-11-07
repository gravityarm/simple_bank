# Show images 
docker images 

# Run docker instance
docker run --name postgres -e POSTGRES_USER=root -e POSTGRES_PASSWORD=secret -p 5432:5432 -d postgres:16.0-alpine3.18


# for starting manually
sudo docker start postgres