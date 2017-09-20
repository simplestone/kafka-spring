# kafka spring example

## 실행
### 스프링 부트 실행
선행으로 브로커 실행
```
# kafka home 디렉토리로 이동.
$ bin/zookeeper-server-start.sh -daemon config/zookeeper.properties
$ bin/kafka-topics.sh -create -zookeeper localhost:2181 -replication-factor 1 -partitions 1 -topic myTopic
```
IDE에서 main class를 선택후 실행
- CommandLine.class : profile - commandline
  
### 스프링 부트 테스트 실행
- KafkaDemoApplicationTest

## 참고
- https://docs.spring.io/spring-kafka/reference/htmlsingle/
- https://www.codenotfound.com/spring-kafka-consumer-producer-example.html

