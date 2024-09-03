# Naver_Shopping_Crawler

Meta Crawler : naver shopping site의 네이버페이 상품 기준 meta data 수집 (상품 url, brand 및 item명, 가격 등)
Image Crawler : naver shopping site의 네이버페이 상품 기준 상세페이지 이미지 데이터 수집
* 상품별 이미지 수집 및 로컬 폴더 저장
* 저장된 이미지 pdf 병합 후 s3 업로드
Review Crawler : naver shopping site의 네이버페이 상품 기준 최근6개월 리뷰 데이터 수집 & 리뷰 첫 페이지의 소비자 이미지 리뷰 수집
upload_data_to_s3 : 수집된 데이터를 S3에 저장
