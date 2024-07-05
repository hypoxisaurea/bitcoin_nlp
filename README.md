# bitcoin_nlp

### ver1
- Doc2Vec, DBSCAN 사용<br/>
- GridSearch를 사용한 파라미터 최적화<br/>
- 빈도수를 이용한 불용어 250개를 추출하여 사용<br/>
- Best DBSCAN params: eps=2.0, min_samples=4 with Silhouette Score=-0.13176951229558614<br/>
Number of clusters: 4<br/>
Number of noise points: 1210<br/><br/>

### ver2
- Doc2Vec, DBSCAN 사용<br/>
- GridSearch를 사용한 파라미터 최적화<br/>
- nltk english 불용어 사용<br/>
- Best DBSCAN params: eps=1.9000000000000001, min_samples=4 with Silhouette Score=-0.13805872132578131<br/>
Number of clusters: 3<br/>
Number of noise points: 1245<br/><br/>

### ver3
- Doc2Vec, DBSCAN 사용<br/>
- GridSearch를 사용한 파라미터 최적화<br/>
- 빈도수를 이용한 불용어 250개를 추출하여 사용<br/>
- Best DBSCAN params: eps=2.0, min_samples=4 with Silhouette Score=-0.12577107405301016<br/>
Number of clusters: 3<br/>
Number of noise points: 1207<br/><br/>

### ver4
- DBSCAN 사용<br/>
- GridSearch를 사용한 파라미터 최적화<br/>
- 빈도수를 이용한 불용어 250개를 추출하여 사용<br/>
- 문서의 최빈 어휘 100개를 추출하여 벡터화한 것을 클러스터링<br/>
- ver1과 비교하여 클러스터의 갯수와 노이즈 포인트의 갯수 모두 증가, 실루엣 스코어 미세하게 하락<br/>
- Best DBSCAN params: eps=0.1, min_samples=2 with Silhouette Score=-0.19123197729214664<br/>
Number of clusters: 32<br/>
Number of noise points: 1242<br/><br/>

### ver5
- DBSCAN 사용<br/>
- GridSearch를 사용한 파라미터 최적화<br/>
- nltk 영어 불용어, 빈도수를 이용한 불용어 250개를 추출하여 사용<br/>
- 문서의 최빈 어휘 100개를 추출하여 벡터화한 것을 클러스터링<br/>
- ver1과 비교하여 클러스터의 갯수와 노이즈 포인트의 갯수 모두 증가, 실루엣 스코어 미세하게 하락<br/>
- Best DBSCAN params: eps=0.1, min_samples=2 with Silhouette Score=-0.1922023335730142<br/>
Number of clusters: 32<br/>
Number of noise points: 1242<br/><br/>

### ver6
- Doc2Vec, DBSCAN 사용<br/>
- GridSearch를 사용한 파라미터 최적화<br/>
- nltk 영어 불용어, 빈도수를 이용한 불용어 250개를 추출하여 사용<br/>
- ver1과 비교하여 클러스터 갯수 유지, 노이즈 포인트 감소 실루엣 스코어 미세하게 상승<br/>
- Best DBSCAN params: eps=2.0, min_samples=4 with Silhouette Score=-0.08230538796258437<br/>
Number of clusters: 4<br/>
Number of noise points: 1084<br/><br/>
