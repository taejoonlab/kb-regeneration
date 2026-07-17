---
tags: [2026-06, Chondrocyte]
extract: 2026-06-08
log:
  - "2026-06-08 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Ttc30a affects tubulin modifications in a model for ciliary chondrodysplasia with polycystic kidney disease

## Citation (NLM)
Getwan M, Hoppmann A, Schlosser P, Grand K, Song W, Diehl R, Schroda S, Heeg F, Deutsch K, Hildebrandt F, Lausch E, Köttgen A, Lienkamp SS. Ttc30a affects tubulin modifications in a model for ciliary chondrodysplasia with polycystic kidney disease. Proc Natl Acad Sci USA. 2021;118(37):e2106770118. doi:10.1073/pnas.2106770118

**DOI:** [https://doi.org/10.1073/pnas.2106770118](https://doi.org/10.1073/pnas.2106770118)

---

## Background

섬모형성장이상증(skeletal ciliopathy, SC)은 Jeune 증후군, short rib polydactyly 증후군, Sensenbrenner 증후군 등과 같은 골격 이상을 특징으로 하며, 종종 신장낭종(nephronophthisis-like cystic kidney disease)을 동반한다. 현재까지 27개 이상의 질환 유전자가 알려져 있으나, 연골 결손과 낭성 신장 질환 간의 공통 분자 기전은 아직 명확히 규명되지 않았다. 중심소체(primary cilium)의 기능 장애는 Hedgehog(Hh) 신호전달 경로를 교란시켜 연골세포 증식 및 분화에 영향을 미친다. 특히, axonemal tubulin의 polyglycylation, polyglutamylation과 같은 번역후 변형(PTM)이 섬모 기능에 중요하지만, 이러한 PTM 결함이 어떤 섬모질환에서 표현형 이질성에 기여하는지는 알려져 있지 않다.

---

## Key Experiment Methods

1. **CRISPR/Cas9 유전자 편집**: X. tropicalis에서 1-세포기 또는 2-세포기 배아에 Cas9/sgRNA RNP 주입. ift80, ift172, ttc30a 및 후보 유전자(cfap20, c11orf74, cep192) 표적.
2. **표현형 분석**: 부종(edema) 정량화, 사지 길이 측정, microCT 조영증강 스캔으로 골격 및 신장 구조 3차원 분석.
3. **조직학 및 면역염색**: H&E 염색, acetylated tubulin, polyglutamylation, monoglycylation 특이 항체를 이용한 면역형광 염색.
4. **신장 배설 기능 분석**: 형광 표지 dextran을 체강 내 주입 후 신세뇨관 내 이동 실시간 관찰.
5. **데이터 마이닝 기반 in silico 스크리닝**: 90개의 공개 게놈 스크린/단백질체 데이터셋(resource lists)에서 SC 유전자와 공통 분자 특성을 가진 후보 유전자 발굴.
6. **RNA-seq**: ift80, ift172 표적 배아(neurula stage 22)에서 전사체 분석. Hh 및 Wnt 신호 경로 관련 유전자 변화 확인.
7. **단일세포 RNA-seq 분석**: E13.5 생쥐 사지 싹의 공개 데이터 활용. Ttc30a1, Ttc30a2, Ttc30b 발현 패턴 분석.

---

## Results

- CRISPR/Cas9로 ift80, ift172를 표적한 X. tropicalis 성체(froglet)에서 심각한 사지 기형(단축, syndactyly, polydactyly)과 낭성 신장(mesone-phric polycystic kidney)이 관찰됨.
- 사지 연골은 휴지기 및 증식대가 우세하고, 비대대 및 골화대가 감소하여 연골세포 분화 결함을 보임.
- ift80, ift172 결손은 다중섬모세포(MCC)의 섬모 길이와 수를 감소시키고, 신장 배설 기능을 현저히 저하시킴 (dextran 배설율 12-14% 대 대조군 85%).
- RNA-seq에서 Hh 신호(ccng1, ulk1, riok3) 및 Wnt 신호 관련 유전자의 변화 감지.
- In silico 스크리닝으로 65개 후보 유전자 발굴. 이 중 ttc30a 표적이 ift80 및 ift172 결손 표현형(부종, 사지 단축, polydactyly, 낭성 신장, 섬모 길이 감소)을 모두 재현함.
- Ttc30a 결손 섬모에서 tubulin glycylation 감소, acetylation 소실, axoneme 구획화(compartmentalization) 결함 확인. 특히 섬모 말단부(tip)의 acetylated tubulin 소실이 두드러짐.
- 생쥐 사지 단일세포 RNA-seq에서 Ttc30b, Ttc30a1이 연골 및 골세포 클러스터에서 높게 발현됨. Ift80, Ift172와 유사한 분포 패턴.
- TTC30A/B가 ciliary segmentation의 핵심 노드로 작용하며, tubulin PTM과 섬모 구획화가 세포 유형 특이적으로 섬모질환 발현에 기여함을 제시.

---

## Perspective

- 본 연구는 X. tropicalis가 SC 연구에 적합한 모델임을 입증; CRISPR/Cas9 표적이 임상 증상을 충실히 재현하며, 기존 zebrafish와 생쥐 모델을 보완함.
- TTC30A/B를 ciliary chondrodysplasia와 nephronophthisis-like 질환의 네트워크에서 새로운 핵심 구성요소로 규명.
- Tubulin PTM(특히 glycylation, acetylation)과 섬모 tip 구획화의 결함이 골격 및 신장 섬모질환의 표현형 다발성(pleiotropy)에 기여함을 시사.
- 인간 TTC30A/B가 tetrapod 계통에서 유전자 중복을 통해 보존된 핵심 유전자좌이며, Chlamydomonas부터 인간까지 고도로 보존되어 있음.
- 향후 TTC30A/B의 Hh 및 Wnt 신호전달 조절 기전, 그리고 낭성 신장 형성에서의 역할 규명이 필요함. in vitro에서 특성화된 섬모 단백질의 조직 특이적 기능을 in vivo에서 할당하는 접근법이 중요한 과제.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-08*

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-08*
