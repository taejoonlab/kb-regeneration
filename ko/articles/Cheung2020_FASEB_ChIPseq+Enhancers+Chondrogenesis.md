---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
---

# Histone ChIP-Seq identifies differential enhancer usage during chondrogenesis as critical for defining cell-type specificity

## Citation (NLM)

Cheung K, Barter MJ, Falk J, Proctor CJ, Reynard LN, Young DA. Histone ChIP-Seq identifies differential enhancer usage during chondrogenesis as critical for defining cell-type specificity. _FASEB J._ 2020;34:5317-5331. doi:[10.1096/fj.201902061RR](https://doi.org/10.1096/fj.201902061RR)

---

## Background

연골세포(chondrocyte)는 관절 연골의 유일한 세포 유형으로, 연골 항상성을 유지하는 역할을 한다. 연골형성(chondrogenesis)은 중간엽 줄기세포(MSC)가 연골세포로 분화하는 다단계 과정으로, SOX9 전사인자가 중심적인 역할을 한다. 유전자 발현은 히스톤 변형(histone modification)과 DNA 메틸화(DNA methylation) 같은 후성유전학적(epigenetic) 기전에 의해 조절되며, 이는 정상 발생과 질병(예: 골관절염, OA) 모두에서 중요하다. 특히 OA 관련 유전적 변이 대부분이 비암호화 영역, 즉 인핸서(enhancer)에 위치하고 있어 연골세포 특이적 인핸서의 후성유전체적 특성 규명이 필수적이다. 본 연구는 인간 MSC의 in vitro 연골형성 과정에서 히스톤 ChIP-seq을 수행하여 염색질 상태(chromatin state) 변화를 포괄적으로 분석하고, 연골세포 인핸서의 세포유형 특이성과 DNA 메틸화 및 SOX9 결합과의 상호작용을 규명하였다.

---

## Key Experiment Methods

**1. hMSC 연골형성 분화**

- 골수 유래 hMSC(LONZA, 여성 2명, 22-24세)를 Transwell 무스캐폴드(scaffold-free) 모델에서 14일간 연골세포로 분화
- 분화 확인: COL2A1, TNBS4, PRG4(관절 연골 마커) 및 COL10A1, PTH1R, ALPL(비대 연골 마커) 상향조절

**2. Histone ChIP-seq**

- 5종 히스톤 변형 ChIP-seq 수행: H3K4me3(활성 프로모터), H3K4me1(인핸서), H3K27ac(활성 인핸서), H3K27me3(전사 억제), H3K36me3(전사 신장)
- Illumina HiSeq 2500(50 bp single-end) 및 NextSeq 500(75 bp single-end) 시퀀싱
- MACS2로 peak calling, ngs.plot으로 유전자 발현 수준별 히스톤 마크 농축 분석

**3. ChromHMM 염색질 상태 모델링**

- ChromHMM(v1.12)을 이용해 hMSC 및 분화 연골세포 데이터로 16개 염색질 상태 모델 학습
- 각 상태별 GREAT GO enrichment 분석
- Riverplot으로 hMSC→연골세포 상태 전이 가시화

**4. Roadmap Epigenomics 데이터와 유사성 분석**

- 98개 세포유형의 18-상태 Roadmap 데이터와 Jaccard 유사도 계수 비교
- 인핸서(9_EnhA1 ↔ 13_EnhS) 중심 계층적 군집화

**5. DNA 메틸화 데이터 통합**

- Infinium HumanMethylation450K BeadChip 데이터(GSE129266)와 염색질 상태 교차분석
- 탈메틸화(de-methylated) CpG의 인핸서 과대표출 통계 검정(Chi-square test, 1000 Monte Carlo permutations)

**6. Luciferase reporter assay**

- 선별된 6개 인핸서 영역(ASPSCR1, TLE3, WWP2, ZMIZ1, LRP5, MYEOV)을 CpG-free pCpGL-EF1 벡터에 클로닝
- In vitro CpG 메틸화(M.SssI) 처리 후 조골세포종 SW1353 세포에서 luciferase 활성 측정
- SOX9 과발현(pUT-FLAG-SOX9 공동형질주입)이 인핸서 활성에 미치는 영향 평가

**7. 모티프 분석 및 SOX9 ChIP-seq 데이터 활용**

- MEME suite(AME)로 연골세포 인핸서의 de novo 모티프 검색
- 공개된 생쥐 늑골 연골세포 SOX9 ChIP-seq(GSE69109) 데이터를 hg38으로 liftOver하여 인간 SOX9 결합 부위 비교

---

## Results

**연골형성 중 염색질 상태의 대규모 변화** 5종 히스톤 변형의 ChIP-seq 데이터는 예상된 게놈 분포(예: H3K4me3의 TSS 농축)를 보였으며, 발현량이 높은 유전자에서 활성 히스톤 마크(H3K4me3, H3K27ac, H3K36me3)의 농축이, 저발현 유전자에서는 억제 마크(H3K27me3)의 농축이 확인되어 데이터 품질이 검증되었다. ChromHMM 16-상태 모델은 hMSC와 분화 연골세포 간의 광범위한 염색질 상태 변화를 보여주었으며(Riverplot), 특히 분화된 연골세포의 강한 활성 인핸서 상태(13_EnhS; H3K4me1+H3K27ac 고농축)에서 연골형성 및 연골 기능 관련 GO 용어(예: cartilage development, skeletal system development)가 유의하게 농축되었다. COL2A1 유전자 주변에서는 hMSC의 억제/비활성 상태에서 연골세포의 전사 허용 상태로의 전환이 뚜렷이 관찰되었다.

**인핸서의 세포유형 특이성** Roadmap Epigenomics 98개 세포유형과의 Jaccard 유사도 분석 결과, 프로모터 등 다른 염색질 상태와 달리 인핸서 상태(9_EnhA1/13_EnhS)에서만 세포유형별 군집화가 명확히 나타났다. 본 연구의 분화 연골세포(CHON)와 Roadmap의 골수-MSC 유래 연골세포가 동일 군집을 형성하였고, hMSC는 근세포, 조골세포, 섬유아세포 등 일차배양 세포군과 근접하여, 서로 다른 모델과 실험실에서도 연골세포 고유의 후성유전체 시그니처가 보존됨을 입증하였다.

hMSC 유래 연골세포 인핸서(23,158개 공통 영역)는 태아 관절 연골보다 성인 관절 연골 인핸서와 더 높은 유사성을 보였다. OA 무릎 연골의 차등 접근성 인핸서 중 1,239개(약 33%)가 본 연구의 인핸서와 중첩되어(hypergeometric test, P < 3.75 × 10⁻⁹⁰), OA에서 탈조절된 인핸서가 연골세포 특이적 인핸서에 농축되어 있음을 확인하였다.

**인핸서 탈메틸화와 후성유전학적 상호작용** 연골형성 동안 탈메틸화된 CpG 부위(전체 차등 메틸화 부위의 94%)가 H3K4me1과 H3K27ac으로 표지된 강한 인핸서(13_EnhS)에 현저히 과대표출되었다. 총 450K 어레이 CpG의 2% 미만만이 13_EnhS 상태에 위치하지만, 탈메틸화된 CpG의 41.8%가 이 상태에서 발견되었다(Chi-square, P < 0.001). Luciferase reporter assay에서 6개 선별 인핸서 영역(ASPSCR1, TLE3, WWP2, ZMIZ1, LRP5, MYEOV) 모두 비메틸화 상태에서 유의한 인핸서 활성을 보였으며, CpG 메틸전이효소 처리 시 모든 영역에서 활성이 유의하게 감소하여 DNA 메틸화가 인핸서 활성을 직접 조절함을 증명하였다.

**SOX9 결합과 인핸서 활성 조절** De novo 모티프 검색에서 연골세포 강한 인핸서 상태에서 SOX9 결합 모티프가 가장 풍부하게 검출되었으며, 이외에 CREB3L1(OASIS), ELF3, HES/HEY 등 골연골 발생 관련 전사인자 모티프도 확인되었다. 연골형성 과정에서 새로 획득된 인핸서(new enhancer)는 분화 전후 지속적 인핸서(constant enhancer)보다 SOX9 모티프 농축도가 유의하게 높았다. 생쥐 늑골 연골세포 SOX9 ChIP-seq 데이터의 liftOver 결과, SOX9 피크의 대부분이 연골세포의 강한 프로모터(2_TssS) 및 강한 활성 인핸서(13_EnhS) 상태와 중첩되었다. Luciferase assay에서 6개 인핸서 중 4개(TLE3 제외)가 SOX9 과발현 시 유의한 활성 증가를 보여 SOX9이 이들 인핸서의 전사 활성을 조절함을 입증하였다.

---

## Perspective

본 연구는 인간 MSC 연골형성 모델에서 5종 히스톤 변형의 ChIP-seq을 통합한 최초의 포괄적 후성유전체 분석으로, 다음과 같은 중요한 발견을 제시한다.

첫째, 연골형성 과정에서 게놈 차원의 대규모 염색질 상태 재프로그래밍이 발생하며, 특히 H3K4me1/H3K27ac으로 정의된 인핸서가 프로모터보다 훨씬 더 세포유형 특이적임을 밝혔다. 서로 다른 in vitro 연골형성 모델과 실험실에서도 연골세포 인핸서 시그니처가 보존되어, in vitro 모델의 신뢰성과 재현성을 뒷받침한다.

둘째, 인핸서 영역의 탈메틸화가 연골형성의 주요 후성유전학적 사건임을 밝히고, DNA 메틸화가 인핸서 활성을 직접 조절함을 기능적으로 증명하였다. 이는 히스톤 변형과 DNA 메틸화라는 두 후성유전학적 기전 간의 상호작용(crosstalk)을 연골세포 분화 맥락에서 규명한 의의를 가진다.

셋째, 연골세포 인핸서에서 SOX9 결합 모티프의 농축을 확인하고, SOX9이 분화 중 새로 활성화되는 인핸서를 통해 연골 형성을 조절함을 제시하였다. SOX9 외에도 CREB3L1, ELF3 등 골연골 질환 관련 전사인자의 인핸서 결합 가능성이 확인되어 질환 연구의 단서를 제공한다.

넷째, OA 연골의 차등 접근성 인핸서가 연골세포 특이적 인핸서와 유의하게 중첩되어, OA 병인이 발생 과정 후성유전체의 재활성화와 연관될 가능성을 지지한다. 이는 연골세포 인핸서가 OA 치료 표적으로서 잠재적 가치를 가짐을 시사한다.

향후 과제로는 (1) 인핸서의 실제 표적 유전자 규명을 위한 염색질 입체형태 분석(3C/Hi-C), (2) 다양한 in vitro 모델과 실제 인간 관절 연골세포 후성유전체의 체계적 비교, (3) 발생-질환 연결고리의 완전한 규명이 필요하다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
