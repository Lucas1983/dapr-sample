# Run
* dapr run --app-id order-svc --dapr-http-port 4001 --app-port 3001 --config ./dapr.yaml ./gradlew bootRun
* dapr run --app-id gateway-svc --dapr-http-port 4000 --app-port 3000 --config ./dapr.yaml ./gradlew bootRun

# Test
* curl http://localhost:3000/orders/make