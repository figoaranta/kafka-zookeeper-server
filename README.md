## Containerized zookeeper and kafka servers

### 1. To start both zookeeper and kafka servers
Run option1: docker-compose -f docker-compose.yml up <br/>
Run option2: docker-compose -f docker-compose.yml up -d (start service in background mode)

### 2. To shut down both zookeeper and kafka servers
Run: docker-compose down

### 3. Accessing kafka
Run: docker exec -it kafka /bin/sh

### 4. Dir to configure kafka features (After executing step 3)
Run: cd opt/kafka
