Clone zipkin server: https://github.com/openzipkin/zipkin/
b1: mở terminal file mới clone
b2: chạy lệnh: ./mvnw -DskipTests --also-make -pl zipkin-server clean install (chờ build)
b3: chạy lệnh: java -jar ./zipkin-server/target/zipkin-server-*exec.jar (chạy xong có thể sử dụng)
