---
tags: [2026-06, Chondrocyte]
extract: 2026-06-08
log:
  - "2026-06-08 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Microenvironmental mechanoactivation through Yap/Taz suppresses chondrogenic gene expression

## Citation (NLM)
Hallström GF, Jones DL, Locke RC, Bonnevie ED, Kim SY, Laforest L, Cruz Garcia D, Mauck RL. Microenvironmental mechanoactivation through Yap/Taz suppresses chondrogenic gene expression. *Mol Biol Cell*. 2023 Jun 1;34(7):ar73. doi:10.1091/mbc.E22-12-0543

**DOI:** [https://doi.org/10.1091/mbc.E22-12-0543](https://doi.org/10.1091/mbc.E22-12-0543)

---

## Background

연골세포의 표현형은 세포가 둥글고 actin 세포골격이 cortical 형태일 때 유지된다. 그러나 단층 배양에서 연골세포는 빠르게 탈분화(dedifferentiation)되며, Rho 신호 활성화에 의해 세포 크기가 증가하고 큰 actin stress fiber가 형성된다. Rho가 연골세포 표현형에 미치는 영향은 잘 알려져 있으나, 그 분자 기전은 완전히 규명되지 않았다. Yap은 기계적 자극 전달(mechanotransduction) 경로에서 Rho에 의해 조절되는 전사 공조인자로, 생체 내에서 연골형성(chondrogenesis)을 억제할 수 있다는 보고가 있다. 본 연구는 기계적 자극 전달 경로인 Rho와 Yap 간의 관계가 연골형성 유전자 발현을 어떻게 조절하는지 규명하고자 하였다.

---

## Key Experiment Methods

1. **세포 배양 및 연골 분화 유도**: ATDC5 연골 전구세포주를 고밀도 단층 배양하고 TGF-β3(10 ng/mL)가 포함된 연골 분화 배지(CM)로 분화 유도.

2. **Rho 신호 조절 약물 처리**: Rho 억제제 C3 transferase(0.3 μg/mL)와 Rho 활성화제 LPA(50 또는 20 μM)를 처리하여 연골형성 마커(Sox9, Col2a1, Acan)의 발현 변화를 qRT-PCR로 분석.

3. **siRNA 기반 Yap/Taz 녹다운**: Yap1 및 Wwtr1(Taz)에 대한 siRNA를 ATDC5 세포에 형질주입 후 5일째 연골형성 마커 발현 평가. 단일 및 이중 녹다운 조건 비교.

4. **RNA-seq 분석**: C3 처리, LPA 처리, siY/T 처리, 다양한 기질 경도 조건(5 kPa, 55 kPa polyacrylamide hydrogel, glass)에서의 전사체를 NovaSeq 6000으로 시퀀싱. DESeq2 및 Gene Ontology 분석.

5. **기질 경도 조절 실험**: 5 kPa(연골 주변세포기질 유사) 및 55 kPa PA hydrogel 제작, fibronectin 코팅 후 세포 접종. Yap 핵/세포질 비율 및 연골형성 마커 분석.

6. **면역형광 염색 및 이미징**: F-actin(phalloidin), YAP, collagen VI 항체 염색. 공초점 현미경으로 Yap 핵/세포질 국재화 정량. 세포 및 핵 면적은 CellProfiler로 측정.

7. **Western blot**: SOX9, YAP/TAZ, collagen VI 단백질 발현 평가. Odyssey 적외선 이미징 시스템으로 정량.

8. **통계 분석**: 비모수 일원분산분석(Kruskal-Wallis with Dunn's test), 비모수 t-test(Mann-Whitney), 모수 일원분산분석.

---

## Results

**Rho 신호와 연골형성 유전자 발현의 역상관 관계**: C3(Rho 억제) 처리 시 Sox9, Col2a1, Acan 발현이 유의하게 증가하였고, LPA(Rho 활성화) 처리 시 감소하였다. RNA-seq 분석 결과, Rho 억제는 Gdf5, Nkx3-2, Col6a1-3, Col9a2, Col11a1 등 새로운 연골형성 유전자들의 광범위한 상향 조절을 유도하였다. 반면 LPA 처리는 MMP-3, -9, -10, -12, -13 등 이화성 기질 단백질의 발현을 증가시켰다.

**Yap/Taz의 연골형성 억제 역할**: Yap과 Taz의 이중 녹다운(siY/T)은 연골형성 마커 발현을 유의하게 증가시켰으며, 비연골형성 배지(BM)에서도 유사한 효과를 보여 Yap/Taz가 연골형성의 주요 음성 조절자임을 입증하였다. siY/T 처리 세포는 세포 및 핵 면적이 유의하게 감소하였다.

**기질 경도 감소가 연골형성 촉진**: 5 kPa의 연한 기질에서 glass에 비해 YAP 핵 국재화가 현저히 감소하였고, Col2a1, SOX9, COLVI 발현이 유의하게 증가하였다. 55 kPa 기질은 중간 정도의 효과를 보였다. RNA-seq에서 5 kPa 및 55 kPa 기질 모두 Gdf5, Col6, Col9, Col11, Trpv4, Prg4 등의 연골형성 유전자 상향 조절을 유도하였다.

**통합 분석**: C3, siY/T, 5 kPa, 55 kPa의 4가지 연골형성 촉진 조건에서 공통적으로 상향 조절된 27개 유전자를 발굴하였다(Col2a1, Col9a2, Col11a1, Trpv4, Gdf5, Sox6 포함). GO 분석에서 연골 발달, 연골 응축, 골화, ECM 조직화, 연골세포 분화 항목이 확인되었다.

**Yap/Taz가 Rho 신호 하류에서 연골형성 조절**: 55 kPa 기질에서 C3 처리는 YAP 핵 국재화를 감소시키고 연골형성 마커를 증가시킨 반면, LPA 처리는 반대 효과를 보였다. siY/T 녹다운 상태에서는 LPA 처리에도 연골형성 유전자 발현이 감소하지 않았으며, C3 추가 처리에도 추가 증가가 없어, Rho 신호가 주로 Yap/Taz 경로를 통해 연골형성을 조절함을 입증하였다.

---

## Perspective

본 연구는 연골세포의 기계적 환경이 Yap/Taz를 매개로 연골형성 유전자 발현을 조절하는 분자 기전을 포괄적으로 규명하였다. 기계적 활성화가 낮은 환경(Rho 억제, 연한 기질)에서는 YAP 핀 국재화가 감소하여 SOX9 의존적 연골형성 프로그램이 활성화되고, 기계적 활성화가 높은 환경(Rho 활성화, 딱딱한 기질)에서는 YAP이 핵으로 이동하여 연골형성을 억제한다.

다양한 조건(C3, siY/T, 연한 기질)에서 유도된 연골형성 유전자 프로그램이 상당 부분 중복된다는 점은, 이들 경로가 공통적인 하류 기전을 공유함을 시사한다. 특히 siY/T가 비연골형성 배지에서도 연골형성을 유도할 수 있다는 발견은 Yap/Taz가 연골세포 운명 결정의 핵심 스위치 역할을 함을 강조한다.

향후 과제로는 Yap이 SOX9 프로모터의 TEAD 결합 부위를 통해 직접적 전사 억제자로 작용하는지, 또는 항연골형성 유전자좌의 전사 활성화자로 기능하는지에 대한 ChIP-seq 기반 기전 연구가 필요하다. 또한 본 연구의 발견은 Rho/Yap/Taz 경로를 표적으로 하는 소분자 또는 생체재료를 활용한 연골 재생 치료 전략 개발에 중요한 기초를 제공한다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-08*
