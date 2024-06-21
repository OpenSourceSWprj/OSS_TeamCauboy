# 자기소개서 작성 도우미

프로젝트 설명: 이 프로젝트는 자기소개서 작성에 어려움을 겪는 사람들을 위해 GPT를 활용하여 자기소개서의 초안을 작성하고, 기존 합격 자기소개서와 비교하여 개선된 문장을 제안하는 도우미입니다.

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

## 목차
- [프로젝트 소개](#프로젝트-소개)
- [설치](#설치)
- [사용법](#사용법)
- [기여](#기여)
- [라이선스](#라이선스)

## 프로젝트 소개

이 프로젝트는 다음과 같은 문제를 해결하고자 합니다:
1. **기본적인 구조와 흐름을 잡기 어려움**: 처음 자기소개서를 작성할 때 막막함을 느끼는 경우.
2. **시간 소요**: 글을 쓰는 데 시간이 많이 걸림.
3. **자신의 특징을 글에 녹이기 어려움**: 자신의 특징을 객관적으로 파악하고 글로 풀어내기 어려움.

프로젝트의 주요 기능:
- **자기소개서 질문과 키워드 조합**: 사용자가 작성하고 싶은 내용의 키워드를 조합하여 GPT가 자기소개서의 대략적인 구조와 흐름을 작성합니다.
  
  ![키워드와 질문 조합](path/to/image1.png)

- **합격 자기소개서 크롤링**: 합격 자기소개서를 모아놓은 사이트를 크롤링하여, GPT가 작성한 내용과 유사도를 비교 후 출력합니다.
  
  ![크롤링](path/to/image2.png)

- **키워드 추천**: 높은 유사도를 가진 합격 자소서 문장의 텍스트를 추출하여 사용자가 떠올리지 못한 키워드를 추가로 추천합니다.
  
  ![키워드 추천](path/to/image3.png)

- **시각적 확인**: 사용자가 입력한 키워드의 내용은 GPT가 출력하는 중괄호 안에 반영되어 있음을 시각적으로 확인할 수 있습니다.
  
  ![시각적 확인](path/to/image4.png)

## 사용 시나리오

1. **Step 1**: 자기소개서의 질문 하나를 입력합니다.
   
   ![Step 1](path/to/image5.png)

2. **Step 2**: 해당 질문에 대해 쓰고 싶은 키워드를 입력하고 제출합니다.
   
   ![Step 2](path/to/image6.png)

3. **Step 3**: 사용자가 입력한 키워드 및 추가된 키워드에 대해 보충하고 싶은 내용을 작성합니다. 답변을 작성하기 힘든 경우 다음 버튼을 통해 넘어갈 수 있습니다.
   
   ![Step 3](path/to/image7.png)

4. **Step 4**: 사용자가 입력한 답변을 기반으로 크롤링한 합격 자소서와 비교하여 GPT가 문장을 생성합니다.
   
   ![Step 4](path/to/image8.png)

## 설치

프로젝트를 설치하려면 다음 명령어를 사용하세요:

```bash
git clone https://github.com/yourusername/yourproject.git
cd yourproject
npm install
