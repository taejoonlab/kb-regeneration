---
tags: [2026-07, Fibroblast]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
---

# Cross-tissue organization of the fibroblast lineage

## Citation (NLM)

Buechler MB, Pradhan RN, Krishnamurty AT, Cox C, Karabacak Calviello A, Wang AW, Yang YA, Tam L, Caothien R, Roose-Girma M, Modrusan Z, Arron JR, Bourgon R, Müller S, Turley SJ. Cross-tissue organization of the fibroblast lineage. Nature. 2021;593(7860):575-579. doi:10.1038/s41586-021-03549-5

**DOI:** [https://doi.org/10.1038/s41586-021-03549-5](https://doi.org/10.1038/s41586-021-03549-5)

---

## Background

섬유아세포(fibroblast)는 비조혈성 구조 세포로서 장기의 구조를 규정하고 세포외기질(ECM)을 생산·재구성하며, 조직 상주 세포를 지지하고, 섬유화·암·자가면역·상처 치유에서 중심적 역할을 한다. 단일세포 연구로 개별 조직 내 섬유아세포 이질성은 밝혀졌으나, 건강 및 질환 상태의 여러 조직에 걸친 단일세포 수준의 특성화는 부재했다. 섬유아세포 아형은 관절염, 암, 특발성 폐섬유증(IPF) 같은 섬유화 질환을 주도하므로, 섬유아세포 표현형이 맥락 특이적인지 아니면 광범위하게 보존되는지를 이해하는 것은 치료적으로 직접적 의의가 있다. 대식세포가 계통 전반의 핵심 시그니처와 조직 특이적 프로그래밍을 결합하는 방식에 착안하여, 저자들은 섬유아세포 이질성이 정상 상태에서는 조직 유형에 의해, 교란(perturbation) 시에는 질환 맥락에 의해 촉진된다고 가정하고 섬유아세포 계통의 조직화 원리를 규명하고자 하였다.

---

## Key Experiment Methods

**1. 정상 상태 마우스 섬유아세포 지도**
- 16개 비교란 마우스 조직의 scRNA-seq 데이터셋 28개(자체 및 공개 저장소) 통합, n = 120,583개 PDGFRα+ 섬유아세포
- 비섬유아세포 제거, 실험실 간 배치 효과 보정; graph-based 클러스터링으로 10개 클러스터
- 여러 조직에서 FACS 분류한 섬유아세포의 bulk RNA-seq 및 ATAC-seq로 교차검증

**2. 클러스터 주석 및 계통 추론**
- 대표 마커(Pi16+, Col15a1+, Ccl19+, Coch+, Comp+, Cxcl12+, Fbln1+, Bmp4+, Npnt+, Hhip+)와 각 200여 개 DEG로 클러스터 주석
- 기능적 정체성 부여(FRC, red-pulp, MSC/osteolineage, 장, 폐포, 세기관지주위 섬유아세포)
- Pi16+ 클러스터를 뿌리로 한 Slingshot pseudotime 궤적 추론

**3. DptIRESCreERT2 계통추적 마우스**
- 표면 마커 LY6C와 SCA1으로 11개 조직에서 Pi16+(LY6C+SCA1+), Col15a1+(LY6C−SCA1+), 특수화(SCA1−) 섬유아세포를 유세포 분석으로 구분
- DptIresCreERT2;Rosa26LSLYFP 마우스 제작; tamoxifen 사료 14일로 Dpt+ 세포 및 후손을 YFP로 비가역 표지
- 폐와 소장에서 Dpt 및 Pi16 RNAscope; Ccl19YFP 및 Grem1CreERT2 리포터와 비교

**4. 교란 상태 마우스 지도**
- 13개 교란 조직(감염, 손상, 암, 섬유화, 대사, 관절염)의 scRNA-seq 데이터셋 17개 통합, n = 99,596개 세포; 10개 클러스터
- 교란 특이적 활성화 클러스터(Cxcl5+, Adamdec1+, Lrrc15+) 규명; DSS 대장염에서 Grem1을 RNAscope로 검증
- DptIresCreERT2 마우스 피하 종양 모델로 universal 섬유아세포가 LRRC15+ myofibroblast를 생성하는지 검증

**5. 인간 섬유아세포 지도 및 종간 비교**
- 췌장 종양 및 정상 인접조직 scRNA-seq(환자 3명, n = 21,262개 세포); 정상 섬유아세포 클러스터 c8에서 인간 universal 섬유아세포 모듈 정의
- 12개 GTEx 조직(n = 5,961 샘플)에서 universal 섬유아세포 존재 추론
- 인간 교란 상태 지도(PDAC, 대장염, NSCLC, IPF, COVID-19; n = 10,355개 세포, 6개 클러스터) 통합, 인간 질환 시그니처를 마우스 클러스터에 매핑

---

## Results

**정상 상태에서 2개의 universal 및 다수의 특수화 섬유아세포 아형**
정상 상태 마우스 지도는 10개 클러스터로 분해되었다. 거의 모든 조직이 Pi16+ 및 Col15a1+ 클러스터에 기여하여 이들을 *universal*로 규정하였다. Pi16+ 섬유아세포(Pi16, Dpp4, Ly6c1)는 혈관 니치의 외막(adventitial) 기질세포를, Col15a1+ 섬유아세포(Col4a1, Hspg2, Col15a1)는 기저막(basement membrane)을 연상시켰다. 두 아형 모두 줄기세포성 유전자(Cd34, Ly6a/SCA1)를 상향발현했다. 나머지 클러스터는 조직 특수화형(Ccl19+ FRC, Cxcl12+ MSC/osteolineage, Npnt+ 폐포, Hhip+ 세기관지주위)이었다. Slingshot 궤적은 Pi16+에서 출발해 Col15a1+를 거쳐 특수화 클러스터에서 종료되어 발생 위계를 시사하였다.

**Dpt는 universal 섬유아세포를 표지하며 계통추적이 위계를 확인**
유세포 분석으로 11개 조직에서 PDGFRα+ 섬유아세포를 Pi16+, Col15a1+, 특수화 그룹으로 분류하였다. Dermatopontin(Dpt) 발현은 특수화와 역상관을 보이며 두 universal 아형에 모두 농축되었다. DptIresCreERT2;Rosa26LSLYFP 마우스에서 PDGFRα+ 섬유아세포는 강하게 YFP를 발현(재조합 효율 림프절 28.7%~심장 83.7%)한 반면 타 세포 유형은 그렇지 않았다. YFP+ 섬유아세포는 Pi16/Col15a1이 농축되고 Ccl19/Npnt가 결핍되어, Dpt+ 세포가 특수화 섬유아세포와 전사적으로 구별됨을 확인했으며, 저자들은 이를 Dpt+Pi16+ 및 Dpt+Col15a1+ universal 섬유아세포로 명명하였다.

**Universal 섬유아세포는 교란 시에도 유지되며 활성화 myofibroblast를 생성**
교란 상태 마우스 지도는 universal Pi16+ 및 Col15a1+ 클러스터(Dpt 최고)를 유지하면서 교란 특이적 활성화 클러스터를 보였다: Cxcl5+(초기 근손상, PI3K/TNF/NFκB), Adamdec1+(대장염, Il11/Grem1, MAPK), Lrrc15+ myofibroblast(관절염, 상처, 섬유화, PDAC; Cthrc1·Acta2·Postn·Adam12·콜라겐·TGFβ 고발현). Universal Dpt+Pi16+ 섬유아세포가 최고 줄기세포성 점수를 유지했고, 계통 추론은 Dpt+Pi16+ → Dpt+Col15a1+ → 활성화 클러스터로의 궤적을 추적했다. 피하 종양 모델에서 LRRC15+ myofibroblast의 52 ± 7%가 YFP+로, 종양 이식 전 표지된 Dpt+ 세포가 LRRC15+ myofibroblast로 분화함을 보였다.

**섬유아세포 상태는 마우스와 인간 간에 보존됨**
인간 췌장 조직에서 정상 섬유아세포 클러스터 c8은 상위 20개 상향유전자 중 12개를 마우스 Dpt+Pi16+ 또는 Dpt+Col15a1+ 클러스터와 공유하여, 12개 GTEx 조직에서 공발현되는 인간 universal 모듈을 정의하였다. 인간 섬유아세포 활성화는 universal 모듈과 음의 상관(r = −0.54)을 보여 마우스 계통 관계를 반영했다. 인간 c3 CAF 시그니처와 류마티스 관절염·간질성 폐질환·IPF·궤양성 대장염 시그니처는 모두 마우스 Lrrc15+ myofibroblast 클러스터에 국재화했고, 기존에 "inflammatory fibroblast"로 기술된 세포는 universal 클러스터에 정렬되어 완전히 전이하지 않은 universal 섬유아세포임을 시사하였다. 인간 교란 상태 지도는 LRRC15+ 및 ADAMDEC1+ 집단을 확인했으나 마우스 지도에 없는 COVID-19 농축 COL3A1+ myofibroblast 아군을 추가로 발견하였다.

---

## Perspective

본 연구는 섬유아세포 계통을 소수의 조직화 원리로 재정의한다: resource 세포로 작동하는 2개의 universal 전사 아형(Dpt+Pi16+ 및 Dpt+Col15a1+)으로부터 여러 조직과 종에 걸쳐 특수화(정상 상태) 및 활성화(교란 상태) 섬유아세포가 파생된다.

첫째, universal Dpt+ 섬유아세포를 계통 전반의 저장고로 보는 개념은 이전 연구들이 단편적으로 기록한 조직 내 이질성에 통합적 틀을 제공하며, DptIRESCreERT2 knock-in 마우스는 이 저장고를 전향적으로 추적·조작하는 유전학적 도구를 제시한다.

둘째, universal 섬유아세포가 관절염·암·섬유화에 공유되는 병원성 상태인 LRRC15+ myofibroblast(콜라겐·TGFβ 고발현, Postn/Adam12 발현)를 생성함을 증명하여, 보존된 발생 기원을 섬유화 질환에 연결한다. 동일한 universal→활성화 궤적이 지도에 포함된 건, 뼈 등 결합조직에서도 작동하므로, 이는 본 저장소의 섬유화 및 연골/근골격 주제와 직접 연관된다.

셋째, 마우스-인간 보존성과 인간 질환 상동체 패널은 마우스 교란 상태 지도를 인간 섬유아세포 아형 해석의 참조로 만들며, 고유한 COVID-19 COL3A1+ myofibroblast는 적응증 특이적 또는 신호 지속시간 차이가 여전히 종·질환 특이적 상태를 생성할 수 있음을 부각한다.

저자들이 제기하는 미해결 과제로는 아형 간 공간적 동태, 왜 2개의 universal 아형이 존재하는가(노동 분업 가능성), 그리고 어떤 니치나 면역 신호가 특수화 및 활성화를 유도하는가가 있으며, 각각 병원성 섬유아세포 상태의 치료적 표적화를 위한 발판이 된다.


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
