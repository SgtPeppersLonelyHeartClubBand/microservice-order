**step1. mvn clean package**



**step 2. 
docker build -t customer-service -f customer-service/Dockerfile .
docker build -t order-service -f order-service/Dockerfile**


**step 3. 
docker run -p 8081:8081 customer-service
docker run -p 8082:8082 order-service**
