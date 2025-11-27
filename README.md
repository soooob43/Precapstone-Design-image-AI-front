# Precapstone – AI 이미지 생성 & 메시지 발송 프론트엔드  
프롬프트 기반 AI 이미지 생성, 이미지 데이터 관리, 메시지 발송 기능을 제공하는 단독 프론트엔드 프로젝트  
(다우기술 과제)

---

## 목차 (Table of Contents)
- [🇰🇷 프로젝트 소개](#🇰🇷-프로젝트-소개)
- [주요 기능](#주요-기능)
- [기술 스택](#기술-스택)
- [내 역할](#내-역할)
- [프로젝트 구조](#프로젝트-구조)
- [시작하기](#시작하기)
- [회고](#회고)
- [🇺🇸 Project Overview](#🇺🇸-project-overview)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [My Contribution](#my-contribution)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Reflection](#reflection)

---

# 🇰🇷 프로젝트 소개

본 프로젝트는 학기 중, 다우기술의 과제를 받고 개발한 AI 이미지 생성 및 메시지 발송 서비스의 프론트엔드 구현 프로젝트입니다.  
사용자가 입력한 프롬프트를 기반으로 AI 이미지를 생성하고, 생성된 이미지를 관리·저장하며, 메시지 작성 UI를 통해 메시지 발송 API와 연동하여 발송할 수 있는 기능을 제공합니다.

전체 UI/UX 구성, 이미지 생성 화면, 메시지 발송 페이지 및 API 연동까지 모든 프론트엔드 개발을 단독으로 수행했습니다.

---

# 주요 기능

- 프롬프트 기반 AI 이미지 생성 기능
- 생성된 이미지 목록 조회 및 미리보기
- 이미지 데이터 관리 (저장, 선택, 삭제)
- 메시지 작성/미리보기 UI
- 메시지 발송 API 연동
- 전체 메인 페이지·서브 페이지 UI/UX 구성
- React 기반 SPA 환경 구성

---

# 기술 스택

- React (Create React App)
- JavaScript  
- CSS / Styled Components  
- REST API 통신  
- Local state management (useState, useEffect 등)

---

# 내 역할

- 프로젝트 초기 세팅(CRA), 구조 설계, 개발 전반 담당
- 프롬프트 입력 기반 AI 이미지 생성 화면 구현
- 생성된 이미지 데이터의 저장/관리/렌더링 기능 구현
- 메시지 작성 UI/상태 흐름 설계 및 메시지 발송 API 연동
- 메인 페이지 및 이미지 출력 페이지 전체 UI 구성
- 사용자 경험을 고려한 SPA 페이지 전환 및 구성 정리

---

# 🇺🇸 Project Overview

This project is the frontend implementation of an AI-based image generation and messaging service, developed in collaboration with DAOU Technology.
It enables users to generate AI images from text prompts, manage and preview generated image data, compose messages, and send them using a messaging API.

All frontend development — UI, page structure, image workflow, messaging UI, and API integration — was fully implemented by me.

Key Features
- Prompt-based AI image generation interface
- Generated image storage, retrieval, and preview
- Message composition and preview UI
- Messaging API integration
- Full UI/UX design and page structure
- React SPA with client-side state management

Tech Stack
React (Create React App)
JavaScript
CSS / Styled Components
REST API communication
Client-side state management (useState, useEffect)

My Contribution
Set up the project using Create React App and designed the full project structure
Implemented AI image generation UI and prompt handling workflow
Built image data management features (save, view, delete, render)
Developed message composition UI and integrated the messaging API
Designed the main page and all user interface flows
Implemented SPA routing and state flow
Designed API request/response logic and error handling

Getting Started
git clone https://github.com/soooob43/Precapstone-Design-image-AI-front.git
npm install
npm start
