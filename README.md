# ParkingStation
> 공간을 새롭게 정의하는 USPACE 주차장의 데모 모델 DPS(Dynamic Parking Station)의 레포지토리 입니다.

USPACE는 스마트 주차장을 목적으로 공간을 더욱 동적으로 사용할수 있도록 하는 솔루션입니다. DPS는 USPACE의 기능을 시현 가능한 데모 모델으로 6X6의 주차 구역을 제작하여 차량의 출입, 주차, 반응 등의 환경을 제어합니다. 

이 레포지토리에는 DPS에 사용되는 아두이노 코드와 Aruco Marker Detection등의 코드가 저장 되어 있습니다. 추가로 후속 개발을 위한 개발 코드도 업로드 되어 있습니다. 자세한 코드는 src 폴더에서 확인해주세요.

## 재원

- Neopixel LED Strap
- MDF 합판
- Nvidia Jetson Nano
- Arduino Mega
- ZED2 stereo camera

## 적용기술

- OpenCV Aruco Marker
- 차량 번화판 인식
- Object Detection, model YOLO v4
- NeoPixel sector 피드백
