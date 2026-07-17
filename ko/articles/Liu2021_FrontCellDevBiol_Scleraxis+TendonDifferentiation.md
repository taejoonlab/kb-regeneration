---
tags: [2026-07, Tenocyte]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
---

# The Scleraxis Transcription Factor Directly Regulates Multiple Distinct Molecular and Cellular Processes During Early Tendon Cell Differentiation

## Citation (NLM)

Liu H, Xu J, Lan Y, Lim H-W, Jiang R. The Scleraxis Transcription Factor Directly Regulates Multiple Distinct Molecular and Cellular Processes During Early Tendon Cell Differentiation. Front Cell Dev Biol. 2021;9:654397. doi:10.3389/fcell.2021.654397

**DOI:** [https://doi.org/10.3389/fcell.2021.654397](https://doi.org/10.3389/fcell.2021.654397)

---

## Background

건과 인대는 근육의 힘을 뼈로 전달하고 관절을 안정화하는 콜라겐(주로 제1형 콜라겐) 풍부 결합조직이지만, 건 발생과 tenocyte 분화를 조절하는 분자 기전은 잘 알려져 있지 않다. 다수의 유전자 녹아웃 중 basic helix-loop-helix(bHLH) 전사인자 Scleraxis(Scx) 또는 TGFβ 신호의 소실만이 건 발생을 심각하게 교란하며, Scx-null 마우스는 힘 전달 건의 심한 형성저하 또는 결손을 보인다. Scx 기능은 건 전구세포의 시작에는 불필요하나 tenocyte 분화에는 필수적이다. 그러나 지금까지 확인된 Scx 직접 표적은 소수(예: Col1a1, Tnmd)에 불과했고 대부분 in vitro 프로모터 분석에 의존했는데, 이는 생체 내 전장유전체 결합 연구에 쓸 수 있는 특이적 Scx 항체가 없었기 때문이다. 본 연구는 ScxFlag knock-in 마우스를 제작하여 내인성 Scx 결합 부위를 전장유전체 수준에서 지도화하고, 새로운 Scx 녹아웃 계통을 특성화하며, ChIP-seq과 RNA-seq을 통합하여 초기 건세포 분화의 직접 Scx 표적 유전자를 규명한다.

---

## Key Experiment Methods

**1. ScxFlag knock-in 마우스 제작**
- CRISPR/Cas9로 내인성 Scx의 카복시 말단에 2xFLAG epitope 삽입
- ScxFlag/Flag 동형접합체는 멘델 비율로 출생, 표현형 이상 없음(FLAG 태그가 Scx 기능 손상 안 함)
- Anti-FLAG 면역형광으로 Scx-FLAG가 건·인대에 특이적으로 발현됨을 확인

**2. ChIP-seq을 통한 전장유전체 Scx 결합 분석**
- E13.5 ScxFlag/Flag 앞다리로 anti-FLAG ChIP-seq 3중 수행(반복당 앞다리 10쌍)
- STAR 정렬, HOMER peak calling, EdgeR 차등 분석(log2FC > 2, FDR < 0.01)
- De novo motif 분석(HOMER); GREAT(basal-plus-extension)로 peak–유전자 연관

**3. 새로운 Scx 녹아웃 마우스 계통 특성화**
- KOMP Scxtm1.1(KOMP)Vlcg 계통(Scx 코딩 서열을 LacZ 카세트로 치환)
- Sanger 시퀀싱으로 구조 확인; in situ hybridization으로 Scx−/−에서 Scx mRNA 완전 소실 확인
- 골격 표본 및 Scx-GFP 리포터로 건/골격 표현형 평가

**4. Scx 의존 전사체(RNA-seq)**
- Scx−/− 및 대조 littermate의 E15.5 앞다리에서 Scx-GFP+ 세포 FACS 분리
- 성별 보정 RUVseq, DESeq2 차등 발현(FDR < 0.05), GO 분석(ToppGene)

**5. 통합 및 검증**
- ChIP-seq peak과 Scx 의존 차등 발현 유전자의 중첩으로 직접 표적 정의
- 후보 유전자(Fmod, Kera, Htra3, Ssc5d, Tnmd, Zfp185)에 대한 whole-mount·절편 in situ hybridization 및 qRT-PCR(E13.5, E15.5)

---

## Results

**기능적 ScxFlag 마우스로 내인성 Scx 결합의 전장유전체 지도화**
2xFLAG 태그는 Scx 기능을 변경하지 않았고 Scx-FLAG는 건·인대에 강하고 특이적으로 발현되었다. E13.5 앞다리 anti-FLAG ChIP-seq에서 12,097개의 고품질 Scx 결합 peak이 확인되었으며, 약 77%는 intron/intergenic, 약 14%만 프로모터에 위치했다. 가장 농축된 de novo motif는 C-A-G/T-A/C-T-G로 EMSA로 결정된 선호 Scx 결합 motif와 일치했고, 두 번째 motif는 NFAT 컨센서스(TGGAAA)와 일치하여 보고된 Col1a1에서의 Scx–Nfatc4 협력과 부합하였다.

**ChIP-seq은 ECM·건 프로그램에 농축된 Scx 연관 유전자를 회수**
GREAT은 peak을 7,520개 유전자와 연관시켰다. 이전 발생 중 건 RNA-seq과 비교 시, E13.5→E15.5 건 분화 중 상향조절된 970개 유전자 중 490개가 Scx ChIP-seq peak을 가졌고, 이들은 "extracellular matrix organization", "collagen fibril organization", "connective tissue development"에 크게 농축되었다.

**새로운 KOMP Scx 녹아웃 계통은 건 결손을 재현**
Scx−/− 마우스는 멘델 비율로 출생했으나 체구 감소와 심하게 손상된 사지(앞·뒷다리 autopod가 등쪽 굴곡으로 고정), 주요 사지·꼬리 건의 심한 형성저하, 골격 변화(삼각근 조면 결손, 슬개골·종골 부착부 연골 감소, 요추 횡돌기 감소)를 보였다. 건 분화·응축은 E15.5까지 교란되어 이전 보고된 Scx 변이 계통과 일치하였다.

**ChIP-seq/RNA-seq 통합으로 직접 Scx 표적 유전자 규명**
E15.5 Scx-GFP+ 세포 RNA-seq에서 Scx−/−의 유의 변화 유전자 68개가 확인되었다. 하향조절 유전자 중 32개가 Scx 결합 peak을 가졌고(후보 활성화 표적; "tendon development", "tendon cell differentiation", "keratan sulfate biosynthesis", "ECM organization"에 GO 농축), 상향조절 유전자 중 17개가 peak을 가졌다(후보 억제 표적; "regulation of cell migration", "ECM organization", "induction of chemotaxis"에 농축; Ccbe1, Cxcl12, Fgf10, Igf1, Postn 포함). 가장 하향조절된 표적은 Fmod, Tnmd, Kera, Col11a1과 전사인자 Mkx, Six2, Eya1을 포함했으나, 이 중 Tnmd만이 이전에 Scx 표적으로 보고되었다.

**다수의 표적이 Scx 의존적 건 특이 발현을 보임**
Whole-mount in situ hybridization에서 Fmod, Htra3, Kera, Ssc5d, Tnmd, Zfp185는 E14.5 야생형에서 고도로 특이적인 건 발현을 보였고 Scx−/−에서 현저히 감소했으며, qRT-PCR로 E13.5에서 이미 유의한 감소가 확인되었다. Scx 결합은 Fmod, Ssc5d, Zfp185의 basal 프로모터와 Fmod, Kera, Htra3, Tnmd의 distal 조절 요소에 농축되었다. 이전에 특성화되지 않았던 Htra3, Ssc5d, Zfp185가 초기 건 분화 중 활성화되는 직접 Scx 표적으로 부상하였다.

---

## Perspective

본 연구는 발생 중 건 조직에서 내인성 Scx 결합의 첫 전장유전체 지도를 확립하고, ChIP-seq과 Scx 의존 전사체를 통합하여 초기 tenocyte 분화를 매개하는 직접 Scx 표적 유전자 집합을 정의하였다.

첫째, ScxFlag knock-in 마우스는 오랫동안 부재했던 특이적 Scx 항체 문제를 해결하고, 발생·항상성·손상 복구 전반에서 내인성 Scx 기능을 직접 분석할 수 있는 폭넓게 유용한 도구를 제공한다. 생체 내 결합에서 얻은 de novo Scx motif(CAG/TA/CTG)는 이전 in vitro EMSA 결과를 검증·정교화한다.

둘째, Col1a1과 Tnmd를 넘어 알려진 Scx 표적 목록을 크게 확장하여, Scx가 ECM 구성요소(Fmod, Kera, Col11a1, Ssc5d), 건 전사인자(Mkx, Six2, Eya1), 세포 이동/주화성 유전자를 협조적으로 조절하고, 건 형성 중 별개의 유전자 프로그램을 활성화 및 억제함을 밝혔다.

셋째, KOMP 유래 Scx 녹아웃 계통은 표준 Scx 건 표현형을 재현하는 커뮤니티 접근 가능 자원이며, ChIP-seq/RNA-seq 데이터셋(GSE173428)은 건세포 분화와 건 조직 재생 연구의 풍부한 기반을 제공한다.

Vault의 결합조직 재생 주제 안에서, 이들 Scx 표적 유전자와 유전자 조절 논리는 건/인대 복구 및 tenogenic 대 chondrogenic 분화 프로그램의 구별에 직접 관련된다. 주요 한계는 직접 표적 집합이 사지의 단일 초기 단계(E13.5–E15.5)에서 정의된 점과, 새로 제안된 표적(Htra3, Ssc5d, Zfp185)의 건 발생 내 기능적 역할이 아직 규명되지 않은 점이다.


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
