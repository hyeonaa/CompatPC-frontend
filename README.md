# CompatPC Frontend

컴퓨터 부품 간의 호환성을 확인하고 진단 결과를 제공하는 웹 서비스 **CompatPC**의 프론트엔드 프로젝트입니다.

사용자가 CPU, GPU, RAM, SSD 등의 컴퓨터 부품을 선택하면 서버 API와 연동하여 부품 정보를 조회하고, 선택된 부품 간의 호환 여부를 확인할 수 있도록 사용자 인터페이스를 제공합니다.

본 프로젝트는 **지능형 시스템 과목 팀 프로젝트**로 진행되었습니다.

---

## Tech Stack

* HTML
* CSS
* JavaScript

---

## Key Features

### 컴퓨터 부품 선택 UI

* CPU, GPU, RAM, SSD 등 다양한 컴퓨터 부품을 드롭다운 형태로 선택할 수 있는 사용자 인터페이스 구현

### 부품 데이터 조회

* 서버 API를 통해 각 컴퓨터 부품의 정보를 조회하고 화면에 표시

### 부품 호환성 확인

* 사용자가 선택한 부품 정보를 서버에 전달하여 부품 간 호환 여부 확인

### 결과 출력 인터페이스

* 서버에서 전달받은 진단 결과를 사용자에게 시각적으로 표시

---

## My Contributions

### Project Manager (PM)

* 팀 프로젝트 일정 관리 및 진행 상황 조율
* 팀원 역할 분배 및 협업 진행 관리
* **Jira를 활용한 작업 일정 관리 및 이슈 정리**

### Frontend Development

* 컴퓨터 부품 선택 **UI 설계 및 구현**
* 드롭다운 기반 **부품 선택 인터페이스 개발**
* 서버 API와의 **데이터 매핑 및 요청 처리**
* 사용자 입력 기반 **결과 출력 화면 구현**

---

## Project Structure

```
CompatPC-frontend
 ┣ css
 ┣ js
 ┣ images
 ┗ index.html
```

---

## Project Overview

CompatPC는 사용자가 직접 컴퓨터 부품을 선택하면
각 부품 간의 호환 여부를 분석하여 결과를 제공하는 시스템입니다.

프론트엔드는 사용자 인터페이스를 담당하며 서버 API와 통신하여
부품 데이터를 불러오고 사용자가 선택한 부품 조합에 대한
호환성 확인 결과를 화면에 표시합니다.

---

## Original Repository

팀 프로젝트로 진행된 원본 저장소입니다.

https://github.com/joejaeyoung/CompatPC
