# 개선 된 점
zookeeper, kafka 의존성 설정 ( 구동시 에러 방지, 원본 예제는 구동시 crash 가능 )
모든 서비스 컨테이너 구동
Gateway 프론트엔드 node 16 버전 명시 ( node 구버전 arm64 architecture 에러 해결 )

# 진행 중 중지
모든 서비스 컨테이너화
network_mode host
    h2 구동 에러
network 지정 or Links
    Kafka 127.0.0.1 하드코딩 부분 수정 필요