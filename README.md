# helmet_detection

face detection으로 pretrained 된 yolov3모델을 이용하여 frame내 face들을 detect하여 crop
crop된 image를 헬멧 착용 유무로 학습시킨 GoolgeNet모델에 predict하여 frame마다 헬멧착용 여부 검출

-- 원래는 Yolo모델 localization + Classification을 통해 얼굴 검출 및 헬멧 착용 여부까지 한 모델로 진행할 수 있지만
   모델 사용 경험을 위해 구분지어 진행해보았음

pretrained yolov3 face detection implement
yolo관련 자료 : https://github.com/sthanhng/yoloface
-- cfg, weight 파일 등은 위 github에서 다운로드 해야함
