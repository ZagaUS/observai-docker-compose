
# ObservAI docker compose

## Requirements

### 1. Kafka

  container name = kafka-zookeeper       \
  port           = 2181

  container name = kafka-broker          \
  port           = 9092


### 2. MongoDB

  container name = mongodb                \
  port           = 27017


### 3. Opentelemetry

  container name = opentelemetry-collector        \
  port           = 2181

### 4. Postgresql

  container name = postgresql14        \
  port           = 5432

### 5. ObservAi Query API

  container name = observai-query-api        \
  port           = 8081

### 6. ObservAi Persistence API

  container name = observai-persistence-api        \
  port           = 8082

### 7. ObservAi Dashboard

  container name = observai-dashboard        \
  port           = 8080



  Note: Change the ports if required