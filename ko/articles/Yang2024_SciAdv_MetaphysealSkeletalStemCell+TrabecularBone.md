---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
---

# Identification of the metaphyseal skeletal stem cell building trabecular bone

## Citation (NLM)
Yang G, He Q, Guo X, Li RY, Lin J, Lang Y, Tao W, Liu W, Lin H, Xing S, Qi Y, Xie Z, Han JDJ, Zhou B, Teng Y, Yang X. Identification of the metaphyseal skeletal stem cell building trabecular bone. Sci Adv. 2024;10(8):eadl2238. doi:10.1126/sciadv.adl2238

**DOI:** [https://doi.org/10.1126/sciadv.adl2238](https://doi.org/10.1126/sciadv.adl2238)

---

## Background

골격 줄기세포(skeletal stem cell, SSC)는 자기재생능과 다분화능을 가지며 골 발달과 항상성에 기여한다. 여러 해부학적 부위에서 다양한 SSC 집단이 보고되었으나, 골간단(metaphysis)에 특이적인 SSC 집단과 그 특성은 완전히 밝혀지지 않았다. 비대형 연골세포(hypertrophic chondrocyte, HC)가 조골세포와 골수 기질세포(BMSC)로 전환될 수 있다는 선행 연구들이 있었지만, HC 유래 세포의 계층 구조와 형질전환의 분자 기전은 명확하지 않았다. 본 연구는 골간단에 위치하며 성장판 직하방에서 발견되는 새로운 SSC 집단인 metaphyseal SSC (mpSSC)를 발굴하고, HC에서 유래하여 해면골 형성을 담당하는 과정을 규명하고자 하였다.

---

## Key Experiment Methods

- **scRNA-seq**: P7.5 Col10a1-ZsGreen 마우스 원위 대퇴골/근위 경골에서 비조혈·비내피 세포 5,861개 및 ZsGreen+ HC 자손 1,998개 분석. 10x Genomics, Illumina.
- **유전자 조작 마우스 계통**: Col10a1-Cre, Col10a1-memG-mitoS-DD-Cre-DD, Sstr2-CreERT2, Sstr2-CreXER, Pdgfrb-LSL-Dre, Ihh-Dre knock-in 등 다수의 CRISPR 유전자 편집 마우스 제작.
- **계통 추적 (Lineage tracing)**: Col10a1-Cre;Pdgfrb-LSL-Dre;ROSA26-LSL-EYFP/RSR-tdTomato (CPYT) 마우스로 순차적 이중 재조합 추적. Confetti2 clonal 분석, Col2a1-CreERT;ROSA26-nTnG 단일세포 클론 추적.
- **면역형광 (IF)**: 다중 IF 염색으로 Sstr2, Pdgfrb, Kitl, Ncad, Pdpn 등 마커 발현 분석.
- **In vitro CFU-F 및 다분화능 검증**: CPYT 골수 단핵구의 성공적 CFU-F 형성, 3계통(연골·골·지방) 분화능 평가.
- **신피막 이식 (Renal capsule transplantation)**: FACS 분리한 tdTomato+Pdgfrb+Kitl- mpSSC를 면역결핍 마우스 신피막 하 이식, 4주 후 bony organoid 형성 확인.
- **골손상 이식 모델**: mpSSC를 골손상 부위에 이식, 14일 후 자가재생 및 분화 평가.
- **Micro-CT**: 해면골 파라미터 (BMD, BV/TV, Tb.N, Tb.Th, Tb.Sp) 평가.
- **Hgs 조건부 녹아웃**: Col10a1-Cre;Hgsfl/fl 마우스로 HC 특이적 Hgs 결손 → mpSSC 전환 및 해면골 형성에 미치는 영향 분석.

---

## Results

### Sstr2+/Pdgfrb+Kitl- mpSSC의 발굴
- scRNA-seq으로 골격세포 14개 클러스터 중 cluster 1 (mpSSC) 동정: Sstr2 단일 마커 또는 Pdgfrb+Kitl- 조합으로 특이적 표지.
- mpSSC는 성장판 비대층 직하방 골간단(metaphyseal zone, MPZ)에 국한되어 위치.
- CD200+CD51+Thy1-Ly51-CD105- 시그니처와 부분적 중첩.

### mpSSC는 HC의 직접적 자손
- Col10a1-ZsGreen HC 자손 scRNA-seq: HC → mpSSC → tBMSC → RetiC/OLC 분화 궤적.
- Slingshot pseudotime: HC → mpSSC → tBMSC 분화 연속체 확인. SCENT 분석: mpSSC가 가장 높은 분화능 entropy.
- Col2a1-CreERT;nTnG 클론 추적으로 단일 HC → Sstr2+ mpSSC 전환 생체 내 증명.
- Acan-CreERT2;nTnG 단기 추적: HC 자손의 51.4%가 Sstr2+ mpSSC.
- 신피막 이식: HC 조직이 tdTomato+Pdgfrb+ 세포로 전환됨을 확인.

### mpSSC는 생체 내 SSC 기능 수행
- Ihh-Dre;Sstr2-CreERT2;Confetti2 클론 분석: Sstr2+ 세포가 자기재생능 (Confetti+ 클론 내 Sstr2+ 세포 유지) 및 다분화능 (Sstr2+ → BMSC, OLC로 분화) 보유.
- CPYT 마우스: EYFP+tdTomato+ (HC→Pdgfrb 발현 이력) 세포가 Sstr2+ mpSSC, Sstr2-Pdgfrb+ BMSC, Ncad+ OLC, Pdpn+ 골세포로 분화.
- P30 이후에도 Sstr2+ 세포 유지 → 장기적 자기재생능.

### In vitro/ex vivo SSC 기능
- CPYT 골수 CFU-F: EYFP+tdTomato+ 세포만이 CFU-F 형성 (EYFP+tdTomato- 세포는 불가). 30개 클론 중 9개가 3계통 분화능, 3개는 2회 계대 후에도 유지.
- FACS 분리 tdTomato+Pdgfrb+Kitl- mpSSC → 신피막 이식: bony organoid 형성 (Sox9+ 연골, Ncad+ OLC, Pdgfrb+/Kitl+ 기질세포).
- 골손상 이식: mpSSC가 자신의 구획 재생 (tdTomato+Pdgfrb+Kitl- 유지) 및 다양한 자손 생성.

### MpSSC는 HC 자손의 대부분을 생성
- CPYT 마우스 시계열 분석: P1에서 EYFP+tdTomato+: EYFP+tdTomato- = 1:2.19 → P7에서 77.1%로 역전 → P30에서 96.7%.
- 해면골(trabeculae): EYFP+tdTomato+ 세포가 80.0% (P7) → 99.5% (P30) 차지 → mpSSC가 HC 자손의 대부분 및 해면골 형성 주도.
- Ki67 증식 세포는 EYFP+tdTomato+ 집단에 농축. Sstr2+ 세포의 Ki67+ 비율은 연령 증가에 따라 감소 (P7: 38.2% → P180: 9.0%).

### Hgs는 HC→mpSSC 전환의 핵심 조절자
- HC-1 클러스터 GO/KEGG 분석: endosomal transport pathway 농축 → Hgs (hepatocyte growth factor-regulated tyrosine kinase substrate) 발현 확인.
- Col10a1-Cre;Hgsfl/fl: HC 특이적 Hgs 결손 시 Sstr2+ mpSSC 76.4% 감소. 전체 EYFP+tdTomato+ (Pdgfrb 이력) 세포도 감소.
- Hgs 결손은 HC 자손의 증식/사멸에는 영향 없음 → HC→mpSSC 전환 자체를 손상.
- 대신 EYFP+tdTomato-Ncad+ OLC (HC→OLC 직접 전환 경로)는 1.36배 증가 → 보상 기전.

### Hgs 결손은 해면골 형성 손상
- P30 Hgs KO 마우스: BMSC 및 OLC 집단 현저히 감소.
- Micro-CT: BMD, BV/TV, Tb.N, Tb.Th 유의하게 감소, Tb.Sp 증가.
- P90에서는 부분적 회복 → 다른 SSC 집단(골막 유래 등)의 보상 작용 시사.
- 골수 BMSC (Lepr-Cre)에서 Hgs 결손 시 정상 → HC 특이적 현상.

---

## Perspective

- 본 연구는 HC에서 유래하여 골간단에 위치하는 새로운 SSC 집단인 mpSSC (Sstr2+/Pdgfrb+Kitl-)를 발굴하고, 이들이 출생 후 해면골 형성의 주요 세포 공급원임을 규명하였다.
- HC→mpSSC→tBMSC/OLC로 이어지는 분화 계층을 정립하고, HC가 mpSSC로 탈분화(dedifferentiation)하는 과정이 연골내 골화의 핵심 과정임을 입증하였다.
- Hgs/endosomal transport 경로가 HC→mpSSC 전환에 필수적임을 발견하였으며, 이 경로 손상이 해면골 형성 장애를 초래함을 보였다.
- 기존에 보고된 다양한 골수 기질세포(BMSC) 집단 (Gli1+, Lepr+, Grem1+, Osterix+ 등)이 mpSSC의 하위 자손임을 제안하여 SSC 계층을 통합적으로 이해할 수 있는 틀을 제공한다.
- 골다공증, 골형성 부전증 등 해면골 질환의 병리 기전 이해와 치료 전략 개발에 새로운 표적(mpSSC, Hgs 경로)을 제시한다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
