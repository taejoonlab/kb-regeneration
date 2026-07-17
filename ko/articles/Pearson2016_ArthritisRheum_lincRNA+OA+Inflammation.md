---
tags: [2026-06, Chondrocyte]
extract: 2026-06-08
log:
  - "2026-06-08 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# Long Intergenic Noncoding RNAs Mediate the Human Chondrocyte Inflammatory Response and Are Differentially Expressed in Osteoarthritis Cartilage

## Citation (NLM)
Pearson MJ, Philp AM, Heward JA, Roux BT, Walsh DA, Davis ET, Lindsay MA, Jones SW. Long Intergenic Noncoding RNAs Mediate the Human Chondrocyte Inflammatory Response and Are Differentially Expressed in Osteoarthritis Cartilage. Arthritis Rheumatol. 2016;68(4):845-56. doi:10.1002/art.39520

**DOI:** [https://doi.org/10.1002/art.39520](https://doi.org/10.1002/art.39520)

---

## Background
골관절염(OA)은 연골 퇴행을 특징으로 하는 질환으로, 염증이 OA 연골 병리의 중요한 동인(driver)으로 인식되고 있다. OA 관절의 활막액에서는 여러 전염증성 사이토카인이 증가되어 있으며, 사이토카인 자극이 OA 관절 내 병리적 변화를 유발한다. 짧은 비암호화 RNA인 microRNA(miRNA)가 염증 반응을 조절한다는 증거는 축적되었으나, 긴 비암호화 RNA(lncRNA) — 특히 long intergenic noncoding RNA(lincRNA), antisense RNA, pseudogene — 가 OA 연골세포 염증 반응에서 수행하는 역할은 거의 알려져 있지 않다. 본 연구는 RNA sequencing을 통해 인간 일차 OA 연골세포의 염증 반응과 관련된 lncRNA를 발굴하고, 이들의 OA에서의 발현과 기능을 탐색하고자 하였다.

## Key Experiment Methods
1. 고관절 및 슬관절 전치환술을 받은 OA 환자와 사후 공여자 및 대퇴골 경부 골절 환자로부터 비-OA 연골 조직을 수집
2. Collagenase IIA 소화법을 통한 일차 연골세포 분리 및 배양
3. IL-1β(1 ng/mL) 자극 후 RNA 추출, ribosomal RNA 제거 및 Illumina HiSeq 2000을 이용한 RNAseq (100-bp paired-end, stranded)
4. Tophat2/Cufflinks 파이프라인을 활용한 전사체 어셈블리 및 Gencode v19, Human LincRNAs Catalog와 비교하여 lncRNA 동정
5. CuffDiff를 이용한 차별 발현 분석 (FDR < 0.05, fold change > 2, FPKM 변화 > 1)
6. LNA longRNA GapmeR을 이용한 CILinc01 및 CILinc02 knockdown (TC28 연골세포주)
7. Luminex 기반 Bio-Plex Pro 17-plex cytokine immunoassay를 통한 염증성 사이토카인 분비 측정
8. qRT-PCR을 통한 OA 및 비-OA 연골 조직에서의 lincRNA 발현 확인

## Results
1. 인간 OA 연골세포에서 983개의 lncRNA가 동정되었으며, 이 중 642개 lincRNA, 124개 antisense RNA, 217개 pseudogene이 포함됨
2. 158개 lincRNA와 25개 antisense RNA는 기존 데이터베이스에 없는 새로운 전사체임
3. IL-1β 자극 후 125개 lncRNA(93개 lincRNA 포함)가 차별 발현되었으며(106개 상향, 19개 하향), 이 중 37개(30%)는 새로운 lncRNA임
4. PACER(p50-associated COX-2-extragenic RNA)를 포함한 8개의 염증 관련 lincRNA(CILinc01-07)가 동정됨
5. PACER, CILinc01, CILinc02는 고관절 및 슬관절 OA 연골에서 비-OA 연골에 비해 유의하게 감소함
6. 이들 lincRNA는 IL-1β, TNF, visfatin, leptin 등 여러 전염증성 사이토카인에 대해 빠르고 일시적으로 유도됨
7. CILinc01 knockdown은 IL-1β 자극 하 IL-6, IL-8, TNF, MIP-1β, G-CSF 분비를 유의하게 증가시켰으며, CILinc02 knockdown은 IL-6 분비를 증가시킴
8. IKK-2 억제제(TPCA-1) 처리 시 IL-1β 유도 CILinc01 및 CILinc02 발현이 유의하게 감소하여, NF-κB 경로가 이들의 발현을 조절함을 시사

## Perspective
본 연구는 RNAseq을 이용하여 인간 일차 OA 연골세포의 lncRNA 프로파일을 최초로 규명하고, 염증 반응과 관련된 lncRNA의 광범위한 변화를 보고하였다. CILinc01과 CILinc02는 OA 연골에서 감소되어 있으며, 이들의 knockdown이 염증성 사이토카인 생성을 증가시킨 점은 이들 lincRNA가 연골세포 염증 반응의 음성 조절자(negative regulator) 역할을 함을 시사한다. 이는 OA 연골에서 CILinc01/02의 감소가 염증 조절 능력 상실로 이어져 염증 매개 연골 퇴행에 기여할 가능성을 제기한다. PACER의 OA 연골에서의 감소는 PTGS2/COX-2 경로의 항염증 기능 및 염증 해소(resolution) 능력 저하와 연관될 수 있다. 흥미롭게도 염증 관련 lincRNA 발현 패턴이 고관절과 슬관절 OA 간 차이를 보여, 해부학적 위치에 따른 OA 이질성을 lncRNA 수준에서 확인하였다. 향후 CILinc01/02의 작용 기전 및 다른 연골세포 염증 관련 lincRNA의 OA 병리에서의 역할 규명이 필요하며, 이는 새로운 치료 표적 발굴로 이어질 수 있다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-08*
