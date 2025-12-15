# 🛡️ AION(아이온)
> **AI 기반 네트워크 공격 감지 서비스 (NIDS)**

**AION**은 AI를 활용하여 사용자의 네트워크 트래픽 상태를 실시간으로 분석하고, 위협적인 공격을 감지하여 시각화해 주는 웹 기반 보안 플랫폼입니다.

> **[🛡️ 탐지 범위 (Detection Scope)]**
> * **💥 DDoS & Flooding:** `SYN Flood`, `UDP Flood`, `UDP Amplification`, `ICMP Flood`, `Other TCP Flood`
> * **🕵️ Reconnaissance (정찰):** `Port Scan` (포트 스캔)
> * **🐢 Slow-Rate Attack:** `Slowloris` (저속 공격)

<br/>

<div align="center">

[![AION 시연 영상](https://img.youtube.com/vi/f3IA_bDUtyc/0.jpg)](https://youtu.be/hAPD6JiZzeE)

[📺 AION 시연 영상 보러가기](hhttps://youtu.be/hAPD6JiZzeE)

</div>

<br/>

## 👥 Developers (개발팀)

<table width="100%">
  <thead>
    <tr>
      <th width="33%" align="center">💻 웹 사이트 개발</th>
      <th width="34%" align="center">🧠 AI 분석 서버 개발</th>
      <th width="33%" align="center">🕵️ 분석기 개발 (Client)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/seo342">
          <img src="https://github.com/seo342.png" width="100px;" alt=""/>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/Lineon24">
          <img src="https://github.com/Lineon24.png" width="100px;" alt=""/>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/Urban31722">
          <img src="https://github.com/Urban31722.png" width="100px;" alt=""/>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">
        <b>서승진</b> <br/><br/>
        <span style="font-size: 13px;">
          웹 사이트 구현<br/>
          로그인/회원가입<br/>
          API 인증<br/>
          API 별 데이터 관리<br/>
          트래픽 통계 시각화<br/>
          실시간 트래픽 요약<br/>
          실시간 이메일 알림
        </span>
      </td>
      <td align="center">
        <b>이준희</b> <br/>
        <span style="font-size: 12px;">👑 팀장</span><br/><br/>
        <span style="font-size: 13px;">
          프로젝트 총괄<br/>
          시스템 아키텍처 설계<br/>
          JSON 포맷 정의<br/>
          <br/>
          핵심 방법론 연구<br/>
          (특징/트래픽 측정 방식)<br/>
          학습 데이터셋 자체 구축<br/>
          데이터 수집기 개발<br/>
          AI 공격 탐지 모델 제작
        </span>
      </td>
      <td align="center">
        <b>김윤정</b> <br/><br/>
        <span style="font-size: 13px;">
          데이터 수집기 고도화<br/>
          (분석기 제작)<br/>
          트래픽 통계 실시간 확인<br/>
          위험 IP 탐지<br/>
          사용자 편의성 설정<br/>
          분석기 패키징<br/>
          매뉴얼 제작
        </span>
      </td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/seo342/network-security-service">
          <img src="https://img.shields.io/badge/AION-Web_코드-black?logo=github"/>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/Lineon24/Network-ai-Analysis"> 
          <img src="https://img.shields.io/badge/AION-AI_Server_코드-black?logo=github"/>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/Urban31722/network_analyzer">
          <img src="https://img.shields.io/badge/AION-Analyzer_코드-black?logo=github"/>
        </a>
      </td>
    </tr>
  </tbody>
</table>

<br/>

## 🏆 Awards
* **정보통신학과 공모전 장려상 수상**
<br/>

## 🚀 Getting Started (시작 가이드)

### 🏠 1. 메인 사이트 접속
AION 서비스의 메인 랜딩 페이지입니다.
<div align="center">
  <img src="./images/메인.gif" width="100%" />
</div>
<br/>

### 🔐 2. 회원가입 및 로그인
서비스 이용을 위해 계정을 생성하고 로그인합니다.
<div align="center">
  <img src="./images/회원가입.png" width="100%" />
</div>
<div align="center">
  <img src="./images/로그인.png" width="100%" />
</div>
<br/>

### 🔑 3. API 키 발급
분석기와 연동할 고유 API 키를 발급받습니다.
<div align="center">
  <img src="./images/API 키 발급.gif" width="100%" />
</div>
<br/>

### 📥 4. 분석기 다운로드
내 PC를 보호할 분석기 프로그램과 매뉴얼을 다운로드합니다.
<div align="center">
  <img src="./images/다운로드.gif" width="100%" />
</div>
<br/>

### 📖 5. 매뉴얼 확인
제공된 가이드를 참고하여 설정을 진행합니다.
<div align="center">
  <img src="./images/메뉴얼.gif" width="100%" />
</div>
<br/>

### ▶️ 6. 탐지 시작
분석기를 실행하여 실시간 네트워크 보호를 시작합니다.
<div align="center">
  <img src="./images/탐지 시작.gif" width="100%" />
</div>
<br/>

## 🚨 Core Features: 공격 탐지
### ⚠️ 공격 탐지 알림
분석기가 공격 패킷을 감지하면 즉시 화면에 경고 로고가 나타납니다. AION은 아래의 **7가지 주요 네트워크 공격**을 실시간으로 식별합니다.

<div align="center">
  <img src="./images/공격 탐지 1.gif" width="100%" />
</div>
<br/>

### 📈 상태 대시보드
실시간 트래픽 흐름과 이상 징후를 그래프로 확인합니다.
<div align="center">
  <img src="./images/상대 대시보드.gif" width="100%" />
</div>
<br/>

### 📧 이메일 알림 
공격 발생 시 이메일로 알림을 전송하고
<div align="center">
  <img src="./images/포트스캔 및 이메일.gif" width="100%" />
</div>
<br/>

### 🚫 위험 IP 차단 정보
감지된 위험 IP 정보를 웹 서버로 전송하여 관리합니다.
<div align="center">
  <img src="./images/위험 IP.png" width="100%" />
</div>
<br/>

## 💻 Web Dashboard Features (웹 기능)

### 🗄️ 키(Key)별 데이터 관리
생성한 API 키 별로 수집된 데이터를 분리하여 저장/관리합니다.
<div align="center">
  <img src="./images/키별 데이터.png" width="100%" />
</div>
<br/>

### 🎛️ 다양한 대시보드 위젯
사용자가 필요한 정보를 선택하여 볼 수 있는 다양한 메뉴를 제공합니다.
<div align="center">
  <img src="./images/대시보드.gif" width="100%" />
</div>
<br/>

### ⚡ 실시간 트래픽 요약
현재 네트워크 트래픽 상태를 실시간 요약 정보로 제공합니다.
<div align="center">
  <img src="./images/실시간 트래픽 요약.gif" width="100%" />
</div>
<br/>

### 🧐 위협 분석 상세
등록된 위험 IP들의 상세 정보와 공격 이력을 제공합니다.
<div align="center">
  <img src="./images/위협 분석.gif" width="100%" />
</div>
<br/>

### 📑 다각도 트래픽 분석
수집된 데이터를 차트, 표 등 다양한 형식으로 가공하여 보여줍니다.
<div align="center">
  <img src="./images/분석.gif" width="100%" />
</div>
<br/>

### ⚙️ 환경 설정
이메일 알림 수신 여부나 API 키 활성/비활성화 상태를 변경합니다.
<div align="center">
  <img src="./images/설정.png" width="100%" />
</div>
<br/>

## 🛠️ Development Process

### 1. Final System Architecture (최종 시스템 아키텍처)
> **"Secure Pipeline for Real-time Threat Detection"**
> 개발 완료 후 정립된 최종 시스템 구조입니다. 데이터의 수집부터 분석, 시각화까지 이어지는 파이프라인을 **보안성(Security)**과 **실시간성(Real-time)**에 초점을 맞춰 구현했습니다.

* **Secure Data Transmission:**
    * 사용자 분석기(AION_Sentinel)는 **5초 단위**로 플로우 통계 데이터를 집계하여 전송합니다.
    * 단순 전송이 아닌, **API Key와 Auth Key를 조합한 Hash 검증** 로직(Random Salt + Admin Value)을 통해 비인가된 접근을 원천 차단합니다.
* **Decoupled AI Engine:**
    * AI 분석 서버는 인증된 데이터의 **41개 핵심 피처**를 분석하여 공격 여부를 판별하고, 그 결과를 즉시 웹 서버와 DB로 전파합니다.
* **Centralized Data Management:**
    * 데이터베이스 서버는 사용자 정보, 트래픽 로그, 위험 IP 목록을 통합 관리하며 전체 시스템의 허브 역할을 수행합니다.

<div align="center">
  <img src="./images/간단한 아키텍처.png" alt="Final System Architecture Diagram" width="90%">
  <p><em>[Figure 1] 간단한 아키텍처</em></p>
</div>

<br>

### 2. Initial Wireframe & Design (초기 기획 및 와이어프레임)
> **"Blueprint for the Dashboard"**
> 프로젝트 착수 단계에서 구상한 **초기 디자인(Prototype)**입니다. '판단'과 '대응'이 직관적으로 가능한 UI를 목표로 설계되었습니다.

개발 과정에서 실제 구현 가능성과 사용자 편의성을 고려하여 UI를 지속적으로 고도화하였으며, 아래의 초기 기획안을 바탕으로 현재의 대시보드가 완성되었습니다.

* **Concept:** 복잡한 설정 없이 API를 발급받고(Onboarding), 네트워크 흐름을 한눈에 보며(Monitoring), 위협에 대응(Response)하는 3단계 구성을 기획했습니다.
* **Plan:** * **Overview:** 텍스트보다는 그래프와 차트 위주의 시각화 배치

<div align="center">
  <table>
    <tr>
      <td align="center"><b>초기 와이어 프레임: 페이지들</b></td>
    </tr>
    <tr>
      <td colspan="2" align="center"><img src="./images/와이어프레임1.png" width="80%"></td>
    </tr>
    <tr>
      <td colspan="2" align="center"><b>초기 와이어 프레임: 대시보드 1</b></td>
    </tr>
    <tr>
      <td colspan="2" align="center"><img src="./images/와이어프레임2.png" width="80%"></td>
    </tr>
        <tr>
      <td colspan="2" align="center"><b>초기 와이어 프레임: 대시보드 2</b></td>
    </tr>
    <tr>
      <td colspan="2" align="center"><img src="./images/와이어프레임3.png" width="60%"></td>
    </tr>
  </table>
  <p><em>[Figure 2] 프로젝트 초기 와이어 프레임</em></p>
</div>

