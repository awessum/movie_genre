### movie_genre
genre_prediction 파일에 있는 코드를 처음부터 실행해서 마지막 코드를 실행하면 장르가 예측됩니다.

poster / writing / review 순으로 가지고 와서 세가지를 합친 것을 실행시켜 장르가 예측되도록 합니다. 

(3가지 네트워크 결과의 평균을 기준으로 2가지 장르가 예측됩니다.)

코드를 실행하기 위한 파일들을 첨부합니다

ocr_data : ocr로 추출한 글귀들을 장르별로 구분하여 모아둔 파일

poster_model.h5 : cnn으로 학습된 poster 모델

review_model : nlp word2vec으로 학습된 review 모델

train_df2 : 영화 데이터 장르별로 구분한 파일

word : 썸트렌드에서 크롤링한 장르별 단어 리스트 파일
