## Drone 낙하 시스템
![alt text](/DroneRelease/image/DroneRelease2.jpg "Drone Release")

```
드론으로 참치를 잡는 동영상이 유행이었다.
참치는 공대형들에게 무리고 일단 캐스팅을 정확히 할 수 있는 방법이 필요했다.
드론으로 정확한 위치에 캐스팅을 할 수 있어야 했다.
```
### Drone 낙하 시스템 개요
![alt text](/DroneRelease/image/DroneRelease-sketch.jpg "Drone Release")

3d 프린터를 이용하여 구조부를 만들었고 소형 서보 모터와 RC 수신기 + 배터리 그리고 RC 송신기를 이용하여 구현하였다.(송수신기는 Spektrum 사의 것을 사용)

무선 통신을 널리 쓰고 있지만 실제 명령을 내려 동작을 수행하는 시스템을 가장 쉽게 만들 수 있는 방법은 RC 무선 모듈을 이용하는 것이다. 무선 통신으로 데이터를 주고 받을 때 인코딩 + 에러체크를 하지 않으면 제대로 무선통신이 되기 힘들다. 이 두 부분을 빠른 시간에 구현하기도 쉽지 않기때문에 DIY 상황에서 RC 시스템이 최적인 경우가 많다.

#### 발전 가능한 부분
1. 드론 릴리즈 시스템에 핀과 서보를 연결하는 부위가 현재 낚시줄인데 이걸 좀더 단단한 소재로 바꾸자. 지금은 잘못하면 핀이 빠지지 않는다.
2. RC 송수신기를 연결하면 시스템이 커지지 커스텀 무선 통신 시스템으로 소형화 해보자.

#### 파일 살펴보기
- 3d 폴더: 3d 프린터로 인쇄가능한 .stl 파일
- image 폴더: 각종 참조 사진 들

#### 사용된 기술들
[공대형 낚시 편 Wiki 가서 확인!](https://github.com/gradefree-eng/Fishing/wiki/F%ED%95%99%EC%A0%90-%EA%B3%B5%EB%8C%80%ED%98%95-%EB%82%9A%EC%8B%9C%ED%8E%B8-%EC%9C%84%ED%82%A4)
