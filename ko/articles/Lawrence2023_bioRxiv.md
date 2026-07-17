---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
---

# Single cell transcriptomics reveals chondrocyte differentiation dynamics in vivo and in vitro

## Citation (NLM)
Lawrence JEG, Woods S, Roberts K, Sumanaweera D, Balogh P, Predeus AV, He P, Li T, Polanski K, Prigmore E, Tuck E, Mamanova L, Zhou D, Webb S, Jardine L, He X, Barker RA, Haniffa M, Flanagan AM, Young MD, Behjati S, Bayraktar O, Kimber SJ, Teichmann SA. Single cell transcriptomics reveals chondrocyte differentiation dynamics in vivo and in vitro. bioRxiv. 2023. doi:10.1101/2023.12.20.572425

**DOI:** [https://doi.org/10.1101/2023.12.20.572425](https://doi.org/10.1101/2023.12.20.572425)

---

## Background
연골 재생 의학 및 근골격계 질환 모델링을 위해 체외(in vitro)에서 배아 발달을 정확히 모방하는 연골세포를 일관적으로 생산하는 것이 중요하다. 현재 체외 연골 형성 프로토콜은 비표적 분화로 인해 이질적인 생성물을 생산하는 한계가 있으며, 인간 배아 조직과의 비교 부재로 인해 체외 세포의 상세한 평가가 어렵다.

## Key Experiment Methods
1. 인간 1분기(7-9 PCW) 하지 장골에서 단일 세포 RNA 시퀀싱(scRNA-seq) 수행 (72,944 cells)
2. 기존 공개 데이터와 통합하여 5-17 PCW 범위의 249,151 세포 발달 아틀라스 구축
3. 90유전자原位杂交(in-situ sequencing, ISS) 데이터와 k-최근접 이웃 분석을 통한 공간적 매핑
4. 공개된 체외 연골 형성 프로토콜의 bulk/scRNA-seq 데이터와 CellSignalAnalysis를 통한 전사 프로그램 비교
5. 체내(in vivo)와 체외(in vitro) 세포 간 Genes2Genes 동적 프로그래밍 궤적 정렬
6. FOXO1 억제제(AS1842856) 처리를 통한 비표적 골아세포 분화 억제 실험
7. RNA原位杂交(FISH)를 통한 마커 유전자 발현 검증

## Results
- 단일 세포 아틀라스에서 연골전구세포(PRRX1+, TWIST1+, FOXP1/2+), 초기 휴지기/휴지기 연골세포, 증식기, 전비대기, 비대기 연골세포, interzone 세포(GDF5+PRG4- 및 GDF5+PRG4+), 관절 연골세포(PRG4+, AQP1+, TPPP3+, COL2A1-) 등 다양한 세포 군집 동정
- 근위-원위 발달 구배 확인: 대퇴골은 경골/비골보다 성숙한 연골세포 비율이 높음
- 전사조절인자 네트워크 분석: SOX9, KLF4, STAT3 등은 연골형성 전반에 걸쳐 활성 증가, HAND1은 연골전구세포 특이적, DLX3/NFAT5/KLF15는 전비대/비대 연골세포 특이적, FOXO1은 골아세포에서, FOXO3은 비대 연골세포에서 높은 활성
- 체외 프로토콜 평가: MSC 기반 프로토콜은 섬유/골 세포 유형과 매칭, BMP4 프로토콜은 비대 연골세포, TGF-β 프로토콜은 관절 연골세포 신호 강화
- Genes2Genes 궤적 정렬: 체내-체간 전체 가변 유전자 중 58%만 일치, SOX6, SOX9, KLF2, KLF4 등은 일치하지만 COL1A1, ALPL, SPP1, SP7, FOXO1 등은 체외에서 비표적 발현
- FOXO1 억제제(AS18, 4-20 nM) 처리 시 COL2A1, COL9A1, MATN3, COMP 및 비대 마커(COL10A1, PTH1R) 발현 증가, 일부 골아세포 유전자(DDX5, KCNQ1OT1, SNHG14) 감소

## Perspective
본 연구는 인간 배아 발달의 단일 세포 데이터를 활용하여 조직 공학 프로토콜을 평가하고 개선하는 새로운 프레임워크를 제시한다. FOXO1 억제를 통해 연골세포 유전자 발현을 증가시킨 것은 개념 증명(proof of principle)으로, 배아 발달 데이터가 근골격계 조직 공학에 활용될 수 있음을 보여준다. 향후 전사조절인자 표적화를 통해 비표적 전사를 최소화하고 체내 세포 상태를 더 정확히 모방하는 프로토콜 개발이 기대된다. 단일 세포 시퀀싱의 한계(기질 풍부 조직의 해리 어려움, 17 PCW 이후 샘플 부재)와 실험 간 변동성은 해결해야 할 과제이다.

---

*Processed by **qwen3.6-plus** (OpenCode Go) on 2026-06-07*
