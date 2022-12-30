Learn Kubernetes by Example.


# Level 1. 

Create a basic flask app deployment with Kubernetes.

# Level 2.

Same as Level 1 but add a worker service that communicates internally with our flask server. Simple get request.

# Level 3. 

Connect the flask server to an External database.

# Level 4. 

Have the worker do 'fake work' and post its results to the server who in turns saves them to a database.



# Temp

Build image.
docker build --tag digitaloceanflaskk8s .
Run image.
docker run -p 8080:8080 -p digitaloceanflaskk8s
Visit
visit: http://localhost:8080/