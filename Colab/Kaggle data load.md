# GCS (Google Cloud Storage) PATH 이용
## 1. Kaggle에서 GCS PATH 복사
1. 불러올 데이터가 있는 competetion에서 노트북 open, Add data
2. 다음 코드 입력
  from kaggle_datasets import KaggleDatasets
  GCS_DS_PATH = KaggleDatasets().get_gcs_path('[데이터셋 이름]')
  print(GCS_DS_PATH)
3. 출력 결과 ('gs://~' 형태) 복사

## 2. Colab Notebook
