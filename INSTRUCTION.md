how to run MySQL container with a volume attached
docker run -d -p 8080:8080 --name mysql-local -v mysql-volume mysql-local:1.0.0

how to run an App container which connected to a MySQL db container to a MySQL db container.
docker run -d -p 8081:8080 --name todoapp todoapp:2.0.0

link to docker hub repositorth with an app image
https://hub.docker.com/repository/docker/deadmarvald/todoapp

access the application via a browser
http://localhost:8081/
