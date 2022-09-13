# 졸음 운전 진단 시스템

### Cap_MyFace
* 웹캠으로 사진을 찍는 ipynp 파일입니다.
* 경로를 설정해 주어야 합니다.

### Make_DataSet
* 데이터셋을 만드는 ipynp 파일입니다.
* pose/train/의 drowsy, not drowsy에 사진을 넣으면 데이터셋이 만들어집니다.
* train과 test에 들어있는 img는 임시로 넣은 이미지로 데이터를 직접 만들어서 사용하실 때는 지우고 하셔야 합니다.

### Check_Drowsy_Driving
* 웹캠으로 졸음운전을 감지(자세 기반)하는 ipynp 파일입니다.
* 데이터셋을 만들지 않아도 기본적으로 제공되는 데이터셋이 있습니다(data)
