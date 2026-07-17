---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
extract_file: extract/2026-06-07_p02.txt
log:
  - "2026-06-07 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# A proteomic analysis of chondrogenic, osteogenic and tenogenic constructs from ageing mesenchymal stem cells

## Citation (NLM)

Peffers MJ, Collins J, Loughlin J, Proctor C, Clegg PD. A proteomic analysis of chondrogenic, osteogenic and tenogenic constructs from ageing mesenchymal stem cells. _Stem Cell Res Ther._ 2016 Sep 9;7(1):133. doi: [10.1186/s13287-016-0384-2](https://doi.org/10.1186/s13287-016-0384-2).

---

## Background

중간엽줄기세포(MSC)는 연골, 뼈, 힘줄 등 근골격계 조직으로 분화할 수 있는 능력을 가져 재생의학 및 조직공학에서 중요한 자원으로 주목받고 있다. 그러나 공여자의 나이에 따라 MSC의 표현형과 분화 능력이 어떻게 변화하는지는 명확히 규명되지 않았다. 고령 환자의 MSC 기반 치료제 개발에 있어 노화 관련 기능 저하는 조직 생존력 및 품질에 중대한 영향을 미칠 수 있다. 단백질체학(proteomics)은 특정 세포 표현형을 담당하는 단백질 집단을 규명하고 근골격계 조직의 노화 관련 변화 기전을 통찰할 수 있게 한다. 본 연구는 젊은 및 고령 공여자 유래 인간 골수 MSC로부터 연골형성(chondrogenic), 조골형성(osteogenic), 건형성(tenogenic) 조직공학 construct를 제작하고, 공여자 연령에 따른 단백질체 변화를 label-free LC-MS/MS로 체계적으로 분석하였다.

---

## Key Experiment Methods

**1. 세포 배양 및 분화**

- 젊은(n=4, 21.8±2.4세) 및 고령(n=4, 65.5±8.3세) 공여자 유래 인간 골수 MSC를 passage 4까지 배양
- 각 공여자를 연골형성(3D pellet), 조골형성(2D monolayer), 건형성(3D fibrin gel, SYLGARD 코팅 웰에서 staples로 고정) construct로 분화
- 28일 후 수확, 모든 배양은 5% 산소 조건에서 수행

**2. 분화 검증**

- 연골형성: Alcian Blue/Nuclear Fast Red 염색, aggrecan/COL2A1/SOX9 qRT-PCR
- 조골형성: Alizarin Red S 염색(정량 분석 포함), RUNX2 qRT-PCR
- 건형성: Masson's Trichrome 염색, TEM으로 콜라겐 섬유 배열 확인, COL1A1/SERPINF1/THBS4 qRT-PCR

**3. 단백질 추출 및 시료 준비**

- 연골형성/조골형성: guanidine hydrochloride 추출
- 건형성: 0.1% Rapigest™ 추출
- Bradford assay로 정량 후 in-solution trypsin digestion, C18 tip으로 desalting

**4. LC-MS/MS 및 label-free 정량**

- NanoAcquity UPLC online LTQ-Orbitrap Velos mass spectrometer 사용
- ProgenesisQI™로 피처 정렬, PEAKS® 7 PTM으로 펩타이드 동정(Uniprot human database, FDR 1%, 최소 2 peptides/protein)
- 차등발현(DE) 단백질 기준: FDR p<0.05, ±2-fold regulation

**5. Neopeptide 분석(건형성)**

- Mascot으로 semi-tryptic search, e>0.001 conservatively applied threshold
- 콜라겐, 프로테오글리칸, 글리코단백질의 단편화 패턴 확인

**6. 기능 분석**

- PANTHER, DAVID bioinformatics 6.7, Ingenuity Pathway Analysis(IPA)로 GO, canonical pathway, network 분석
- MatrisomeDB로 ECM 단백질 분류

**7. Western blotting 검증**

- Automated western blotting(Wes Simple Western)으로 COMP, biglycan(건형성), SOD1(연골형성) 정량
- Mann-Whitney test로 통계 분석

---

## Results

**Construct 특성화** Alcian Blue 염색 및 aggrecan/COL2A1/SOX9 발현 증가로 연골형성 확인, Alizarin Red S 염색 및 RUNX2 발현 증가로 조골형성 확인, Masson's Trichrome/TEM/COL1A1 발현으로 건형성 확인하였다. 젊은 및 고령 MSC 유래 construct 간 콜라겐 배열에는 질적 차이가 없었다.

**단백질 동정** 연골형성 2,226개, 조골형성 2,233개, 건형성 615개 단백질이 동정되었다. PCA 분석에서 단백질은 공여자 연령에 따라 클러스터링되었다(연골 71%, 조골 66%, 건 83%).

**연령 관련 차등발현(DE) 단백질** 연골형성 construct에서 128개(고령에서 28개 증가, 100개 감소), 건형성에서 207개(고령에서 201개 증가, 6개 감소), 조골형성에서 4개(FDR 기준)의 DE 단백질이 확인되었다. 조골형성은 2D 배양이었으므로 3D construct와 비교 시 연령 영향이 적게 나타난 것으로 해석되었다.

**Gene Ontology 및 pathway 분석** 모든 construct 유형에서 공통적으로 actin cytoskeleton organization, cell survival/death, antioxidant 변화, cytoskeletal 변화가 영향을 받았다. 연골형성에서는 lipid metabolism(LXR/RXR activation, cholesterol biosynthesis)이 주요 pathway였으며, 건형성에서는 glucose metabolism(glycolysis, gluconeogenesis)과 protein metabolism이, 조골형성에서는 mitochondrial dysfunction이 주요 pathway였다.

**상류 조절인자 분석** 연골형성에서 TGFβ 및 SMAD2/3/4 표적이 억제되는 것으로 예측되었고, 건형성에서는 TGFβ가 활성화되는 상류 조절인자로 확인되었다. HIF1α 표적도 연골형성에서 억제, 건형성에서 활성화 패턴을 보였다.

**ECM matrisome 변화** COL4A2, MMP14, MXRA5, THBS1이 연골형성 및 건형성 construct 모두에서 연령 관련 변화를 보였다. 건형성 construct에서 neopeptide가 고령 MSC에서 유의하게 더 많이 확인되어(14±2.5 vs 2.5±1, p=0.049) ECM turnover 증가를 시사하였다.

**Western blotting 검증** Mass spectrometry 결과와 일치하게, 건형성에서 COMP와 biglycan이 고령 construct에서 높았고(p=0.05), 연골형성에서 SOD1이 고령 construct에서 높았다(p=0.05).

---

## Perspective

본 연구는 MSC 기반 근골격계 조직공학에서 공여자 연령이 construct 단백질체에 미치는 영향을 체계적으로 규명한 최초의 포괄적 단백질체 분석 연구이다. 세 가지 분화 계통 모두에서 산화 스트레스 보호, 세포 사멸/생존, 세포골격 변화가 공통적으로 영향을 받았으며, 각 계통별로 lipid metabolism(연골), glucose/protein metabolism(건), mitochondrial dysfunction(조골)이 특이적으로 영향을 받았다.

고령 MSC 유래 건형성 construct에서 단백질 대사와 ECM turnover가 현저히 증가한 것은 노화 건의 생리적 재형성 기전을 이해하는 데 중요한 통찰을 제공한다. 연골형성에서 lipid metabolism 변화와 염증반응(inflammaging) 소견은 노화 연골의 특성과 일치하며, MSC 기반 연골 치료에서 allogeneic MSC 사용 시 공여자 연령을 고려해야 함을 시사한다.

조골형성 construct에서 연령 영향이 적게 나타난 것은 2D 배양 시스템의 한계로, 향후 3D 조골형성 모델에서의 단백질체 분석이 필요하다. 본 연구에서 규명된 DE 단백질 프로파일은 고령 인구를 대상으로 한 MSC 기반 치료제 개발 시 산화 스트레스 보호에 초점을 맞춘 표적 중재 전략 수립에 유용한 가이드를 제공한다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*