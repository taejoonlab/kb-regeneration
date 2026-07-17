---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
---

# Single-Cell Analysis 연구 정리

본 vault에收录된 논문 중 **single-cell 분석 기술** (scRNA-seq, snRNA-seq, scATAC-seq 등)을 사용하여 연골·골격·줄기세포의 이질성을 규명한 연구들을 정리한다.

---

## 개요

| 구분 | 건수 |
|------|------|
| 전체 논문 | 63편 |
| Single-cell 분석 수행 | 22편 (35%) |
| 주요 기술 | scRNA-seq (20), snRNA-seq (2), snATAC-seq (1) |
| 주요 플랫폼 | 10x Genomics (12), Smart-Seq2 (3), Fluidigm C1 (2) |

---

## 논문 목록

### 1. 인간 배아 골격 발달 멀티오믹 아틀라스

**To2024_Nature** — A multi-omic atlas of human embryonic skeletal development
- **기술:** snRNA-seq + snATAC-seq (10X Multiome), 336,162 nuclei, 12명 (5-11 PCW)
- **분석 조직:** 인간 배아 고관절, 무릎, 어깨, 두개골
- **주요 발견:**
  - 12개 연골세포 하위 집단 확인, 부위별 분포 차이
  - SOX9+ enSC (endoneurial Schwann cells) — 슈반세포와 연골세포 마커 동시 발현, 비정형 연골세포 기원
  - 관절 형성 중 interzone zonation 규명
  - 무릎 골관절염 GWAS 신호는 ArticularChon, 고관절 OA는 Preosteoblast에 집중
- **링크:** [To2024_Nature (ko)](ko/articles/To2024_Nature.md) · [To2024_Nature (en)](en/articles/To2024_Nature.md) · [DOI](https://doi.org/10.1038/s41586-024-08189-z)

---

### 2. 인간 배아 골격 줄기세포 발생

**He2021_CellRes** — Dissecting human embryonic skeletal stem cell ontogeny by single-cell transcriptomic and functional analyses
- **기술:** scRNA-seq (10× Genomics), 19,890 cells (5 WPC limb bud) + 15,680 cells (8 WPC long bones) + 7,287 cells (8 WPC calvaria)
- **분석 조직:** 인간 배아 지아 싹, 장골, 두개골
- **주요 발견:**
  - 16개 세포 집단 동정
  - eSSC (embryonic skeletal stem/progenitor cells) — perichondrium 위치, CADM1/PDPN 마커, FOXP1/2 조절
  - 두개골: NCDC (neural crest-derived cells), FOXP1/2/4 regulon 공유
- **링크:** [He2021_CellRes (ko)](ko/articles/He2021_CellRes.md) · [He2021_CellRes (en)](en/articles/He2021_CellRes.md) · [DOI](https://doi.org/10.1038/s41422-021-00467-z)

---

### 3. 인간 hiPSC 연골분화 single-cell 분석

**Wu2021_NatComm** — Single cell transcriptomic analysis of human pluripotent stem cell chondrogenesis
- **기술:** scRNA-seq (10× Chromium), >19,000 cells (9 time points) + 14,683 cells (WNT inhibition)
- **분석 조직:** hiPSC 유래 연골전구세포 → 3D pellet 연골분화 (3개 hiPSC 계통)
- **주요 발견:**
  - off-target 신경계 (NES, OTX2, SOX2, WNT3A) 및 멜라닌세포 (MITF+) 계통 동정
  - WNT4 = 신경발생 허브, WNT2B = 멜라닌발생 허브
  - WNT 억제(C59)로 4개 연골세포 아집단 확인: 증식형, 조기분화형, 조기성숙형 (COL2A1/ACAN 최대), 성숙-비대형
- **링크:** [Wu2021_NatComm (ko)](ko/articles/Wu2021_NatComm.md) · [Wu2021_NatComm (en)](en/articles/Wu2021_NatComm.md) · [DOI](https://doi.org/10.1038/s41467-020-20598-y)

---

### 4. 인간 배아 장골 chondrocyte differentiation dynamics

**Lawrence2023_bioRxiv** — Single cell transcriptomics reveals chondrocyte differentiation dynamics in vivo and in vitro
- **기술:** scRNA-seq, 72,944 cells (인간 일삼분 hindlimb) + 통합 아틀라스 249,151 cells (5-17 PCW)
- **분석 조직:** 인간 배아 hindlimb 장골; in vitro 연골분화 프로토콜
- **주요 발견:**
  - 연골전구세포 (PRRX1+, TWIST1+, FOXP1/2+), 휴지기/증식형/전비대/비대 연골세포, interzone cells (GDF5+PRG4-/+), 관절연골세포 (PRG4+, AQP1+, TPPP3+) 동정
  - FOXO1 억제 시 연골세포 유전자 발현 증가
  - in vivo vs in vitro highly variable gene match율 58%에 불과
- **링크:** [Lawrence2023_bioRxiv (ko)](ko/articles/Lawrence2023_bioRxiv.md) · [Lawrence2023_bioRxiv (en)](en/articles/Lawrence2023_bioRxiv.md) · [DOI](https://doi.org/10.1101/2023.12.20.572425)

---

### 5. 인간 추간판 single-cell profiling

**Gan2021_BoneRes** — Spatially defined single-cell transcriptional profiling characterizes diverse chondrocyte subtypes and nucleus pulposus progenitors in human intervertebral discs
- **기술:** scRNA-seq (10X Genomics Chromium), 128,833 cells → 108,108 after QC
- **분석 조직:** 건강한 인간 추간판 (NP, AF, CEP)
- **주요 발견:**
  - 9개 root cluster, 6개 연골세포 아집단: 조절형 (BMP2/TGFB1/FGF2), 항상성형 (ACAN/COL2A1), 효과형 (PRG4/CNMD)
  - PROCR+ 다능성 전구세포 (NPPC-3) in NP — 3계통 분화 능력
  - CellChat 분석: PDGF, TGF-β가 NP 핵심 신호전달 네트워크
- **링크:** [Gan2021_BoneRes (ko)](ko/articles/Gan2021_BoneRes.md) · [Gan2021_BoneRes (en)](en/articles/Gan2021_BoneRes.md) · [DOI](https://doi.org/10.1038/s41413-021-00163-z)

---

### 6. 인간 골관절염·가시병 연골세포 비교

**Wang2021_CellDeathDis** — Comparison of the major cell populations among osteoarthritis, Kashin-Beck disease and healthy chondrocytes by single-cell RNA-seq analysis
- **기술:** scRNA-seq (10× Chromium V2), 16,375 cells (KBD 6,140, OA 5,834, healthy 4,401)
- **분석 조직:** 인간 무릎 관절연골 (KBD, OA, healthy)
- **주요 발견:**
  - 건강한 연골에서 7개 세포 집단 (FCs, CPCs, RegCs, preHTCs, HomCs)
  - KBD: HomCs 및 MTCs (mitochondrial chondrocytes, MT-ND1/ATP6/ND2/ND3) 확장
  - OA: CHI3L1+ RegCs 확장
  - CPCs는 두 질환 모두에서 소실
  - Pseudotime: KBD와 OA는 서로 다른 운명 분기에서 갈라짐
- **링크:** [Wang2021_CellDeathDis (ko)](ko/articles/Wang2021_CellDeathDis.md) · [Wang2021_CellDeathDis (en)](en/articles/Wang2021_CellDeathDis.md) · [DOI](https://doi.org/10.1038/s41419-021-03832-3)

---

### 7. 골관절염 연골세포 하위 집단 및 세포 간 통신

**Wang2023_SciRep** — Probing the communication patterns of different chondrocyte subtypes in osteoarthritis at the single cell level
- **기술:** scRNA-seq (GSE104782 재분석), 1,600 cells (OA 환자 10명)
- **분석 조직:** 인간 무릎 OA 연골세포 (7개 아집단)
- **주요 발견:**
  - preHTC是唯一 모든 4가지 통신 역할 (sender, receiver, mediator, influencer) 수행하는 아집단
  - ECs와 FCs는 서로 다른 신호전달 경로를 사용하는 "상호 배타적" 쌍
  - COLLAGEN, LAMININ pathway가 핵심 통신 경로로 동정
- **링크:** [Wang2023_SciRep (ko)](ko/articles/Wang2023_SciRep.md) · [Wang2023_SciRep (en)](en/articles/Wang2023_SciRep.md) · [DOI](https://doi.org/10.1038/s41598-023-41874-z)

---

### 8. 폐경 후 골관절염 신규 연골세포·골아세포 아형

**Liu2025_SignalTransductTargetTher** — Single-cell transcriptomics reveals novel chondrocyte and osteoblast subtypes and their role in knee osteoarthritis pathogenesis
- **기술:** scRNA-seq (STRT), 65,491 cells (대퇴과 osteochondral complex)
- **분석 조직:** 생쥐 대퇴과 osteochondral complex (폐경 후 KOA 모델)
- **주요 발견:**
  - 15개 세포 유형, 26개 cluster
  - 3개 신규 연골세포 아집단: Smoc2+ 혈관형, Angptl7+ 혈관형 (FGF2-FGFR2 경유 혈관형성 촉진), Col1a1+ 골형성형
  - Sparc+ 기능이상 골아세포는 골광화 억제
- **링크:** [Liu2025_SignalTransductTargetTher (ko)](ko/articles/Liu2025_SignalTransductTargetTher.md) · [Liu2025_SignalTransductTargetTher (en)](en/articles/Liu2025_SignalTransductTargetTher.md) · [DOI](https://doi.org/10.1038/s41392-025-02136-8)

---

### 9. SOX9 결손에 의한 연골세포 탈분화·골아세포 재분화

**Haseeb2021_PNAS** — SOX9 keeps growth plates and articular cartilage healthy by inhibiting chondrocyte dedifferentiation/osteoblastic redifferentiation
- **기술:** scRNA-seq (10× Genomics Chromium), distal femur/proximal tibia epiphyses
- **분석 조직:** 생쥐 성장판 및 관절연골 (Sox9 conditional KO)
- **주요 발견:**
  - Sox9 결손 GPCs는 후기 증식형/전비대/비대 단계 skip
  - terminal GPC → mesenchymal progenitor → OB progenitor → pre-OB → OB 경로로 전환
  - 연골세포 탈분화 → 골격전구세포 → 골아세포 재분화 과정 실증
- **링크:** [Haseeb2021_PNAS (ko)](ko/articles/Haseeb2021_PNAS.md) · [Haseeb2021_PNAS (en)](en/articles/Haseeb2021_PNAS.md) · [DOI](https://doi.org/10.1073/pnas.2019152118)

---

### 10. 연골세포 탈분화高分解能 route map

**Chen2022_BoneRes** — A high-resolution route map reveals distinct stages of chondrocyte dedifferentiation for cartilage regeneration
- **기술:** scRNA-seq (Fluidigm C1), 634 cells (P0/P2/P4/P8 passage)
- **분석 조직:** 생쥐 무릎 관절 연골세포 (계대 배양)
- **주요 발견:**
  - 4개 연골세포 아집단: ProC (증식형), EcmC (ECM 생산형), MetC (해당과정/항산화, 조기 탈분화), DegC (기질분해/염증, 후기 탈분화)
  - Pseudotime trajectory: EcmC→MetC→DegC, biphasic 탈분화 모델 제시
- **링크:** [Chen2022_BoneRes (ko)](ko/articles/Chen2022_BoneRes.md) · [Chen2022_BoneRes (en)](en/articles/Chen2022_BoneRes.md) · [DOI](https://doi.org/10.1038/s41413-022-00209-w)

---

### 11. 전비대 연골형성 enhancer landscape

**Darbellay2023_NatCommun** — Pre-hypertrophic chondrogenic enhancer landscape of limb and axial skeleton development
- **기술:** scRNA-seq, E14.5 Col2a1EGFP limb mesenchyme
- **분석 조직:** 생쥐 태아 지아 중간엽, 전비대 연골세포
- **주요 발견:**
  - 8개 cluster (MCT, dermis, PM, tendon, pre-osteoblast, perichondrium, interdigit mesenchyme, chondrocyte)
  - Col2a1 reporter가 전비대 연골세포 특이적으로 라벨링 확인 (Col2a1/Sox9/Foxa2/3/Matn/Fgfr3 고발현)
- **링크:** [Darbellay2023_NatCommun (ko)](ko/articles/Darbellay2023_NatCommun.md) · [Darbellay2023_NatCommun (en)](en/articles/Darbellay2023_NatCommun.md) · [DOI](https://doi.org/10.1038/s41467-024-49203-2)

---

### 12. 인간 신경능선 유래 두안면 연골 오가노이드

**Foltz2024_iScience** — Craniofacial chondrogenesis in organoids from human stem cell-derived neural crest cells
- **기술:** snRNA-seq (10x Genomics), NCSC day 1/28/87
- **분석 조직:** hESC/iPSC 유래 신경능선줄기세포 → 두안면 연골 오가노이드
- **주요 발견:**
  - 6개 cluster: NCSC, chondrocytes, mesenchymal cells, neuroblasts, melanocytes
  - Chondrocyte cluster: COL2A1, COL11A1, ACAN, VCAN, ELN, FBN1, LOX 고발현
  - Day 28: mesenchymal→chondrocyte paracrine signaling (EGF, PTN, WNT3, WNT7B) 및 ECM-autocrine feedforward
- **링크:** [Foltz2024_iScience (ko)](ko/articles/Foltz2024_iScience.md) · [Foltz2024_iScience (en)](en/articles/Foltz2024_iScience.md) · [DOI](https://doi.org/10.1016/j.isci.2024.109585)

---

### 13. 배아 골격줄기세포 Cd168+ 고증식 집단

**Hao2023_JGenetGenomics** — Single-cell transcriptomic analysis identifies a highly replicating Cd168+ skeletal stem/progenitor cell population in mouse long bones
- **기술:** scRNA-seq (공개 데이터셋 통합 분석), 14,116 cells
- **분석 조직:** 생쥐 장골 발달 (E11.5-E18.5 지아 싹, 생후 3주/12주 장골, 골절 치유)
- **주요 발견:**
  - 발달 과정 10개 세포 cluster
  - Cd168+ 고증식성 골연골전구세포 집단 동정
  - Trajectory 분석: 골형성/연골형성 bifurcation 재현
  - Cd168+ 세포는 골절 가골에서 재생 연골세포로 분화
- **링크:** [Hao2023_JGenetGenomics (ko)](ko/articles/Hao2023_JGenetGenomics.md) · [Hao2023_JGenetGenomics (en)](en/articles/Hao2023_JGenetGenomics.md) · [DOI](https://doi.org/10.1016/j.jgg.2023.04.004)

---

### 14. 사골 재생 ABPCs

**Qin2023_Science** — A population of stem cells with strong regenerative potential discovered in deer antlers
- **기술:** scRNA-seq, 74,730 cells (사골 재생 주기 8 time point)
- **분석 조직:** 사골 pedicle 골막 및 성장중심
- **주요 발견:**
  - 8개 세포 집단
  - ABPCs (antler blastema progenitor cells, CX43+FGFR2+) — BMSCs 대비 우수한 골연골분화 능력, 지방분화 능력 없음
  - 공간 분석: AGC differentiation gradient (mesenchymal layer → hypertrophic cartilage layer)
- **링크:** [Qin2023_Science (ko)](ko/articles/Qin2023_Science.md) · [Qin2023_Science (en)](en/articles/Qin2023_Science.md) · [DOI](https://doi.org/10.1126/science.add0488)

---

### 15. 골격줄기세포 distinct types — ocSSC vs pvSSC

**Ambrosi2021_eLife** — Distinct skeletal stem cell types orchestrate long bone skeletogenesis
- **기술:** SmartSeq2 scRNA-seq, 143 ocSSCs + 169 pvSSCs
- **분석 조직:** 생쥐 장골 골격줄기세포
- **주요 발견:**
  - 2개 distinct SSC type: ocSSCs (Acan, Col2a1, Pthr1, Spp1) vs pvSSCs (Pdgfra, Postn; Cxcl12, Igf1)
  - pvSSC는 BMAT의 유일한 기원
  - Ligand-receptor 분석: pvSSCs → Tgfb/Wnt로 ocSSC 운명 지원; ocSSCs → Bmp/Egf 신호 되돌림
- **링크:** [Ambrosi2021_eLife (ko)](ko/articles/Ambrosi2021_eLife.md) · [Ambrosi2021_eLife (en)](en/articles/Ambrosi2021_eLife.md) · [DOI](https://doi.org/10.7554/eLife.66063)

---

### 16. metaphyseal SSC (mpSSC)

**Yang2024_SciAdv** — Identification of the metaphyseal skeletal stem cell building trabecular bone
- **기술:** scRNA-seq (10x Genomics), 5,861 non-hematopoietic/non-endothelial + 1,998 ZsGreen+ HC progeny
- **분석 조직:** 생쥐 원위 대퇴골/근위 경골 metaphysis (P7.5 Col10a1-ZsGreen)
- **주요 발견:**
  - 14개 골격 cluster 중 mpSSC (Sstr2+/Pdgfrb+Kitl-) 동정
  - HC progeny trajectory: HC → mpSSC → tBMSC → RetiC/OLC
  - mpSSCs가 trabecular bone 형성의 대부분 주도
- **링크:** [Yang2024_SciAdv (ko)](ko/articles/Yang2024_SciAdv.md) · [Yang2024_SciAdv (en)](en/articles/Yang2024_SciAdv.md) · [DOI](https://doi.org/10.1126/sciadv.adl2238)

---

### 17. in vitro 배양 연골세포 — MSC 유사 균일 집단

**Karlsen2021_Cartilage** — Single-Cell RNA Sequencing of In Vitro Expanded Chondrocytes: MSC-Like Cells With No Evidence of Distinct Subpopulations
- **기술:** scRNA-seq (Smart-Seq2), 86 cells (OA 환자 연골, Passage 3)
- **분석 조직:** in vitro 배양 인간 관절연골세포 (OA, single donor)
- **주요 발견:**
  - 86개 세포가 단일 균일 집단으로 클러스터링 — distinct subpopulation 없음
  - 배양 연골세포는 MSC 마커 (CD44, CD90, CD73, CD105) 발현
  - adipogenic/osteogenic multilineage 분화 능력 확인
- **링크:** [Karlsen2021_Cartilage (ko)](ko/articles/Karlsen2021_Cartilage.md) · [Karlsen2021_Cartilage (en)](en/articles/Karlsen2021_Cartilage.md) · [DOI](https://doi.org/10.1177/1947603519847746)

---

### 18. Mkx−/− 건골화 single-cell 분석

**Lin2022_BoneRes** — Single cell analysis reveals inhibition of angiogenesis attenuates the progression of heterotopic ossification in Mkx−/− mice
- **기술:** scRNA-seq (Fluidigm C1), 486 cells → 466 after QC (WT vs Mkx−/− tail tendons)
- **분석 조직:** 생쥐 꼬리 건 (WT vs Mkx−/− HO 모델)
- **주요 발견:**
  - 3개 세포 유형: TPC (tendon progenitor), TB (tenoblast), TC (tenocyte)
  - Pseudotime: Mkx−/− TPCs에서 골연골유전자 (Spp1, Ogn, Mgp, Comp) 조기 활성화
  - 혈관형성 유전자가 모든 세포 유형에서 enrichment
- **링크:** [Lin2022_BoneRes (ko)](ko/articles/Lin2022_BoneRes.md) · [Lin2022_BoneRes (en)](en/articles/Lin2022_BoneRes.md) · [DOI](https://doi.org/10.1038/s41413-021-00175-9)

---

### 19. 십자인대 퇴행 single-cell atlas

**Yang2023_eLife** — A Single-Cell Atlas Depicting the Cellular and Molecular Features in Human Anterior Cruciate Ligamental Degeneration
- **기술:** scRNA-seq (10× Genomics), 49,356 cells (healthy 4명 + degenerated 4명 ACL)
- **분석 조직:** 인간 전방십자인대 (건강 vs 퇴행)
- **주요 발견:**
  - 4개 주요 class: fibroblasts (66%), immune (16%), pericytes (10%), endothelial (8%)
  - 10개 fibroblast subset
  - 2개 opposing trajectory: 염증 손상 (Fib.2, Fib.9) vs repair (Fib.10)
  - FGF7-FGFR1, TGFB1-TGFBR2 핵심 신호전달 축
- **링크:** [Yang2023_eLife (ko)](ko/articles/Yang2023_eLife.md) · [Yang2023_eLife (en)](en/articles/Yang2023_eLife.md) · [DOI](https://doi.org/10.7554/eLife.85500)

---

### 20. 청소년 특발성 측만증 (AIS) 세포 풍경

**Yang2021_JORSpine** — Single-cell RNA Seq reveals cellular landscape-specific characteristics and potential etiologies for adolescent idiopathic scoliosis
- **기술:** scRNA-seq (BD Rhapsody), 2,226 AIS + 2,241 control cells (vertebral cancellous bone)
- **분석 조직:** 인간 척추 해질골 (AIS 환자 vs 대조군)
- **주요 발견:**
  - 11개 세포 집단
  - AIS 특이적 MSC-IGFBP5: 골아세포 분화 실패 (저골밀도 기전)
  - AIS 특이적 CPC-PCNA: 연골세포 분화 실패 (비대칭 성장 기전)
  - 면역세포가 AIS에서 현저히 증가
- **링크:** [Yang2021_JORSpine (ko)](ko/articles/Yang2021_JORSpine.md) · [Yang2021_JORSpine (en)](en/articles/Yang2021_JORSpine.md) · [DOI](https://doi.org/10.1002/jsp2.1184)

---

### 21. 후종인대 골화증 (OPLL) single-cell atlas

**Wang2024_BoneRes** — Sorafenib inhibits ossification of the posterior longitudinal ligament by blocking LOXL2-mediated vascularization
- **기술:** scRNA-seq, 51,245 cells (OPLL 3명 + non-OPLL 2명)
- **분석 조직:** 인간 후종인대 (OPLL vs non-OPLL)
- **주요 발견:**
  - 13개 cluster
  - RNA velocity: 인대세포 내피분화 trajectory 확인 — C6 (progenitor) → endothelial/chondrocyte/osteoblast branches
  - LOXL2, HIF1A가 내피분화 중 점진적 증가
  - OPLL 최초 single-cell atlas
- **링크:** [Wang2024_BoneRes (ko)](ko/articles/Wang2024_BoneRes.md) · [Wang2024_BoneRes (en)](en/articles/Wang2024_BoneRes.md) · [DOI](https://doi.org/10.1038/s41413-024-00327-7)

---

### 22. iPSC 유래 건세포 분화 trajectory

**Yoshimoto2022_FrontCellDevBiol** — Tenogenic Induction From Induced Pluripotent Stem Cells Unveils the Trajectory Towards Tenocyte Differentiation
- **기술:** scRNA-seq (modified CEL-Seq2), 4,592 cells (T0/T3/T6/T9)
- **분석 조직:** 생쥐 iPSC 유래 건세포 분화 (ScxGFP reporter)
- **주요 발견:**
  - 11개 cluster: pluripotent, endothelial, early tenogenic progenitors (Aldh1a2+/Acta2+), differentiating tenocytes (Scx+), mature tenocytes (Tnmd+)
  - PHATE trajectory: iPSC → mesodermal → tenocyte 연속 경로
  - RA signaling이 건형성 음성 조절
- **링크:** [Yoshimoto2022_FrontCellDevBiol (ko)](ko/articles/Yoshimoto2022_FrontCellDevBiol.md) · [Yoshimoto2022_FrontCellDevBiol (en)](en/articles/Yoshimoto2022_FrontCellDevBiol.md) · [DOI](https://doi.org/10.3389/fcell.2022.780038)

---

## 비교 요약

### 세포 수 규모

| 논문 | 세포 수 |
|------|---------|
| To2024_Nature | 336,162 nuclei |
| Gan2021_BoneRes | 128,833 → 108,108 |
| Lawrence2023_bioRxiv | 249,151 (통합 아틀라스) |
| Qin2023_Science | 74,730 |
| Liu2025_SignalTransductTargetTher | 65,491 |
| Wang2024_BoneRes | 51,245 |
| Yang2023_eLife | 49,356 |
| He2021_CellRes | 42,857 (3 조직 합계) |
| Wang2021_CellDeathDis | 16,375 |
| Wu2021_NatComm | ~34,000 |
| Hao2023_JGenetGenomics | 14,116 |
| Karlsen2021_Cartilage | 86 |

### 주요 연골세포 아집단 패턴

여러 논문에서 공통적으로 보고된 연골세포 하위 집단:

| 아집단 | 마커 | 보고 논문 |
|--------|------|-----------|
| 증식형/전구세포 | PRRX1, TWIST1, FOXP1/2, Cd168 | Lawrence2023, Hao2023, He2021 |
| 항상성/ECM 생산형 | COL2A1, ACAN, COL11A1 | Wu2021, Gan2021, Foltz2024 |
| 비대형 | COL10A1, MMP13, SPP1 | Lawrence2023, Chen2022, Liu2025 |
| 재생/반응형 | CHI3L1, PRG4 | Wang2021, Wang2023, Gan2021 |
| 혈관형 | SMOC2, ANGPTL7 | Liu2025 |
| 탈분화/퇴행형 | DegC (matrix degradation) | Chen2022, Haseeb2021 |

---

*Processed by **qwen3.6-plus** (OpenCode Go) on 2026-06-07*
