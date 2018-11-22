To run the jupyter notebook, run the following command:

	docker run -v c:/Spark/:/home/jovyan -p 8888:8888 162.246.156.70:5000/seng501no

To see running docker containers:

	docker container ls

To see all docker containers:

	docker container ls -a

To (force) remove a specific container:

	docker container rm -f <container_name>

To remove all stopped containers:

	docker container prune
