# VOLTDB-EX-02
VoltDB-Ex-02 Exercise for İ2İ Systems Software Internship

I successfully ran the VoltDB Community Edition using Docker on my GCP virtual machine. I pulled the full360/docker-voltdb-ce:latest image from Docker Hub and configured the container with BUSY_COUNT=1 and HOSTS=node1. I created a local Docker network named voltLocalCluster and launched the container with proper port mappings. The container is actively running as node1, and VoltDB initialized with normal operational status, as confirmed by docker logs and docker ps outputs. Screenshots are attached to demonstrate the successful deployment.
