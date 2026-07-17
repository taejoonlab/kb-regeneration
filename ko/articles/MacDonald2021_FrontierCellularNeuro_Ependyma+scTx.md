---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p05.txt
---

# Single Cell Transcriptomics of Ependymal Cells Across Age, Region and Species Reveals Cilia-Related and Metal Ion Regulatory Roles as Major Conserved Ependymal Cell Functions

## Citation (NLM)

MacDonald A, Lu B, Caron M, Caporicci-Dinucci N, Hatrock D, Petrecca K, Bourque G, Stratton JA. Single Cell Transcriptomics of Ependymal Cells Across Age, Region and Species Reveals Cilia-Related and Metal Ion Regulatory Roles as Major Conserved Ependymal Cell Functions. Front Cell Neurosci. 2021;15:703951. doi:10.3389/fncel.2021.703951

**DOI:** [https://doi.org/10.3389/fncel.2021.703951](https://doi.org/10.3389/fncel.2021.703951)

---

## Background

뇌실막세포(ependymal cell)는 방사형 신경교세포(radial glia)에서 발생하는 섬모-상피성 신경교세포로, 뇌의 뇌실계와 척수의 중심관(central canal)을 따라 배열한다. 이들은 뇌척수액(CSF) 항상성, 뇌 대사, 노폐물 청소에 필수적이며, 발달 질환·암·신경퇴행성 질환과 연관된다. 섬모 수와 위치에 따라 세 가지 아형이 정의된다: E1(다섬모; 성체 전뇌 뇌실에서 우세), E2(이섬모; 척수 중심관과 제3/4뇌실 일부를 형성), E3(단섬모; 제3뇌실 특정 부위에 국한). 그 중요성에도 불구하고 뇌실막세포는 여전히 연구가 부족하다.

본 연구에서는 공개된 단일세포 RNA 시퀀싱(scRNA-seq) 데이터셋을 활용하여 연령, 신경계 영역, 종에 걸친 뇌실막세포 유전자 서명의 보존성과 차이를 규명하고, 조직에서 핵심 발견을 검증한다.

---

## Key Experiment Methods

1. 공개 scRNA-seq 데이터셋 스크리닝으로 고품질 뇌실막세포 식별; 네 개 데이터셋 사용: 신생아 마우스 전뇌(GSE123335), 성체 마우스 전뇌(GSE100320), 마우스 척수(PanglaoDB SRA667466), 성체 인간 전뇌(공동저자 제공).
2. Seurat(v4.0.1) 품질관리 및 클러스터링; 뇌실막 클러스터는 마커 유전자 Foxj1, Pifo, Dynlrb1/Dynlrb2로 식별(방사형 신경교세포는 Gfap로).
3. 신생아 뇌실막세포와 방사형 신경교 전구세포의 Slingshot 유사시간(pseudotime) 정렬로 미성숙 대 성숙 유전자 서명 정의.
4. 뇌실막 클러스터별 상위 200개 차등발현유전자에 대한 GO-term 농축분석(clusterProfiler v3.18.1); 상위 30개 GO-term을 데이터셋 간 비교.
5. 마우스 신생아·성체·척수 데이터셋 통합(SCTransform)으로 영역/연령 특이적 차등발현유전자 식별.
6. 신생아 및 성체(생후 12주) 마우스 뇌, 마우스 척수, 성체 인간 뇌 부검 조직에서 Foxj1, Fam183b, Mt3(metallothionein 3), Rarres2에 대한 RNAscope in situ hybridization 검증.

---

## Results

- 각 데이터셋에서 단일 뇌실막 클러스터(Foxj1+, Pifo+, Dynlrb1+)가 식별되었다. 성숙 뇌실막세포는 출생 후 0일에 이미 검출 가능하다: 신생아 유사시간에서 도출한 상위 "성숙 상태" 유전자 15개 중 14개(Lrrc1, Meig1, Fam183b, Foxj1 등)가 성체 세포에서도 높게 발현된 반면, 미성숙 상태 유전자(Phyhipl, Ncan, Bcan)는 성체에서 부재했다.
- RNAscope로 두 연령 모두에서 뇌실 내벽을 따라 Foxj1과 Fam183b를 확인했으며, 신생아 뇌에서는 발현이 내측벽에 국한(Foxj1 ~34%, Fam183b ~20%)되어 내측-외측 발달 진행을 뒷받침했다.
- GO-term은 연령과 종에 걸쳐 세 개의 보존된 범주로 클러스터링되었다: 섬모 관련, 금속이온 관련, 수송 관련. 섬모 관련 항목이 우세했다(신생아 20/30, 성체 마우스 15/30, 인간 20/30). 금속이온 조절 기능이 두드러지게 과대표현되고 보존되었다(신생아 4/30, 성체 마우스 9/30, 인간 8/30; 척수 8/30).
- 금속이온 완충 유전자 Metallothionein 3(Mt3)은 모든 뇌실 및 척수 중심관 내벽에서 높게 발현(74.6-100%)되었고, 성숙 뇌실막세포가 아직 없는 신생아 외측 경계에서도 발현되어 금속이온 기능이 완전 성숙 이전에 시작될 수 있음을 시사했다. MT3은 성체 인간 뇌실 내벽에서도 확인되었다.
- 영역/연령 차이: 척수(E2) 뇌실막세포가 가장 뚜렷하게 구별되며, "oligodendrocyte differentiation" GO-term에 고유하게 농축되고 Plp1을 상향조절했다. 수송 관련 GO-term(예: Aquaporin-4 주도)은 전뇌(E1)에서 두드러졌으나 척수에서는 부재했다. 신생아 고유 유전자로 Ccdc104/Ccdc19(섬모 발달), 성체 뇌 고유 유전자로 Rarres2(Chemerin; 염증)가 포함되었다.
- Rarres2는 성체 뇌에서 높게(100%), 신생아 뇌에서 미미하게(~12%), 척수에서 검출 불가(0%)로 발현되어, 성체 뇌의 뇌실주위 염증병변 분포와 일치했다.
- 척수(E2) 뇌실막세포는 "negative regulation of neural precursor cell proliferation" GO-term을 고유하게 보유하여, E2 세포가 척수손상 후 재생 반응에 기여하는 반면 E1 세포는 그렇지 않다는 기존 보고와 일치했다.

---

## Perspective

본 리소스형 연구는 뇌실막세포 전사체가 연령·종·아형에 걸쳐 현저히 균질하고 보존되어 있으며, 예상된 섬모 기능뿐 아니라 이전에 과소평가되었던 금속이온 항상성(metallothionein 매개) 역할이 보존되어 산화 스트레스 및 신경퇴행성 질환과 관련됨을 확립한다. 척수/재생 연구 측면에서 가장 두드러진 발견은 척수 중심관 E2 뇌실막세포가 뇌 E1 세포와 전사체적으로 뚜렷이 구별되며, 희소돌기아교세포 분화 및 증식 음성조절 프로그램을 고유하게 발현하여, 척수손상 후 기록된 잠재적 재생 능력과 부합한다는 점이다. 한계로는 데이터셋당 뇌실막세포 수가 적은 점(33-344개), 이질적 공개 데이터셋 의존, 인간 척수 데이터 부재(인간은 뇌에 한정), 소수 유전자에 대해서만 검증된 GO 기반 상관적 기능 추론 등이 있다. 향후 과제로는 질환에서 뇌실막 금속이온 조절을 기능적으로 검증하고, 척수에서 E1 대 E2 재생 차이의 기전적 기반을 규명하는 것이 있다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
