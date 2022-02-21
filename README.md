# KoBERTopic
## 소개
KoBERTopic은 BERTopic을 한국어 데이터에 적용할 수 있도록 토크나이저와 BERT를 수정했습니다.

* 기존 BERTopic : https://github.com/MaartenGr/BERTopic/tree/05a6790b21009d1704e912e0d9ae22290694cfed
* 토크나이저로는 형태소 분석기 Mecab을 사용.
* BERT로는 다국어 SBERT인 'sentence-transformers/xlm-r-100langs-bert-base-nli-stsb-mean-tokens'를 사용.
* 토픽의 수는 임의로 50으로 결정.
* 별도 불용어 제거 등의 추가 전처리는 진행하지 않았음. (진행할 경우 더 좋은 결과를 얻을 수 있을 것으로 기대.)
