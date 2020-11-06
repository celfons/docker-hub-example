# Docker Hub example
CRUD SpringBoot + Kotlin + Docker


POST
curl --location --request POST 'http://localhost:8080/kuadra/order/' \
--header 'Content-Type: application/json' \
--data-raw '{
    "customerId": {customerId}
}'

PATCH
curl --location --request PATCH 'http://localhost:8080/kuadra/order/{orderId}' \
--header 'Content-Type: application/json' \
--data-raw '{
    "customerId": {customerId}
}'

GET
curl --location --request GET 'http://localhost:8080/kuadra/order/{orderId}' \
--header 'Content-Type: application/json' \

DELETE
curl --location --request DELETE 'http://localhost:8080/kuadra/order/{orderId}' \
--header 'Content-Type: application/json' \
