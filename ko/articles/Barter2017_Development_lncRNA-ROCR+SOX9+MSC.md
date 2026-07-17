---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# The long non-coding RNA ROCR contributes to SOX9 expression and chondrogenic differentiation of human mesenchymal stem cells

## Citation (NLM)
Barter MJ, Gomez R, Hyatt S, Cheung K, Skelton AJ, Xu Y, Clark IM, Young DA. The long non-coding RNA ROCR contributes to SOX9 expression and chondrogenic differentiation of human mesenchymal stem cells. Development. 2017;144(24):4510-4521. doi:10.1242/dev.152504

**DOI:** [https://doi.org/10.1242/dev.152504](https://doi.org/10.1242/dev.152504)

---

## Background

SOX9는 연골세포 분화의 마스터 전사인자로, 연골 특이 유전자(Col2a1, Acan 등)의 발현을 조절한다. SOX9의 기능 상실은 생쥐의 사지 발달을 완전히 차단하며, 인간의 SOX9 코딩 서열 돌연변이는 campomelic dysplasia(CD)라는 골격 형성 이상 증후군을 유발한다. SOX9는 염색체 17의 약 2 Mb 유전자 사막(gene desert)에 위치하며, 그 발현은 다양한 조직 특이적 인핸서에 의해 조절된다. CD 환자의 염색체 재배열 분석 결과 SOX9 상류 50-350 kb 영역에 연골형성 특이적 인핸서가 존재함이 시사되었다. 그러나 SOX9의 세포 발현 조절 기전, 특히 긴 비암호화 RNA(lncRNA)의 역할은 거의 알려져 있지 않다. LncRNA는 조직 특이적 발현 패턴을 보이며 유전자 발현 조절의 핵심 조절자로 기능하지만, 연골 및 연골세포 발달에서의 lncRNA 역할은 거의 연구되지 않았다. 본 연구는 인간 관절 연골의 lncRNA 레퍼토리를 확립하고 SOX9 발현에 기여하는 연골 특이적 lncRNA를 발견하는 것을 목표로 한다.

---

## Key Experiment Methods

- **RNA-seq**: 정상 고관절 관절 연골(대퇴골 경부 골절 환자, 6명, 중앙 연령 76세)에서 RNA 추출 후 RNA-seq 수행. SOX9 유전자자리 상류의 lncRNA 발현 분석.
- **qRT-PCR**: SOX9-AS1 및 ROCR의 발현 확인 및 정량적 분석. 20-조직 RNA 패널을 이용한 조직 특이성 평가.
- **RACE (Rapid Amplification of cDNA Ends)**: ROCR 전사체 변이체 확인.
- **RNA-FISH**: ROCR의 세포 내 위치 분석 시도.
- **MSC 연골형성 분화 (Transwell 및 Pellet 방법)**: 인간 골수 유래 중간엽 줄기세포(MSC)를 연골세포로 분화 유도. ROCR 및 SOX9-AS1의 발현 동역학 분석.
- **RNA 간섭 (siRNA)**: ROCR 및 SOX9-AS1 특이적 siRNA로 유전자 발현 억제 후 연골형성 능력 평가. Safranin O 염색, GAG 정량(DMB assay), DNA 정량(PicoGreen assay).
- **LNA GapmeR**: 독립적인 ROCR 발현 억제 방법으로 검증.
- **렌티바이러스 과발현**: ROCR 및 SOX9 과발현 렌티바이러스 제작 및 MSC 감염. SOX9 과발현을 통한 ROCR 결손 표현형 구제(rescue) 실험.
- **MSC 골모세포 및 지방세포 분화**: ROCR 및 SOX9-AS1 결손이 다른 분화 계통에 미치는 영향 분석. Alizarin Red 염색(골화), Oil Red O 염색(지방).
- **생물정보학 분석**: 공개 RNA-seq 데이터베이스(Human Protein Atlas, Illumina BodyMap)를 이용한 ROCR 발현 프로파일링. ORF Finder, CPAT, CPC, PhyloCSF를 이용한 코딩 가능성 분석.

---

## Results

### 인간 관절 연골의 lncRNA 레퍼토리
- RNA-seq으로 46,087개 전사체(FPKM>1) 중 813개를 lncRNA로 동정.
- SOX9 유전자자리 상류에서 SOX9-AS1 및 LOC102723505(명명: ROCR)의 발현 확인. ROCR는 SOX9 상류 94 kb에 위치한 4-엑손 lncRNA.
- ROCR는 세포질에 주로 위치하며, SOX9-AS1보다 연골 조직 특이적 발현 패턴을 보임. ROCR 변이체 2는 연골세포에만 제한적.
- SOX9-AS1은 활막(synovium) 및 지방 패드(fat pad)에서도 발현되나, ROCR는 관절 내 연골 특이적.

### MSC 분화에서 ROCR 발현
- MSC 연골형성 분화 과정에서 SOX9, SOX9-AS1, ROCR 모두 유사한 동역학으로 상향 조절됨.
- ROCR는 골모세포 분화 및 지방세포 분화에서는 유도되지 않음 → 연골형성 특이적.
- SOX9-AS1은 지방세포 분화에서도 유도됨.

### ROCR의 연골형성 필수적 역할
- ROCR siRNA로 발현 억제 시 연골 디스크 형성 실패, GAG 생성 감소, DNA 함량 감소.
- ROCR 결손 시 COL2A1, ACAN 등 연골 기질 유전자 발현 유의하게 감소.
- ROCR 결손 후 SOX9 mRNA 및 단백질 수준이 초기 분화 단계(1일)에서부터 유의하게 감소.
- SOX5/6 발현도 ROCR 결손 시 유도되지 않음.

### ROCR의 작용 메커니즘: SOX9 의존적
- SOX9 과발현은 ROCR 결손에 의한 연골형성 장애를 유의하게 구제(rescue): GAG 수준 정상화, COL2A1/ACAN 부분적 회복, SOX5/6 완전 회복.
- 이는 ROCR의 주요 기능이 연골형성 과정에서 SOX9 발현 유도임을 시사.
- 그러나 성체 관절 연골세포(HAC)에서 ROCR 과발현은 SOX9 발현에 영향을 주지 않음 → ROCR의 역할은 분화 과정 특이적.

---

## Perspective

- 본 연구는 SOX9 발현 조절에 관여하는 최초의 연골 특이적 lncRNA(ROCR)를 발견하였다.
- ROCR는 MSC 연골형성 분화 과정에서 SOX9 유도를 매개하여 연골세포 운명 결정에 기여하며, 이는 SOX9 과발현으로 구제 가능하다.
- ROCR는 연골형성 과정에서만 특이적으로 유도되며 골모세포 및 지방세포 분화에서는 불필요하여, MSC의 연골세포 계통 결정에 중요한 역할을 한다.
- SOX9 상류 인핸서 영역에 위치한 ROCR 유전자자리는 CD 및 Pierre Robin sequence와 연관된 염색체 재배열 파손점과 일치하여, 이 lncRNA가 골격 발달 질환의 병리 기전에 관여할 가능성을 시사한다.
- 추후 연구 과제: (1) ROCR의 분자적 작용 기전(단백질 결합 파트너 등) 규명, (2) 마우스 ROCR 오솔로그의 기능 분석, (3) 관절 연골의 영역별, 성장판 연골, 체중 부하, 노화 및 골관절염에 따른 lncRNA 발현 변화 분석, (4) ROCR-SOX9 축을 활용한 연골 조직 공학 응용 가능성 탐색.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
