for example :
python resize.py -d image -s 800 600

python resize.py -d 폴더이름 -s 폭 넓이

파이썬 이미지 크기 변환 

파이썬 이미지 리사이징

파이썬 이미지 리사이즈 

이미지 데이터 늘리기 generateIMG.py

python generateIMG.py -d 이미지가_들어있는_폴더 -s 생성된_이미지가_


rotation_range = 90

지정된 각도 범위내에서 임의로 원본이미지를 회전시킵니다. 단위는 도이며, 정수형입니다. 예를 들어 90이라면 0도에서 90도 사이에 임의의 각도로 회전시킵니다. 

width_shift_range = 0.1

지정된 수평방향 이동 범위내에서 임의로 원본이미지를 이동시킵니다. 수치는 전체 넓이의 비율(실수)로 나타냅니다. 예를 들어 0.1이고 전체 넓이가 100이면, 10픽셀 내외로 좌우 이동시킵니다. 

height_shift_range = 0.1

지정된 수직방향 이동 범위내에서 임의로 원본이미지를 이동시킵니다. 수치는 전체 높이의 비율(실수)로 나타냅니다. 예를 들어 0.1이고 전체 높이가 100이면, 10픽셀 내외로 상하 이동시킵니다. 

shear_range = 0.5

밀림 강도 범위내에서 임의로 원본이미지를 변형시킵니다. 수치는 시계반대방향으로 밀림 강도를 라디안으로 나타냅니다. 예를 들어 0.5이라면, 0.5 라이안내외로 시계반대방향으로 변형시킵니다. 

zoom_range = 0.3

지정된 확대/축소 범위내에서 임의로 원본이미지를 확대/축소합니다. “1-수치”부터 “1+수치”사이 범위로 확대/축소를 합니다. 예를 들어 0.3이라면, 0.7배에서 1.3배 크기 변화를 시킵니다. 

horizontal_flip = True

수평방향으로 뒤집기를 합니다. 

vertical_flip = True

수직방향으로 뒤집기를 합니다.

