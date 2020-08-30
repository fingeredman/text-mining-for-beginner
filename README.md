# TEXT MINING for BEGINNER
> 본 자료는 텍스트 마이닝(text mining)을 처음 공부하는 분들을 대상으로 프로그래밍 언어에 대한 장벽을 최대한 낮추어 접근할 수 있도록 작성되었습니다. 텍스트 마이닝은 자연어처리(natural language processing, NLP) 기술에 기반해 대량의 텍스트 데이터에서 유의미한 패턴을 찾아내는 과정으로 다양한 실무/연구 분야에서 활용되고 있습니다. 하지만 텍스트 마이닝에 대한 관심에 비해 쉽게 접근하고 공부할 수 있는 자료가 매우 부족합니다. 본 자료를 통해 텍스트 마이닝을 위한 Python 문법에서 출발하여 텍스트 데이터를 수집하고 처리하는 방법에 대해 직관적인 이해를 돕고자 합니다. 최대한 주석을 꼼꼼하게 읽으시면서 Python 코드의 의미를 이해하시길 권장드리며, 다른 자료와 함께 공부하시면 이해하는 데 도움이 되실 거라고 생각합니다.

- 본 자료는 텍스트 마이닝을 활용한 연구 및 강의를 위한 목적으로 제작되었습니다.
- 본 자료를 강의 목적으로 활용하고자 하시는 경우 꼭 아래 메일주소로 연락주세요.
- 본 자료에 대한 허가되지 않은 배포를 금지합니다.
- 강의, 저작권, 출판, 특허, 공동저자에 관련해서는 문의 바랍니다.
- **Contact : ADMIN(admin@teanaps.com)**

---
## Notice!
> - 강의자료 및 실습자료가 2020년 8월 31일 새로운  업데이트되었습니다.
> - 본 자료는 2018~2019년도 `패스트캠퍼스 <텍스트 분석 유치원>` 강의자료로 활용되었습니다.

---
## Curriculum

### 이론 (lecture-note)
- Part 1. 텍스트 마이닝 개요
- Part 2. 텍스트 마이닝 활용사례
- Part 3. 텍스트 마이닝 프로세스: 수집, 전처리, 분석, 그리고 시각화

### 실습 (practice-note)
> ### Part 1. Python 기초
- DAY 01. Python 기초문법 알아보기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-beginner/blob/master/practice-note/01_text-mining-for-beginner_python-basic.ipynb)
- DAY 02. Python 자료구조 이해하기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-beginner/blob/master/practice-note/02_text-mining-for-beginner_python-data-structure.ipynb)
- DAY 03. Python 조건문과 반복문 다루기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-beginner/blob/master/practice-note/03_text-mining-for-beginner_python-conditional%26loop.ipynb)
- DAY 04. Python 함수와 파일 만들고 호출하기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-beginner/blob/master/practice-note/04_text-mining-for-beginner_python-function%26file.ipynb)

> ### Part 2. Python을 활용한 데이터 수집
- DAY 05. 데이터 크롤링 원리 이해하기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-beginner/blob/master/practice-note/05_text-mining-for-beginner_python-crawling-intro.ipynb)
- DAY 06. 정적 페이지 수집하기: 실시간검색어, 영화댓글 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-beginner/blob/master/practice-note/06_text-mining-for-beginner_python-crawling-practice-1.ipynb)
- DAY 07. 동적 페이지 수집하기: 네이버 카페 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-beginner/blob/master/practice-note/07_text-mining-for-beginner_python-crawling-practice-2.ipynb)
- DAY 08. 동적 페이지 수집하기: 인스타그램 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-beginner/blob/master/practice-note/08_text-mining-for-beginner_python-crawling-practice-3.ipynb)

> ### Part 3. Python을 활용한 텍스트 분석
- DAY 09. 한국어 텍스트 전처리 실습하기: KoNLPy [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-beginner/blob/master/practice-note/09_text-mining-for-beginner_python-korean-nlp.ipynb)
- DAY 10. 영어 텍스트 전처리 실습하기: NLTK [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-beginner/blob/master/practice-note/10_text-mining-for-beginner_python-english-nlp.ipynb)
- DAY 11. 실전 텍스트 분석하기: 단어빈도분석, 연관단어분석 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-beginner/blob/master/practice-note/11_text-mining-for-beginner_python-text-analysis-1.ipynb)
- DAY 12. 실전 텍스트 분석하기: LDA토픽모델링, 감성분석 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-beginner/blob/master/practice-note/12_text-mining-for-beginner_python-text-analysis-2.ipynb)

> ### Appendix. 참고자료
- APPENDIX 01. 텍스트 분석을 위한 Python 분석환경 설치하기
- APPENDIX 02. Assignment: 영화댓글 수집기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-beginner/blob/master/practice-note/text-mining-for-beginner-appendix2.ipynb)
---
## References
> 본 강의자료는 아래 문헌들을 참고해 구성되었습니다.
- A Byte of Python [(Link)](https://python.swaroopch.com/)
- 패스트캠퍼스 <텍스트 분석 유치원 1기~5기> [(Link)](https://www.fastcampus.co.kr/data_class_textmining/)

---
## Update History
> 2019.08.31. Part 1\~3 강의자료 업데이트  
2019.06.12. Part 1\~2 강의자료 업로드  
2019.06.11. DAY 12 실습자료, 실습 데이터 업로드  
2019.06.10. DAY 11 실습자료 업로드  
2019.06.09. DAY 10 실습자료 업로드  
2019.06.08. DAY 09 실습자료 업로드  
2019.06.07. APPENDIX 01 업로드  
2019.06.06. DAY 08 실습자료 업로드  
2019.06.05. DAY 07 실습자료 업로드  
2019.06.04. DAY 05\~06 실습자료, APPENDIX 02 업로드  
2019.06.03. DAY 03\~04 실습자료 업로드  
2019.06.02. DAY 01\~02 실습자료 업로드  
2019.06.01. 목차 구성 입력  

<br><br>
---
<center>ⓒ 2020. FINGEREDMAN all rights reserved.</center>
