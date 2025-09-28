# 건설공사 사고 예방 및 대응책 생성  
**한솔데코 시즌3 AI 경진대회 | Team 안전하GO**

## 📌 프로젝트 개요
- **목표**: 건설공사 사고 데이터를 기반으로 사고 원인을 분석하고, **재발 방지 대응책을 자동 생성하는 LLM 기반 모델** 개발  
- **기간**: 2025.02.17 ~ 2025.03.24  
- **팀 구성**: 4명 (Team 안전하GO)  
- **핵심 접근**:
  - 데이터 불균형 → 증강 기법 적용 (BERT Augmentation, RMI/RMR)  
  - 다양한 LLM 실험 → KoBART, KoGemma 등 성능 비교  
  - Cross Encoder 적용 → 검색 결과 재평가 및 답변 품질 개선  

## 👤 역할 (본인 기여)
- 사고 데이터 **전처리 및 불필요 정보 제거**  
- **데이터 불균형 보완**: BERT 기반 증강 기법 (RMI/RMR) 적용  
- **LLM 성능 비교**: KoBART·KoGemma 등 실험 후 최종 모델 선정  
- Cross Encoder 적용으로 **검색-생성 파이프라인 품질 개선**

## 🚀 성과
- **최종 모델**: Ko-Gemma2 9B + RMR 증강 + Cross Encoder  
- **자체 검증 성능**: Cosine Similarity 0.567  
- **대회 Private Score**: 0.4399  
- 건설공사 **안전 관리·대응 자동화 가능성**을 입증  

* Team 안전하GO! 만든 LLM 은 KO - Gemma 9B 를 Fine - funed 모델입니다.
* 궁금한 사항이 있다면 메일로 문의주세요 
