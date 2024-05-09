## 데이터 전처리 코드 (기준 Yolo 모델)

### manage_file.py
* 파일 목록 불러오기
* 파일 확장자 변경
* 파일 이름 일괄 변경
* 파일 옮기기
* 데이터 나누기 (원하는 폴더 개수에 맞게 나누기)
* 폴더 통합하기
* 비디오 프레임 저장

### manage_image.py
* 이미지 목록 불러오기
* 이미지 랜덤 샘플 인덱스 뽑기
* 특정 레이블 번호 일괄 변경
* 특정 레이블 삭제
* 각 이미지에서 N개수의 샘플 이미지 크롭하여 저장
* 각 이미지의 모든 박스를 크롭하여 레이블 별 폴더에 저장
* 박스 데이터 오류 체크
