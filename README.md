# VOLTDB-EX-02
VoltDB-Ex-02 Exercise for İ2İ Systems Software Internship

For this assignment, I deployed VoltDB Community Edition on a Google Cloud virtual machine using Docker. I pulled the full360/docker-voltdb-ce:latest image from Docker Hub and created a dedicated Docker network named voltLocalCluster to simulate a clustered environment. I then launched the container using appropriate environment variables, specifying BUSY_COUNT=1 and HOSTS=node1, and verified that the VoltDB instance initialized successfully. The logs confirmed that the server entered the NORMAL operational state, indicating a successful setup. I also used docker ps to validate that the container was actively running with all necessary ports exposed. Screenshots of each step are included to demonstrate the process.

