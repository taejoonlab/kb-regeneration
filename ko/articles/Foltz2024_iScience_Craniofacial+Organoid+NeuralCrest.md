---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
---

# Craniofacial chondrogenesis in organoids from human stem cell-derived neural crest cells

## Citation (NLM)
Foltz L, Avabhrath N, Lanchy JM, Levy T, Possemato A, Ariss M, Peterson B, Grimes M. Craniofacial chondrogenesis in organoids from human stem cell-derived neural crest cells. iScience. 2024 Apr 19;27(4):109585. doi:10.1016/j.isci.2024.109585

**DOI:** [https://doi.org/10.1016/j.isci.2024.109585](https://doi.org/10.1016/j.isci.2024.109585)

---

## Background

두개안면 재건술은 선천적 기형, 두경부암 치료, 외상성 안면 손상 등에서 필요하지만, 이식 조직의 거부반응과 공여부 이환율이 문제가 된다. 줄기세포를 이용한 두개안면 연골 재생은 이를 혁신적으로 개선할 수 있는 잠재력을 지닌다. 두개안면 연골은 관절 연골과 달리 신경릉(neural crest)에서 기원하며, 연골세포로의 분화를 조절하는 신호전달 경로에 대한 인간 특이적 지식은 아직 불완전하다. 본 연구는 인간 배아줄기세포(hESC) 및 유도만능줄기세포(iPSC) 유래 신경릉 줄기세포(NCSC)로부터 자가조직화(self-organizing) 두개안면 연골 오가노이드를 제작하고, snRNA-seq 및 단백질체학을 통해 분화 기전을 종합적으로 규명하고자 하였다.

---

## Key Experiment Methods

1. **NCSC 분화 프로토콜**: hESC/iPSC → neuroectoderm (dual SMAD 억제: LDN193189 + SB431542) → NCSC 지정 (CHIR99021/WNT 활성화, Shh, FGF8, ascorbic acid, BDNF) → p75/NGFR MACS 선별 → Poly-L-ornithine/laminin/fibronectin 코팅 접시에서 단층 배양. NCSC는 FGF2/EGF 유지 배지에서 배양.

2. **오가노이드 형성**: NCSC가 합류(confluent) 상태에 도달하면 자연적으로 응집하여 접시 표면에서 탈리, 부유성 오가노이드 형성. 최대 1년간 생산 유지 가능.

3. **snRNA-seq (single nuclei RNA sequencing)**: 10x Genomics 기반. NCSC (day 1), day 28 및 day 87 분화 세포 분석. Seurat 클러스터링, UMAP/t-SNE 시각화.

4. **TMT 질량분석법 (TMT-MS)**: hESC(WA09), 신경줄기세포(NSC), NCSC, 연골 오가노이드의 전단백질체 및 인산화/아세틸화/메틸화 PTM 프로파일링. BioPlanet 경로 분석 및 Pathway Crosstalk Network (PCN) 구축.

5. **조직화학 염색**: H&E, Saffranin O, Toluidine Blue, Weigert's resorcin-fuchsin (탄력섬유). 면역형광: COL2A1, COL1A1, SOX9, COMP, MATN1, DCX, PTPRZ1, DDR1/2, PDGFRA, DCN, TNC 등.

6. **리간드-수용체 상호작용 분석**: connectome 패키지로 세포군 간 autocrine/paracrine 신호 분석.

---

## Results

**1. NCSC→연골 오가노이드 분화 확립** NCSC 단층 배양에서 자발적 응집을 통해 직경 최대 1cm의 오가노이드 형성. 조직학적 염색에서 elastic cartilage 특징 확인: lacunae 내 세포핵, Saffranin O/Toluidine Blue 양성 기질, Weigert's resorcin-fuchsin 양성 탄력섬유. 인간 이개 연골과 유사한 구조.

**2. 세포 집단 동정** snRNA-seq으로 6개 클러스터 확인: NCSC, 연골세포, mesenchyme 세포, neuroblast, melanocyte. 연골세포 클러스터는 collagen (COL2A1, COL11A1 등), proteoglycan (ACAN, VCAN), 탄력섬유 합성 유전자(ELN, FBN1, LOX) 고발현. 면역형광에서 COL2A1은 오가노이드 중심부, COL1A1은 외곽부에 편재.

**3. 단백질체학** TMT-MS로 11,064개 단백질 동정. 연골 오가노이드는 NCSC 대비 25개 연골 마커 및 131개 ECM 단백질 유의미하게 증가. 콜라겐 X(COL10A1)는 미검출 → 비대 분화 없이 탄력연골 표현형 유지. BioPlanet 경로 분석: ECM organization, TGF-β regulation of ECM, Chondroitin sulfate/Dermatan sulfate biosynthesis 등 농축.

**4. Mesenchyme-연골세포 상호작용** Day 28 snRNA-seq에서 mesenchyme 세포(신경릉 유사)와 초기 연골세포(nascent chondrocytes) 두 전구세포 집단 확인. Connectome 분석: mesenchyme(EGF, PTN, WNT3, WNT7B 분비) → 연골세포로의 paracrine 신호 및 연골세포→연골세포 autocrine (ECM-integrin/DDR feedforward) 신호 확인. PTPRZ1+ mesenchyme은 성숙 오가노이드 외곽층에 국한, 중심부에서 COL2A1+ 연골세포로 이행.

**5. ECM의 autocrine 신호 역할** 연골세포가 분비한 ECM 성분들이 직접 integrin/수용체를 통해 연골세포 표현형을 강화하는 feedforward 기전 확인. COL2A1-integrin α5, collagen receptor DDR2, proteoglycan 신호 경로 동정. ECM 제거 시 연골 표현형 소실 → ECM이 단순한 구조적 지지체를 넘어 세포 운명 결정에 필수적임을 시사.

---

## Perspective

본 연구는 인간 신경릉 줄기세포로부터 자가조직화 두개안면 연골 오가노이드를 제작하고 snRNA-seq 및 전단백질체 분석을 통해 두개안면 연골 형성의 세포 및 분자 기전을 종합적으로 규명한 첫 연구이다.

주요 의의: (1) 기존 중배엽 기원 연골과 달리 신경릉 기원 연골의 특이적 분화 경로를 제시하였으며, (2) mesenchyme-연골세포 간 paracrine 신호 및 ECM 기반 autocrine feedforward 신호가 연골 형성을 주도함을 밝혔다. (3) 오가노이드가 비대 분화 없이 탄력연골 표현형을 장기간 유지하여 두개안면 재생에 적합한 세포원으로서 가능성을 보였다.

향후 과제: (1) 오가노이드의 in vivo 이식 후 안전성 및 기능 검증, (2) mesenchyme 세포의 신경릉 기원 여부 및 전구세포로서의 완전한 특성 규명, (3) 환자 특이적 iPSC 유래 오가노이드를 활용한 두개안면 기형 질환 모델링 및 약물 스크리닝, (4) articular cartilage 재생을 위한 중배엽 기원 연골 형성 프로토콜과의 체계적 비교가 필요하다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
