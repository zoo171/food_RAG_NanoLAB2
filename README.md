# food_RAG_NanoLAB2
건국대학교 3학년 2학기 나노 랩 심화 2 수업 기말고사 프로젝트
주제 : LangChain과 ChromaDB를 활용한 문서 검색 시스템 구축

한국 요리 데이터 셋을 활용한 


• 요리 이름 (CKG_NM): 각 요리의 이름 (예: 김치찌개, 불고기 등).

• 재료 설명 (CKG_MTRL_CN): 해당 요리에 필요한 재료의 목록 (예: 배추김치, 돼지고기, 고춧가루 등).

데이터셋 세부 사항
• 데이터셋은 약 200개의 요리와 그에 해당하는 재료를 포함하고 있습니다.
• pandas 라이브러리를 사용하여 CSV 데이터를 불러오고, 요리 이름과 재료 정보를 리스트로 분리하였습니다.

활용 임베딩 모델 : intfloat/multilingual-e5-large-instruct, snunlp/KR-BERT-char16424

두 임베딩 모델에 대한 비교 분석 과정 추가 진행

무료 레시피 데이터 셋 출처 : https://kadx.co.kr/opmk/frn/pmumkproductDetail/PMU_6d212747-8bd4-42c2-bc55-60bc636d6121/5
허깅페이스 임베딩 모델 : https://huggingface.co/intfloat/multilingual-e5-large-instruct
