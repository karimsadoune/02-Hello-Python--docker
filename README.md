
# Creation d'image
docker build -t test

# Execution
docker run -d -p 5000:5000 test