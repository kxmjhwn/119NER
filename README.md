# 119NER

#### **언어모델 기반 개체명 인식 기술을 활용한 119 신고 접수 도움 서비스로, 신고자의 음성 내용을 분석하여, [피해 장소], [피해 유형], [피해 인원]을 파악하여, 신고 접수 소방대원과 출동 소방대원에게 도움을 주는 것을 목표로 합니다.**

* 기간 : 2020.09 ~ 2020.12

* blog : https://kxmjhwn.tistory.com/239?category=1121129

* 주요 파일 설
  
    * KoBERT_NER_KMOU_for_119NER_(modified).ipynb : KoBERT 기반의 개체명 인식 모델을 구현하는 과정 및 코드가 작성된 파일
    
    * 119ner.py : main code가 작성된 파일 (ETRI 음성 인식 API, 구현된 개체명 인식 모델, 규칙 기반 모델)
    
    * rule_based_model.py : 소규모의 규칙 기반 모델이 작성된 파일
    
    * tokenization_kobert.py : KoBERT의 SentencePiece tokenization 기능이 작성된 파일
    
    * server : 웹 페이지 및 서버(localhost) 구현 파일
    
    * yomo.py : 서버와 연동되어 학습된 모델을 통해, 탐지 및 모자이크 처리를 진행하는 코드

