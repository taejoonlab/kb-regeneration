---
tags: [2026-06, Chondrocyte, RawDataAvailable]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
raw_data:
  - "GEO: GSE154381, GSE162033"
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# SOX9 keeps growth plates and articular cartilage healthy by inhibiting chondrocyte dedifferentiation/osteoblastic redifferentiation

## Citation (NLM)
Haseeb A, Kc R, Angelozzi M, de Charleroy C, Rux D, Tower RJ, Yao L, Pellegrino da Silva R, Pacifici M, Qin L, Lefebvre V. SOX9 keeps growth plates and articular cartilage healthy by inhibiting chondrocyte dedifferentiation/osteoblastic redifferentiation. Proc Natl Acad Sci USA. 2021;118(8):e2019152118. doi:10.1073/pnas.2019152118

**DOI:** [https://doi.org/10.1073/pnas.2019152118](https://doi.org/10.1073/pnas.2019152118)

---

## Background

연골은 척추동물의 발달과 성체 생존에 필수적이다. 성장판(growth plate, GP)은 골격 성장을 담당하다가 사춘기에 폐쇄되며, 관절 연골(articular cartilage, AC)은 관절의 구조적·기능적 무결성을 평생 유지한다. SOX9는 배아기 연골형성의 핵심 전사인자로 알려져 있으나, 출생 후 역할은 불분명하였다. 인간에서 SOX9 이형접합 돌연변이는 campomelic dysplasia를 유발하며, 생존 환자는 왜소증과 척추측만증을 보인다. 또한 SOX9는 골관절염(OA)에서 하향 조절된다고 알려져 있다. 연골세포가 osteoblast로 전환될 수 있다는 lineage tracing 연구가 있으나, 이 과정이 transdifferentiation인지 dedifferentiation-redifferentiation인지 불명확하였다. SOX9가 이 세포 가소성(cellular plasticity)을 억제하는 게이트키퍼 역할을 하는지가 본 연구의 핵심 질문이다.

---

## Key Experiment Methods

- **조건부 녹아웃 마우스**: *Sox9*^fl/fl^; *AcanCreERT2*; *R26*^tdT^ 마우스 사용. 타목시펜(tamoxifen) 복강 투여로 성체 연골세포 특이적 *Sox9* 결손 유도. *Sox8/Sox9* 이중 녹아웃 마우스도 병행 분석.
- **조직학적 분석**: Safranin O/Fast Green 염색, H&E 염색으로 성장판 및 관절 연골 구조 평가.
- **골관절염 모델 (DMM surgery)**: 내측 반월상 연골 불안정화 수술(destabilization of the medial meniscus). OARSI 6단계 척도로 OA 중증도 정량화.
- **세포 증식 및 사멸 분석**: EdU 삽입(proliferation), TUNEL assay(apoptosis).
- **레이저 포획 미세절제 + RNA-seq**: 성장판 및 관절 연골을 레이저로 채취하여 전사체 분석 (Illumina NovaSeq; ≥50M reads/sample).
- **RNA in situ hybridization (RNAscope)**: Acan, Ihh, Col10a1, Runx2, Sp7, Bglap, Nt5e, Sox4 등의 RNA를 조직 내 시각화.
- **면역조직화학**: SOX9, RUNX2, osteocalcin, pSMAD2/3, pSMAD1/5/9 단백질 발현 분석.
- **단일세포 RNA-seq (scRNA-seq)**: 10× Genomics Chromium 플랫폼 사용. 원위 대퇴골·근위 경골 골단부 소화 후 단일세포 분리. Seurat v3 및 Monocle 3으로 UMAP 및 pseudotemporal trajectory 분석.
- **일차 연골세포 배양 실험**: *Sox9*^fl/fl^ 갈비연골 연골세포에 Ad-GFP 또는 Ad-CRE 아데노바이러스 감염. TGFβ1(5 ng/mL) 또는 BMP2(200 ng/mL) 처리 후 qRT-PCR 및 Western blot 분석.

---

## Results

### SOX9 발현은 성장판 퇴화 및 관절 연골 노화와 함께 감소
- 4주령 마우스에서 성장판은 크고 SOX9 발현이 풍부하나, 성체/노령 마우스에서 성장판은 크게 축소되고 SOX9 발현도 감소.
- 관절 연골도 노화에 따라 SOX9 발현이 현저히 감소.

### SOX9는 성장판 개방 및 관절 연골 무결성 유지에 필수
- *Sox9* 결손 4주 후 성장판이 2주 내에 폐쇄되기 시작; 프로테오글리칸 소실 및 비대구역 소실.
- 관절 연골도 프로테오글리칸을 소실하나, 구조는 초기에 유지.
- DMM 수술 모델에서 *Sox9* 결손 마우스는 대조군 OARSI 점수 2점 대비 4점으로 훨씬 심한 OA 발생.

### SOX9는 성장판 연골세포의 증식과 생존에 필요하나, 관절 연골세포에서는 불필요
- Sox9 결손 성장판 연골세포(GPC): 증식 중단 (EdU↓), 사멸 증가 (TUNEL↑), MMP13 신호 동반.
- Sox9 결손 관절 연골세포(ACC): 증식·사멸 변화 없음.

### SOX9는 연골 유전자 프로그램의 강력한 발현에 필수
- Sox9 결손 시 Col2a1, Acan, Hapln1, Fgfr3, Ihh, Col10a1 등 췌연골(pancartilaginous) 및 성장판 마커 유의한 하향 조절.
- Sox8은 Sox9 결손을 보상하지 못함.

### SOX9는 하중 부위의 관절 프로그램을 지지하고 OA 유전자를 억제
- Prg4, Smoc2, Clu 등 관절 연골 특이 마커가 내측 대퇴 과두·경골 고원(하중 부위)에서 특이적으로 소실.
- 하중이 없는 부위의 관절 연골 프로그램은 SOX9에 비의존적.
- Sox9 결손 관절 연골에서 OA 관련 유전자 변화: Timp3, Frzb 하향 조절; Adamts5, Vcan, Tnc, Ctsb 상향 조절.

### SOX9는 성장판 및 관절 연골세포의 골모세포화(osteoblastogenesis)를 억제
- Sox9 결손 후 4-7일 내 성장판 GPC에서 Runx2, Sp7 RNA 증가; 10일 후 RUNX2, osteocalcin 단백질 검출.
- 관절 연골에서도 하중 부위 ACC에서 동일한 골모세포 마커 발현 유도.
- Bglap(osteocalcin) 상향 조절 확인 (mature osteoblast marker).
- 내연골 골 내 tdTomato+ 세포의 30-40%가 GPC 유래 골세포임을 확인.

### 연골세포는 골모세포로 전환 시 골격 전구세포 단계를 경유 (dedifferentiation/redifferentiation)
- scRNA-seq UMAP: Sox9 결손 GPC가 후기 증식기·전비대기·비대기를 건너뛰고 terminal GPC → mesenchymal progenitor → OB progenitor → pre-OB → OB 경로로 전환.
- RNA in situ: Sox9 결손 후 Mgp, Nt5e(CD73), Sox4, Mmp13, Ibsp, Postn, Col3a1, Sp7, Col1a1 순차적 발현 확인.
- 이 세포들이 원래 연골 기질 내에 위치함을 확인 → 침입 전구세포가 아닌 연골세포 자체의 전환임을 증명.
- Sox2, Nanog, Oct4(만능 줄기세포 마커) 발현 없음 → 만능 줄기세포 단계로의 역분화는 아님.

### TGFβ 및 BMP 신호가 연골세포 운명 전환에 기여
- Sox9 결손 시 관절 연골에서 pSMAD2/3(TGFβ 신호) 감소; Tgfbr3 하향 조절.
- Sox9 결손 시 pSMAD1/5/9(BMP 신호) 증가; BMP 저해제 유전자(Chrdl2, Grem1, Nog, Bambi) 하향 조절.
- 일차 연골세포 실험: TGFβ1은 Sox9 결손과 시너지로 Col3a1(전구세포 마커) 증가; BMP2는 Sox9 결손 시 SP7 단백질 발현 크게 증가 → BMP 신호 증가가 연골세포의 골모세포 전환에 기여.

---

## Perspective

- 본 연구는 SOX9가 배아기뿐 아니라 출생 후에도 성장판 개방과 관절 연골 항상성 유지에 필수적임을 입증한다.
- 연골세포는 Sox9 발현이 감소하면 dedifferentiation → 골격 전구세포 단계 → redifferentiation의 경로를 통해 골모세포로 전환될 수 있으며, SOX9는 이 전환을 억제하는 gatekeeping 역할을 한다.
- 이 세포 가소성 기전은 골관절염 병리 이해에 새로운 시각을 제공하며, 특히 하중 부위에서 SOX9 감소가 골모세포 전환 및 연골 손상을 초래하는 것은 OA 진행의 메커니즘으로 주목할 만하다.
- BMP 신호 증가와 기계적 자극의 조합이 이소성 골화(heterotopic ossification; fibrodysplasia ossificans progressiva와 유사)를 유발할 수 있다는 가설을 제시한다.
- SOX9 발현 유지 또는 골모세포 전환 경로 차단이 OA 치료 전략이 될 수 있음을 시사한다. 또한, 성장판 폐쇄 조절 인자(에스트로겐 등)와 SOX9 발현의 관계 규명이 향후 중요한 과제이다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- GEO: GSE154381, GSE162033

**본문에 인용된 기타 accession (외부·재사용 데이터):**
- GEO: GSE145477


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
