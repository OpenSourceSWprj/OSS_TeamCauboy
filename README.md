# <h1>🧑‍🏫 Interviewer Mr. G
<br>

Chung Ang University 2024 Spring Semester Open Source Software Project  

Team : **HanJeongHongLee**  

<br>
<br>

# <a href="https://www.youtube.com/watch?v=6JUicG0729g&t=4210s" target="_blank">YouTube Video</a>

<br>
<br>

# <a href="https://github.com/OpenSourceSWprj/OSS_Team15" target="_blank">Github Repository</a>

<br>
<br>
<br>
<br>

# 자기소개서 작성 도우미


**이 프로젝트는 자기소개서 작성에 어려움을 겪는 사람들을 위해 설계된 혁신적인 도구입니다.**  
인공지능 **GPT**를 활용하여 자기소개서의 초안을 자동으로 생성하고,  
기존 합격 자기소개서와의 비교를 통해 **보다 완성도 높은 문장**을 제안합니다.  
이를 통해 사용자들이 자신의 강점과 경험을 **효과적으로 표현**할 수 있도록 돕습니다.

특히, 사용자가 생각지 못했던 키워드를 합격 자기소개서에서 추출하여 제안함으로써 **보다 폭넓고 깊이 있는 자기소개서**를 작성할 수 있도록 지원합니다.  
또한, **사용자 인터랙션 기반**으로 작동하기 때문에 개인의 **독창적인 특징과 개성**을 반영할 수 있는 장점을 제공합니다.



![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

<br>
<br>
<br>
<br>

# 목차


## ℹ️ [Project Overview](#project-overview)  
<br>

## 🔑 [Usage Scenarios](#usage-scenarios)  
<br>

## 🤝 [Contribution Highlights](#contribution-highlights)  
<br>

## 📜 [License](#license)  
<br>

## 👥 [Contributors](#contributors)  

<br>
<br>
<br>
<br>


<a name="project-overview"></a>

## ℹ️ Project Overview


이 프로젝트는 다음과 같은 문제를 해결하고자 합니다:
1. **기본적인 구조와 흐름을 잡기 어려움**: 처음 자기소개서를 작성할 때 막막함을 느끼는 경우.
2. **시간 소요**: 글을 쓰는 데 시간이 많이 걸림.
3. **자신의 특징을 글에 녹이기 어려움**: 자신의 특징을 객관적으로 파악하고 글로 풀어내기 어려움.


프로젝트의 주요 기능:
- **자기소개서 질문과 키워드 조합**: 사용자가 작성하고 싶은 내용의 키워드를 조합하여 GPT가 자기소개서의 대략적인 구조와 흐름을 작성합니다.
- **합격 자기소개서 크롤링**: 합격 자기소개서를 모아놓은 사이트를 크롤링하여, GPT가 작성한 내용과 유사도를 비교 후 출력합니다.
- **키워드 추천**: 높은 유사도를 가진 합격 자소서 문장의 텍스트를 추출하여 사용자가 떠올리지 못한 키워드를 추가로 추천합니다.
- **시각적 확인**: 사용자가 입력한 키워드의 내용은 GPT가 출력하는 중괄호 안에 반영되어 있음을 시각적으로 확인할 수 있습니다.

<br>
<br>
<br>
<br>

<a name="usage-scenarios"></a>

## 🔑 Usage Scenarios  

# Interviewer Mr. G 페이지 접속
<br>
<br>

<img width="1106" alt="image" src="https://github.com/OpenSourceSWprj/OSS_Team15/assets/132530028/19189250-4f2a-405e-8619-a6fc1e57d20d">

<br>
<br>

# Keyword & Statement 입력
<br>
<br>

![image](https://github.com/OpenSourceSWprj/OSS_Team15/assets/164728750/ecbc0d96-d428-461d-8354-f77ccd7f47e7)

<br>
<br>

# New Keyword 사용자 답변 입력
<br>
<br>

![image](https://github.com/OpenSourceSWprj/OSS_Team15/assets/164728750/6ddd2885-b83d-4d78-afa2-e616b12f46cd)

<br>
<br>

# Interviewer Mr. G 답변 생성
<br>
<br>

![image](https://github.com/OpenSourceSWprj/OSS_Team15/assets/164728750/e92322be-ecda-45fa-8ac2-0af2697ba993) 

<br>
<br>

# Moderation Detect
<br>
<br>

![image](https://github.com/OpenSourceSWprj/OSS_Team15/assets/164728750/c02e7908-569e-47a4-99a6-d75c02cf4fdc)

![image](https://github.com/OpenSourceSWprj/OSS_Team15/assets/164728750/51eb4080-7f07-4768-ad8f-a69591e2fc02)

<br>
<br>
<br>
<br>
<br>


<a name="contribution-highlights"></a>

## 🤝 Contribution Highlights

  
### 1. 크롤링 및 데이터 수집
- **목적:** 합격 자기소개서 텍스트 데이터를 수집하여 분석할 수 있는 데이터셋을 확보
- **방법:** 링크 커리어 사이트에 접근하여 사용자가 업로드한 합격 자기소개서 텍스트 데이터를 크롤링하는 웹 크롤러 개발
- **결과:** AI 모델의 학습 및 평가에 필요한 강력한 합격 자기소개서 데이터셋을 확보

### 2. 데이터 처리 및 임베딩
- **목적:** 수집된 텍스트 데이터를 AI 모델이 처리할 수 있는 형식으로 변환
- **방법:** 크롤링한 텍스트 데이터를 바탕으로 임베딩 벡터를 생성하고, 이를 자기소개서가 위치한 URL에 매핑하여 데이터베이스에 저장
- **결과:** 텍스트 데이터를 벡터화하여 데이터베이스에 저장함으로써 효율적인 검색 및 유사도 비교가 가능

### 3. 질문 및 키워드 비교
- **목적:** 사용자 입력에 대한 적절한 피드백 제공
- **방법:** 사용자가 입력한 질문과 키워드를 벡터화하고, 데이터베이스에 저장된 벡터들과 유사도를 비교하여 가장 높은 유사도를 가진 URL을 가져옴
- **결과:** 사용자가 입력한 질문과 키워드와 가장 유사한 합격 자기소개서를 제공하여 보다 나은 자기소개서 작성 지원

### 4. 추가 키워드 제시
- **목적:** 사용자가 생각하지 못한 중요한 키워드를 제공하여 자기소개서의 완성도 향상
- **방법:** 크롤링한 합격 자기소개서 텍스트를 분석하고, 가장 유사도가 높은 키워드를 순서대로 정리하여 사용자가 입력하지 않은 추가적인 키워드 제시
- **결과:** 사용자가 놓칠 수 있는 중요한 키워드를 제시하여 자기소개서의 품질을 높임

### 5. 부적절한 입력 감지
- **목적:** 사용자 입력의 정확성을 보장하고, 부적절한 입력을 방지
- **방법:** 자기소개서 질문과 키워드에 부적절한 입력이 감지될 경우 경고 창 출력
- **결과:** 사용자에게 올바른 입력을 유도하여 서비스의 신뢰성 및 사용성을 향상

위와 같은 기여를 통해 프로젝트의 기능성과 사용자 만족도를 크게 향상시킬 수 있었습니다.
  
<br>
<br>
<br>
<br>

<a name="license"></a>

## 📜 License
This project is licensed under the terms of the Creative Commons Attribution-NonCommercial 4.0 International License.
This license allows for non-commercial use only and requires attribution to the original authors.

<br>
<br>
<br>
<br>

<a name="contributors"></a>

## 👥Contributors
| [![텍스트](/Profile/Han.png)](https://github.com/easthee) | [![텍스트](/Profile/Jeong.png)](https://github.com/9hon9) | [![텍스트](/Profile/Hong.png)](https://github.com/StoneCAU)| [![텍스트](/Profile/Lee.png)](https://github.com/woohoosupernewuser1)  |
|:---:|:---:|:---:|:---:|
| 한동희 | 정구홍 | 홍석우 | 이호진 |
