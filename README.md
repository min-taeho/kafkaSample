# kafkaSample

# 스프링부트와 카프카 연동 샘플 어플리케이션

application.proeprties에 Producer와 Consumer 설정을 하고
KafkaProducer 서비스와 KafkaConsumer 서비스를 통해 Kafka와 메시지를 주고 받습니다.

application.properties를 통해 설정을 함으로서 설정을 1개만 관리 할 수 있다.
여러 개 설정을 관리하려면 Bean으로 구현해야 한다.

테스트를 위해 별도 서버에 Kafka 서버를 설치 해야 합니다. 

[<a href="https://velog.io/@taehodot/SpringBoot-%EC%B9%B4%ED%94%84%EC%B9%B4%EC%99%80-%EC%8A%A4%ED%94%84%EB%A7%81%EB%B6%80%ED%8A%B8-%EC%97%B0%EB%8F%99" target="_blank">카프카와 스프링부트 연동</a>]
