---
tags: [2026-07]
extract: 2026-07-16
---

# 단일세포 유전자 발현 분석이 발생 중인 인간 신경세포에서 구별되는 세포 하위집단의 조절자를 밝히다 (Single-cell gene expression analysis reveals regulators of distinct cell subpopulations among developing human neurons)

## Citation (NLM)
Wang J, Jenjaroenpun P, Bhinge A, Espinosa Angarica V, Del Sol A, Nookaew I, Kuznetsov VA, Stanton LW. Single-cell gene expression analysis reveals regulators of distinct cell subpopulations among developing human neurons. Genome Research. 2017;27(11):1783-1794. doi:10.1101/gr.223313.117

**DOI:** [https://doi.org/10.1101/gr.223313.117](https://doi.org/10.1101/gr.223313.117)

---

## Background
개별 인간 신경전구세포(NPC)가 성숙 신경세포로 분화하는 것을 지배하는 확률적 동역학과 조절 기전은 여전히 불완전하게 이해되고 있다. 인간 배아 줄기세포(hESC)와 오가노이드 배양은 초기 발생의 여러 측면을 재현하지만, 세포 혼합물의 이질성과 드물고 수명이 짧은 세포 운명 전이의 존재로 인해 벌크 유전체학으로는 세포 운명 결정의 기저를 이루는 분자 변화를 분해하기 어렵다.

단일세포 RNA 시퀀싱(scRNA-seq)은 새로운 세포 유형을 식별하고, 발생 동역학을 확립하며, 이산적 세포 상태 전이를 밝힐 수 있다. 그러나 대부분의 계산적 궤적 방법(Monocle, Wanderlust, Wishbone, SLICER, Diffusion Pseudotime, SCUBA)은 강박적으로 모든 세포를 매끄러운 연속 궤적으로 정렬하여, 불연속적 발생과 확률적 운명 변화를 놓칠 수 있다. 본 연구에서 저자들은 hESC 유래 후뇌/척수 신경세포의 분화 과정에서 NPC 아형과 중요한 발생 분기점을 규명하기 위한 비지도, 고해상도 전략을 개발한다.

---

## Key Experiment Methods
1. GSK3, SMAD, NOTCH의 소분자 억제제를 이용하여 hESC(H9 계통)를 SOX2+/NESTIN+ NPC로 분화; 이후 신경영양인자(BDNF, GDNF, cAMP)로 30일에 걸쳐 비지향적 신경세포 분화를 유도하여, 주로 TUJ1+/MAP2+ 후뇌/척수(HOX+) 신경세포를 생성.
2. Fluidigm C1 시스템을 이용하여 이산적 시점(0, 1, 5, 7, 10, 30일; 두 번째 실험에서는 0, 3, 7, 14일)에 단일세포 포획; Illumina Nextera XT로 라이브러리 준비 및 개별 전사체 심층 시퀀싱(최종 483개 고품질 세포에 걸쳐 8957개 유전자).
3. hg19에 리드 매핑(TopHat/Bowtie2), HTSeq-count로 정량, DESeq2로 정규화; single-cell differential expression(SCDE)으로 차등 발현 유전자 식별, 528개의 "동적 분류자(dynamic classifier, DC)" 유전자 도출(fold change >1.5, P < 10⁻⁷).
4. 각 시점에서 비지도 계층적 클러스터링(pvclust, 부트스트래핑)을 수행하여 하위집단 정의; 공통 DEG와 인접 시점 간 Pearson 상관을 이용하여 계통 연결 확립.
5. 검증된 상호작용의 MetaCore 데이터베이스를 이용하여 하위집단 특이 유전자 조절 네트워크 재구성; 195개의 차등 발현 전사인자와 138개의 lincRNA 식별.
6. NPC에서 렌티바이러스(plko.1) shRNA 녹다운과 약리학적 WNT 활성화(CHIR99021)로 후보 조절자를 기능적으로 검증, TUJ1/GFAP 면역염색으로 신경세포 분화 정량.

---

## Results
- NPC 집단은 0일에 이질적이었고, 분화 1일 이내에 이질성의 급격한 수축(협조적 유전자 스위치온)을 겪은 후 다시 다양화되어, 30일 신경세포에서 가장 이질적이 되었다.
- 하위집단 추적은 세 계통을 밝혔다: 시작 NPC에 존재하는 두 하위집단("a"와 "b"), 1일에 "b"에서 발생하여 30일까지 지속되는 세 번째("c"); "a"와 "b"는 7일까지 단일 "ab" 계통으로 수렴했다.
- "c" 계통은 "ab"보다 더 일찍 신경세포로 분화했다(신경세포 기능 GO 용어로 농축); "ab"는 유사분열/세포주기 시그니처를 유지하여 미성숙 신경세포를 나타냈다(일부 30일 세포는 여전히 G2/M기에 있음).
- 하위집단 분석은 벌크 분석에서 가려진 유전자 동역학을 드러냈다: 예를 들어 PAX6는 벌크 Q-RT-PCR에서는 변화가 없어 보였으나 "a"에서 급격히 상승하고 "b"에서는 높게 유지되었다; 세포주기 유전자(HMGA1, CENPF)는 "c"에서 가장 빠르게 감소했고 신경세포 마커(DCX, STMN2)는 가장 빠르게 상승했다.
- 알려진 신경발생 조절자(PAX6, MEIS1, ASCL1, NEUROD1, NEUROD4, REST)를 식별하고 새롭게 관여된 조절자를 검증했다: 전사인자 POU3F2와 PBX1, lincRNA MIAT의 녹다운은 각각 신경세포 분화를 유의하게 차단했다; 신경발생에는 WNT5A 하향 조절이 필요했다(CHIR99021이 분화를 차단).
- 유전자 조절 네트워크 분석은 ASCL1이 1일에 "c"의 허브이고 NEUROD1이 5/10일에 허브이며, REST가 PAX6, ASCL1, NEUROD1, MEIS1을 음성 조절하는 마스터 억제자임을 보여주었다; 네트워크 모델링은 ASCL1 또는 NEUROD1 단독으로 "c" 세포를 특정할 수 있음을 뒷받침했다(불연속적, 비순차적 활성화).
- WNT5A는 신경 줄기세포에서 특정 HOX 유전자(HOXC8/9/10, HOXA3)와 공발현되어, 유래된 NPC가 후뇌/척수 정체성으로 계통 제한되어 있음과 부합했다.

---

## Perspective
본 연구는 매끄러운 궤적 방법이 가리는 드물고 일과성인 하위집단(1일 "c" 계통)을 포착하면서 연속적·불연속적 발생 과정을 모두 분해하는, scRNA-seq 시간 경과 분석을 위한 실험적·계산적 프레임워크를 제공한다. 하위집단 특이 동역학을 기능적 검증과 결합함으로써, POU3F2, PBX1, MIAT를 후뇌/척수 신경세포 분화의 중요한 초기 조절자로 식별한다. 척수 생물학과의 관련성은 인간 후뇌/척수 신경발생의 in vitro 모델(HOX+ 신경세포)을 사용한 데 있으며, 발생 중인 척수 신경세포에 대한 후보 조절자와 마커를 제공한다. 저자들이 언급한 한계로는 보수적인 하위집단 판정(실제로는 두 개 이상의 하위집단이 존재할 가능성), 시점당 제한된 세포 수, 녹다운 시 관찰된 계통 이동의 부재 — 계통 분기 예측을 검증하려면 엄격하게 통제되고 시간적으로 분해된 교란이 필요함을 나타냄 — 이 있다. 이 접근은 다른 발생 또는 자극 반응 과정에도 일반화할 수 있다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
