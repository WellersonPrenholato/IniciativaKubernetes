# conversao-temperatura

## Build image
docker image build -t wprenholato/conversao-temperatura:v1 .

# Run
docker container run -d -p 8080:8080 wprenholato/conversao-temperatura:v1