# Jekyll 기반 포트폴리오 사이트

## _config.yml
```yml
title: "AI & Computer Vision Portfolio"
author: "Your Name"
description: "Portfolio of an AI and Computer Vision Researcher"
baseurl: "" # 리포지토리 이름 (예: /your-portfolio)
url: "https://yourgithub.github.io" # GitHub Pages 주소
theme: minima
```

## index.md
```md
---
layout: default
title: Home
---
# AI & Computer Vision Researcher

안녕하세요! 저는 AI와 컴퓨터 비전을 연구하는 연구자입니다.

## 소개
- 학부 연구생 (2025-2027) - 컴퓨터 비전 연구실
- AI 관련 대학원 석사 연구 (2027-2029 예정)

## 기술 스택
- Python, TensorFlow, PyTorch, OpenCV, C++
- React, Node.js, Git, Docker

[GitHub](https://github.com/yourgithub) | [LinkedIn](https://linkedin.com/in/yourlinkedin) | [Email](mailto:your.email@example.com)
```

## about.md
```md
---
layout: default
title: About
---
# About Me

저는 AI와 컴퓨터 비전 연구를 전문으로 하는 개발자입니다. 현재 컴퓨터 비전 연구실에서 학부 연구생으로 활동 중이며, 이후 AI 관련 대학원에서 연구를 이어갈 계획입니다.

## 연구 관심 분야
- 객체 탐지 및 인식
- GAN을 활용한 이미지 생성
- 자율 주행 및 영상 처리
```

## projects.md
```md
---
layout: default
title: Projects
---
# Projects

## AI 기반 객체 탐지
- OpenCV 및 PyTorch를 활용한 실시간 객체 탐지 프로젝트
- YOLO 모델을 사용하여 성능 최적화

## GAN을 활용한 이미지 생성
- 딥러닝을 활용한 스타일 변환 프로젝트
- TensorFlow 기반 CycleGAN 모델 구현
```

## _posts/2025-03-24-first-post.md
```md
---
layout: post
title: "My First Research Blog"
date: 2025-03-24
categories: research
---
# 연구 블로그 첫 글

이 블로그에서는 제가 연구한 AI 및 컴퓨터 비전 관련 내용을 공유할 예정입니다.
```
