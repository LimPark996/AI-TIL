# AI-TIL

AI, LLM, ML, DL 관련 논문과 코드를 분석하고 학습한 내용을 기록하는 저장소입니다.

## 📚 About

이 레포지토리는 인공지능 분야의 최신 논문과 기술을 깊이 있게 공부하고, 그 내용을 체계적으로 정리하기 위해 만들어졌습니다. 
각 주제는 GitHub Issues를 통해 관리되며, 수학적 증명과 개념을 상세하게 다룹니다.

## 🎯 목표

- 최신 AI/ML/DL 논문의 핵심 개념 이해
- 수학적 기초와 증명 과정 상세 분석
- 이론과 실제 구현의 연결
- 지속적인 학습과 기록

## 📖 학습 내용

### [2025.10.04] Language Models & Hallucination

- [Why Language Models Hallucinate - 논문 분석](https://github.com/LimPark996/AI-TIL/issues/1)
  - 언어 모델이 환각(hallucination)을 일으키는 통계적 원인 분석
  - Pretraining과 Post-training 단계에서의 환각 발생 메커니즘
  - Is-It-Valid (IIV) 분류 문제를 통한 수학적 증명

### [2025.10.04] Transformer Architecture

- [Attention Is All You Need - 논문 분석](https://github.com/LimPark996/AI-TIL/issues/2#issue-3483221548)
   - Attention 메커니즘만으로 RNN/CNN 완전 대체 가능성 증명
   - Scaled Dot-Product Attention과 Multi-Head 구조의 수학적 근거
   - WMT 2014에서 SOTA 달성 (BLEU 28.4, 기존 대비 +7.8%)
   - 병렬 처리를 통한 훈련 효율성 향상 (RNN 대비 ~7배)
- [Scaled Dot-Product Attention - 학습](https://github.com/LimPark996/AI-TIL/issues/3#issue-3483635156)
  - Attention 메커니즘의 forward/backward pass 구체적 계산 과정
  - 구체적 수치 예시를 통한 QKV 변환 및 gradient 흐름 분석
