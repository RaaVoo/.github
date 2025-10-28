<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:03aed2,100:feef0d&height=150&text=라보야%20놀자&fontColor=2d2d2d&fontSize=60&fontAlignY=40" />
  <h3>AI 기반 아동 감정·행동 분석 플랫폼</h3>
  <p>감정의 흐름을 데이터로 읽고, 행동의 패턴을 이해하는 서비스</p>
</div>

---

## 🧭 Overview

> **Ravo**는 아동의 음성 및 표정 데이터를 AI로 분석하여  
> 감정 상태와 행동 패턴을 부모에게 시각적인 리포트 형태로 제공하는 서비스입니다.  
> 본 저장소(`Ravo_`)는 **개발용 메인 리포지토리**이며,  
> 전시용 저장소(`Ravo_be`, `Ravo_fe`)는 아래에서 확인할 수 있습니다.

---

## 🧩 Repository Structure

| 구분 | 저장소 링크 | 주요 기술 스택 |
|------|--------------|----------------|
| ⚙️ **Backend** | [RaaVoo/ravo_back](https://github.com/RaaVoo/ravo_back) | Node.js · Express · MySQL · Python(AI) |
| 🎨 **Frontend** | [RaaVoo/ravo_front](https://github.com/RaaVoo/ravo_front) | React · Vite · Tailwind CSS · Recharts |
| 🧠 **AI Module** | *(내장)* `ravo_emotion` | OpenAI API · Emotion Classification |

---

## 🛠️ Tech Stack

<div align="center">

| Frontend | Backend | AI / Infra |
|:---------:|:--------:|:-----------:|
| <img src="https://skillicons.dev/icons?i=react,vite,tailwind,js,html,css" height="45" /> | <img src="https://skillicons.dev/icons?i=nodejs,express,mysql,postman" height="45" /> | <img src="https://skillicons.dev/icons?i=python,raspberrypi,github" height="45" /> |

</div>

---

## ⚙️ Hardware Configuration

<div align="center">

<table>
  <tr>
    <th>Raspberry Pi 5</th>
    <th>Raspberry Pi Camera V2</th>
    <th>reSpeaker 2-Mics Pi HAT V2.0</th>
    <th>Raspberry Pi DAC Pro</th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/15b276fc-1acd-4a19-83df-93c33fea25dc" width="200"/></td>
    <td><img src="https://www.devicemart.co.kr/data/goods/1/2021/11/1077951_tmp_fec8135a266941e5f9cf8470be7c62016973view.png" width="200"/></td>
    <td><img src="https://www.devicemart.co.kr/data/collect_img/kind_0/fogoods/large/1383296_1.jpg" width="200"/></td>
    <td><img src="https://www.devicemart.co.kr/data/goods/1/2023/07/13237161_tmp_4f6c1d9e827c181b2c473cee474b378d4270view.png" width="200"/></td>
  </tr>
  <tr>
    <td>프로젝트의 메인 제어 보드로, 카메라 및 오디오 입력을 처리</td>
    <td>아이의 표정 및 행동 인식용 영상 데이터 수집 카메라</td>
    <td>AI 및 음성 애플리케이션용 Raspberry Pi용 듀얼 마이크 확장 보드</td>
    <td>음성 출력 품질 향상을 위한 고음질 DAC 모듈</td>
  </tr>
</table>

</div>

---

## 🚀 Main Features

### 🎙️ 1. AI Voice & Behavior Analysis Report  
AI가 아이의 **음성 및 행동 데이터를 분석**하여 자동으로 보고서를 생성합니다.

**🗣️ Voice Report (음성 보고서)**  
- 대화 내용 기반 **감정 분석 및 감정 요약**  
- 주요 감정 키워드 추출 및 시각화  
- 감정 흐름에 따른 **정서 상태 솔루션 제시**

**🎥 Behavior Report (행동 보고서)**  
- 영상 기반 **행동 분석 및 행동 요약**  
- 이상 행동 감지 및 분석  
- 행동 유형별 **AI 솔루션 제공**

> 📈 부모는 AI가 분석한 감정·행동 리포트를 통해  
> 자녀의 정서 변화를 직관적으로 확인할 수 있습니다.

---

### 🔊 2. Real-Time Voice Conversation  
아이와의 실시간 음성 대화를 통해 AI가 감정 변화를 분석하고 기록합니다.

- **AI Mode (자동)**: AI가 아이의 발화를 인식하고 자연스럽게 응답  
- **Manual Mode (수동)**: 부모가 직접 음성 대화 참여  
- 대화 자동 저장 및 **AI 요약 기능 제공**  
- 대화 내용 기반 **음성 보고서 자동 생성**  
- **대화 검색 / 모아보기 / 감정 히스토리 조회** 가능

> 💬 모든 대화는 아이의 감정 데이터를 형성하며,  
> 하루의 대화 패턴을 한눈에 분석할 수 있습니다.

---

### 📹 3. HomeCam Streaming & Recording  
홈캠을 통해 아이의 일상을 실시간으로 관찰하고, AI가 행동을 분석합니다.

- **Live Streaming**: 실시간 영상 시청  
- **Recording**: 특정 장면 저장 및 다시보기  
- **Gallery**: 영상 모아보기, 검색, 삭제 기능  
- 녹화된 영상을 기반으로 **행동 분석 보고서 생성**

> 🎞️ 단순한 영상 시청을 넘어,  
> AI가 일상의 순간을 ‘행동 인사이트’로 전환합니다.

---

### 👩‍👧 4. My Page – Profile & Child Management  
사용자 맞춤형 마이페이지에서 자녀 정보 및 보고서를 관리합니다.

- **프로필 및 자녀 정보 편집**  
- **자녀 추가 / 삭제 / 정보 수정**  
- **보고서 모아보기 (음성·행동 통합 조회)**  
- **로그인 / 로그아웃 / 회원 탈퇴 관리**  
- **FAQ 및 AI 문의 챗봇 제공**

> 📊 Ravo의 직관적인 대시보드를 통해  
> 자녀의 성장과 감정 데이터를 한눈에 관리할 수 있습니다.

---
