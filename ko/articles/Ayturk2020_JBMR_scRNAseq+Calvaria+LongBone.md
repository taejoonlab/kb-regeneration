---
tags: [2026-07, Ossification]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
---

# Single-Cell RNA Sequencing of Calvarial and Long-Bone Endocortical Cells

## Citation (NLM)

Ayturk UM, Scollan JP, Goz Ayturk D, Suh ES, Vesprey A, Jacobsen CM, Divieti Pajevic P, Warman ML. Single-Cell RNA Sequencing of Calvarial and Long-Bone Endocortical Cells. J Bone Miner Res. 2020;35(10):1981-1991. doi:10.1002/jbmr.4052

**DOI:** [https://doi.org/10.1002/jbmr.4052](https://doi.org/10.1002/jbmr.4052)

---

## Background

단일세포 RNA 시퀀싱(scRNA-Seq)은 수천 개 개별 세포의 전사체를 분해능 있게 파악하여 복잡한 조직 내 세포 유형, 신규 집단, 분화 단계를 검출할 수 있게 한다. 저자들은 scRNA-Seq이 골모세포에 대한 환경적·약리적 교란의 효과를 검출할 수 있는지 물었다. 두 골격 시스템을 분석하였다. (1) 신생 마우스 두개관(calvarium)은 골모세포가 풍부한 고전적 세포원으로, 갓 분리한 세포를 통상 확장 배양 후 in vitro에서 석회화 유도한다. (2) 성체 장골 내피질(endocortical) 세포로, scRNA-Seq이 스클레로스틴 중화항체(SclAbIII)에 의한 골형성(anabolism)을 검출할 수 있는지 검증하였다. 스클레로스틴(SOST)은 LRP5/6를 통해 WNT 신호를 억제하며, 항스클레로스틴 항체는 FDA 승인 골다공증 치료제(romosozumab)이다. Bulk RNA-Seq은 골형성 전사체 증가가 골모세포 수 증가인지 개별 세포 활성 증가인지 구분할 수 없으므로 단일세포 분해능이 필요하였다.

---

## Key Experiment Methods

**1. 두개관 세포 분리 및 in vitro 분화**
- P4 CD-1 마우스 두개관(복제당 6마리, n=2)을 순차적 collagenase/EDTA 처리로 소화
- 일부는 신선 상태로 scRNA-Seq; 나머지는 ascorbic acid·β-glycerophosphate로 12일간 골형성 석회화 유도 후 재시퀀싱

**2. 장골 내피질 세포 분리 및 약물 처리**
- 12주령 C57Bl/6J 수컷에 SclAbIII(25 mg/kg, n=4) 또는 PBS(n=4)를 3일 간격 2회 피하 주사
- 경골·대퇴골 골간에서 골수 세척, 골막 제거, 내골막 노출 후 collagenase 소화; 적혈구 다량인 1차 소화물은 폐기

**3. 단일세포 포획·시퀀싱·군집화**
- 10X Genomics Chromium; 두개관 시료당 ~6000개, 내골막 시료당 ~10,000개 로딩; Illumina NextSeq
- Cellranger + Seurat 파이프라인; t-SNE, 비편향 군집 검출, 세포주기 회귀; Monocle 궤적 분석
- Tabula Muris 골수 참조로 세포 정체성 부여

**4. 차등발현 및 검증**
- edgeR 군집별 차등발현(SclAbIII 대 PBS), 검출역치(세포 >50%가 발현) 적용
- FACS(CD45/F4/80) 및 F4/80 면역세포화학으로 대식세포 비율 검증

---

## Results

**신선 두개관은 골모세포가 풍부하며 분화 구배를 보임**
Seurat이 신선 두개관 세포에서 11개 군집을 검출하였고, 중간엽세포(>75%)에는 Col1a1·Bglap·Dmp1이 구배로 발현되는 골모세포 군집과 18개의 차등발현 전사인자(Mef2c, Satb2, Sp7)가 포함되었다. 연골세포와 αSMA+ 평활근세포도 존재하였다. 신선 두개관 세포의 40% 이상이 골모세포 전사체를 지녔다.

**In vitro 배양은 집단을 재편하고 골모세포를 탈분화시킴**
배양 세포는 별도로 군집화되며 골모세포 계통 마커(Col1a1, Runx2, Sp7, Alpl)를 발현하였으나 성숙 마커 Bglap, Dmp1, Ifitm5는 검출 불가 수준으로 소실되었다 — in vitro 탈분화와 일치. 조혈세포는 ~10–12%에서 ~45–48%로 확장되었고, 대식세포는 ~6%(scRNA-Seq)/2%(FACS)에서 12일 후 ~34%/~51%로 증가하였으며 FACS·F4/80 면역염색으로 확인되었다.

**내피질 세포는 조혈세포 우세, 골모세포 소수**
22개 내피질 군집 중 중간엽/골모세포는 ~13%에 불과(PαS 세포, Bglap·Ifitm5·Dmp1이 구배인 골모세포 군집 #7/#14)하여 골모세포는 ~7%였고, 회수 세포의 >80%가 조혈성이었다. CAR 세포와 αSMA+ 평활근세포도 확인되었다.

**scRNA-Seq은 SclAbIII 골형성 반응을 검출하지 못함**
SclAbIII군과 PBS군 골모세포 간 세포유형 비율이나 단일세포 Col1a1/Bglap/Cpz 발현에 유의한 차이가 없었고 소수 전사체만 변화하였다. 저자들은 이를 검정력 부족(마우스당 ~75개 골모세포, 세포당 ~1500 유전자)으로 돌리며, 검정력 계산상 마우스당 ~250개 골모세포 또는 군당 최대 18마리가 필요하다고 하였다. 다만 신선 분리한 두개관과 내피질 골모세포의 전사체는 매우 일치하여, 골격 기원과 무관하게 공통 골모세포 표현형으로 수렴함을 시사하였다.

---

## Perspective

본 연구는 골격 생물학에 대한 scRNA-Seq의 역량과 현 시점의 한계를 동시에 확립한다. scRNA-Seq이 세포 존재비와 정체성 변화 — 배양 두개관 세포의 대식세포 농축 및 골모세포 탈분화 이동 — 를 검출함을 명확히 보여주며, 막내(두개관)와 연골내/사지(장골) 골모세포가 신선 분리 시 공통 전사체를 공유함을 입증한다.

골화 주제 측면에서 본 연구는 방법론적 기준점이다. 골모세포 계통 분화 구배(전구세포 → 성숙 Bglap+/Dmp1+ 골모세포)를 단일세포 분해능으로 지도화하고, 배양 기반 골화 모델에 영향을 주는 in vitro 탈분화 교란을 문서화하였다 — 이는 볼트의 골/석회화 논문 전반에 쓰이는 두개관 세포·골모세포 분석 해석에 직결되는 주의점이다.

핵심 한계는 민감도이다. 내피질 골모세포 회수가 너무 적어 bulk RNA-Seq이 스클레로스틴 항체 처리 후 검출한 완만한(~1.2배) 골형성 유전자 발현 변화를 검출하지 못하였다. 저자들은 리포터 기반 골모세포 농축(예: Bglap.eGFP, 2.3ColGFP)과 시퀀싱 심도 증가를 제안하여, scRNA-Seq을 내피질 골에 대한 유전적·약리적·환경적 교란 모니터링의 실용 도구로 만들 것을 제안한다.


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
