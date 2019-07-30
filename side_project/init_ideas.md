# 7월 22일에 정한 Side Project의 초기 아이디어를 작성합니다.

## 유재혁
## 장형기
- OpenCV에 내장되어있는 여러가지 feature 모듈들과 tracking 모듈을 적절히 조합해서, 간단한 SLAM 또는 Mapping 프로그램을 만들기.
  - eigen, ceres 등 외부 라이브러리도 사용을 고려함.
![image](https://github.com/ai-robotics-kr/opencv_study/blob/master/side_project/orb_slam.png?raw=true)

## 김경찬
- 실시간으로 카메라에 비춰지는 얼굴의 영상으로부터 사용자가 누구인지를 인식할 수 있는 프로그램을 만들기.
- 단순히 내장된 Haar feature based cascade classifier 을 사용하지 않고, 기왕이면 ml을 활용해서 성능을 높이는 방식을 활용할 것.

## 전현우
- 파이캠의 비춰지는 영상으로 부터 개발자 얼굴과 비교하는 실시간 얼굴인식 프로그램 만들기.
- 하드웨어 구성 : 라즈베리파이4, 카메라모듈, 스피커폰사용 
- DB Server 카메라 모듈에서 검출된 사진 저장. (구축 고려)
- 안드로이드 : Googel WebRTC API 를 사용하여 영상확인. Toast.makeText, Vibrator 등의 알림 메세지 사용
