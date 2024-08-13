


# Talksum

<div align = "center">
<img width="700" alt="image" src="https://github.com/junhaa/study/blob/main/image/project/talksum/talksumLogo.png?raw=true">
</div>

<br>

<div align = center>
<b>인공지능을 활용한 스마트 요약 시스템, talksum</b>
</div>



## 팀원 소개

<br>

> **한성대학교 공학경진대회**
> <br>
> **개발기간: 2023.07 ~ 2023.09**

<br>

|                                        이나경                                        |                                        김진하                                        |                                       김준하                                       | 박지원                                                                              |
| :-------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------: | :--------------------------------------------------------------------------------: |
| <img width="160px" src="https://avatars.githubusercontent.com/u/115490634?v=4" /> | <img width="160px" src="https://avatars.githubusercontent.com/u/121429925?v=4" /> | <img width="160px" src="https://avatars.githubusercontent.com/u/94986147?v=4"/> | <img width="160px" src="https://avatars.githubusercontent.com/u/113771563?v=4"/> |
|                  [@Na.\_.kyung](https://github.com/lee-nakyung)                   |                    [@Jinha Kim](https://github.com/ghvfgfcht)                     |                      [@junhaa](https://github.com/junhaa)                       |               [@Jiwon_Park](https://github.com/hs-1971342-jiwonpark)             |
|                                     프론트엔드 개발                                      |                                     백엔드 서버 개발                                     |                                    백엔드 서버 개발                                    |안드로이드 개발|

<br>

## 프로젝트 소개
<br>
톡썸(Talksum)은 사용자가 요약을 원하는 영상 혹은 음성 데이터를 입력하면 실시간으로 처리하여 자동 알고리즘을 통해 주요 키워드와 함께 텍스트 형식의 요약본을 제공해주는 서비스입니다. 오디오 녹음 파일, 회의록, 학교 강의, 뉴스 등 다양한 데이터 포맷의 데이터를 손 쉽게 요약할 수 있으며, 다국어 지원으로 언어 제한 없이 사용할 수 있는 스마트 요약 시스템입니다.

<br>

## 주요 기능 


### ✅ 영상 혹은 음성 데이터를 자동으로 요약
- STT모델을 이용하여 음성 데이터를 글로 변환
- 글로 변환된 음성 데이터를 LLM 모델을 이용하여 중요한 내용에 맞추어 요약

### ✅ 다양한 음성 데이터 포맷 지원
- 대부분의 음성 데이터 포맷을 글로 요약 가능
- 음성 데이터가 아닌 Youtube의 링크로도 음성 데이터 업로드 가능

### ✅ 요약 결과 데이터 저장
* 사용자 별 요약 결과 데이터를 저장, 수정, 삭제 가능


## 구현 화면

|                                                            메인 페이지                                                             |                                                        요약 노트 목록 페이지                                                         |
| :---------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------: |
| <img width="400" alt="image" src="https://github.com/junhaa/study/blob/main/image/project/talksum/talksum_main.png?raw=true"> | <br><img width="500" src="https://github.com/junhaa/study/blob/main/image/project/talksum/talksum_note_page.png?raw=true"/> |
|                                                        노트 생성 페이지(업로드)                                                         |                                                          요약 노트 페이지                                                          | <br>
<img width="500" src="https://github.com/junhaa/study/blob/main/image/project/talksum/talksum_upload.png?raw=true"/>|<br><img width="500" src="https://github.com/junhaa/study/blob/main/image/project/talksum/talksum_note.png?raw=true"/> |

---
## 시작 가이드

### Front-End
```bash
$ git clone https://github.com/Talk-Sum/TalkSum-FE.git
$ cd Talksum-FE/
$ npm install 
$ npm start
```

### Back-End
```bash
$ git clone https://github.com/Talk-Sum/TalkSum-BE.git
$ cd TalkSum-BE/
$ ./gradlew build -x test
$ java -jar ./build/libs/talksum-0.0.1-SNAPSHOT.jar
```

---

## 사용된 기술

### Front-End
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Kotlin](https://img.shields.io/badge/Kotiln-A349A4?style=for-the-badge&logo=Kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
### Back-End
![Mysql](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon%20AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

### Tools
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)             

---
<br><br>
<div align=center>
<img width="700px" src="https://github.com/junhaa/study/blob/main/image/project/talksum/talksum_panel.png?raw=true" />
</div>
