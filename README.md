## Containerized zookeeper and kafka servers \n

### 1. To start both zookeeper and kafka servers \n
option1: docker-compose -f docker-compose.yml up
option2: docker-compose -f docker-compose.yml up -d (start service in background mode)

### 2. To shut down both zookeeper and kafka servers \n
docker-compose down

### 3. Accessing kafka \n
docker exec -it kafka /bin/sh

### 4. Dir to configure kafka features (After executing step 3) \n
cd opt/kafka
