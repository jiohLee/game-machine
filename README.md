# 3학년 1학기 마이크로프세서 ARM 프로젝트

개요: 휴대용 벽돌깨기 게임기 개발 및 Firmware 구현

### 주요 요소
* MCU(Cortex-M3, stm32f103c8t6, bluepill) 사용
* 자이로센서(MPU6050, I2C), 플레이어가 게임기를 기울여 공을 튀기기 위한 발판을 제어
* MP3모듈(DFPlayer mini, GPIO) 및 스피커, 플레이 시 BGM 재생
* 게임 시작/종료 버튼(GPIO)
* 주요 회로 구성 및 전원부 납땜
