docker-compose up

■build
cd javaproject
mvn package

java --version
mvn -version

https://qiita.com/mfunaki/items/dc09764cb08bb787c261
https://qiita.com/makoxti/questions/195ae6dd67ad7bdf164c

docker-compose exec app bash
cd pictgram
./mvnw clean install
./mvnw spring-boot:run