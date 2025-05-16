# 👁️‍🗨️ Team: Observer

# 🎮 Project Name: Perfect pose

# 👥 Project Member

| 이름 | 역할 | GitHub ID | 비고 |
|------|------|-----------|------|
| 홍훈의 | 팀장 | [@HuniGit](https://github.com/HuniGit) | 총괄 PM |
| 오경택 | 부팀장 | [@GyeongtaekOh0207](https://github.com/GyeongtaekOh0207) | AI |
| 임정환 | 팀원 | [@HALIMIE](https://github.com/HALIMIE) | AI |
| 조정호 | 팀원 | [@jjh9708](https://github.com/jjh9708) | AI |


# 필요 기술
 - CAN, OPENPOSE

# 개요
Open pose 라는 AI모델을 사용

웹카메라를 통해, 사용자의 모션을 인식한다.

사진을 촬영한 후, 몇 초의 시간동안 사용자가 포즈를 취하면,특정한 위치마다 좌표가 생성된다.

좌표에 대한 정보를 Linux OS 로컬 컴퓨터와, 웹 카메라, STM32 보드와 Analog Buzzer 및 LED를 CAN 모듈로 연결

캡쳐된 포즈를 벗어나면, Buzzer가 울리면서, LED 불 점등
