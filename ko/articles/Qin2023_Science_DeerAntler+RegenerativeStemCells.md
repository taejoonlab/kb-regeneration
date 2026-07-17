---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
extract_file: extract/2026-06-06_p01.txt
log:
  - "2026-06-06 · create · DeepSeek V4 Flash (OpenCode Go)"
---

# A population of stem cells with strong regenerative potential discovered in deer antlers

## Citation (NLM)

Qin T, Zhang G, Zheng Y, et al. A population of stem cells with strong regenerative potential discovered in deer antlers. Science. 2023;381(6657):eadd0488. doi:10.1126/science.add0488

**DOI:** [https://doi.org/10.1126/science.add0488](https://doi.org/10.1126/science.add0488)

---

## Background

사슴 뿔(antler)은 포유류에서 유일하게 완전한 기관 재생이 연간 반복적으로 일어나는 모델로, 긴 뼈(long bone)의 발생 및 재생 연구에 임상적으로 중요한 통찰을 제공한다. 매년 봄, 경골(硬角, hard antler)이 pedicle(뿔 기저부)에서 탈락한 후, pedicle 골막(periosteum)으로부터 뿔의 골조직과 연골이 완전히 재생된다. 뿔은 늦봄부터 초여름까지 약 2.75 cm/day의 놀라운 성장 속도로 3~4개월간 신장하며, 이는 중대형 포유류 중 가장 빠른 골 성장률이다. 기존 연구는 주로 조직학적·형태학적 측면에 머물렀으며, 항상성 유지 및 급속 성장을 가능하게 하는 세포 및 분자 기전은 불명확했다. 저자들은 단일세포 전사체 분석(scRNA-seq)과 기능 실험을 결합하여 뿔 재생을 주도하는 줄기세포 집단과 그 공간적·시간적 역동성을 규명하고자 하였다.

---

## Key Experiment Methods

**1. 단일세포 전사체 지도 구축**
- 시카사슴(Cervus nippon)의 뿔 재생 전 주기를 포괄하는 8개 시점(casting 10일 전, 0일, 2일, 5일, 10일, 45일, 60일, 90일 후)에서 scRNA-seq 수행
- 총 74,730개 세포 분석
- 신뢰도 높은 유전체 분석을 위해 수컷 시카사슴의 염색체 수준 참조 유전체(chromosome-level genome assembly) 새로 구축

**2. 세포 집단 분류 및 발생 궤적 분석**
- Seurat 기반 무감독 클러스터링으로 8개 세포 집단 식별(PRRX1+ 간엽세포, SOX9+ 연골모세포, PHEX+ 조골세포, COL3A1+ 섬유모세포, CHAD+ 연골세포, ACTA2+ 주피세포, PECAM1+ 내피세포, PTPRC+ 면역세포)
- Monocle 2 pseudotime 분석으로 세포 운명 결정 경로 재구성
- PMC(PRRX1+ mesenchymal cells) → 연골모세포 → 연골세포로의 분화 궤적 확인

**3. 이소성 뿔 재생 실험 (nude mouse)**
- Casting 후 0일 및 5일째의 세포 덩어리를 면역결핍 생쥐 두개골에 이식
- tdTOMATO 표지 생쥐를 이용한 이식 세포 기원 확인

**4. ABPCs 표현형 및 기능 분석**
- 유세포분석(FACS)으로 CX43+FGFR2+ ABPCs 분리
- In vitro: CFU-F(섬유아세포 콜로니 형성), 삼계열 분화(osteogenic/chondrogenic/adipogenic) 평가
- In vivo: 면역결핍 생쥐 신장 피막하 이식, 토끼 대퇴과 결손 모델에서 골 재생 평가

**5. 급속 성장기 뿔의 공간적 이질성 분석**
- 60일째 뿔 성장 중심(AGC)의 5개 조직층(간엽층, 전연골층, 연골층, 전비대층, 비대층)을 분리하여 scRNA-seq 및 bulk RNA-seq 수행
- 생쥐 배아 사지와의 교차 비교 분석

**6. 조직면역화학염색**
- 주요 세포 마커(PRRX1, POSTN, SOX9, CX43, FGFR2 등)에 대한 IHC 확인

---

## Results

**PRRX1+ 간엽세포(PMC)의 항상적 존재**
뿔 재생 전 시점(casting 10일 전)부터 PMC가 pedicle 골막에 상시 존재하며, 이는 도롱뇽 사지 재생에서 관찰되는 탈분화(dedifferentiation) 과정과는 달리 줄기세포 기반 재생 기전을 시사하였다.

**뿔아세포 전구세포(ABPC)의 발견**
Casting 후 5일째에 PMC2(periosteal mesenchymal progenitor)로부터 유래한 새로운 세포 집단(PMC4, TNN+PTN+TNC+DLX5+)이 출현하였다. 이 세포는 섬유아세포 콜로니 형성능이 월등히 높았고, 계대 배양 시 자기재생 능력을 유지하였으며, 골·연골 분화능(osteochondrogenic differentiation)은 골수기질세포(BMSC)보다 우수하였으나 지방세포 분화능은 없었다. 이 세포는 CX43+FGFR2+ 표면 마커로 분리 가능하였고, 저자들은 이를 'antler blastema progenitor cells'(ABPCs)로 명명하였다.

**Blastema의 보존성**
Casting 후 5일째 조직은 blastema(재생아)의 정의를 충족하였으며, 십자매 교차 비교 결과 ABPC 유사 세포가 생쥐 재생성 말단 지골(P3)에서는 발견되었으나 비재생성 중간 지골(P2), 도롱뇽 사지, 제브라피시 꼬리지느러미에서는 발견되지 않았다. 이는 ABPC가 포유류 부속기관 재생에 특화된 세포 집단일 가능성을 제시한다.

**In vivo 재생능 확인**
CX43+FGFR2+ 세포의 신장 피막하 이식 8주 후 BMSC 대비 유의하게 넓은 연골·골 신생 영역이 형성되었다(p<0.001). 토끼 대퇴과 연골 결손 모델에서도 CX43+FGFR2+ 세포가 BMSC 대비 더 높은 골부피율(BV/TV)과 섬유주 수(Tb.N)를 달성하였다.

**급속 성장기 AGC의 공간적 세포 구조**
뿔 성장 중심(AGC)은 말단 간엽층(ABPC 49.96% + perichondral cell 29.68%)에서부터 근위부의 비대 연골층(조골세포 63.87%)까지 명확한 공간적 세포 분화 구배를 보였다. 연골전구층에서는 Wnt 경로 유전자(WNT10B, WNT10A, WNT6)가, 비대층에서는 MMP9, MMP12 등 광물화 관련 유전자가 고발현되었다. 생쥐 배아 사지 성장판과 151개의 고발현 유전자가 공유되어 있어 AGC가 포유류 사지 발달과 유사한 분자 기전을 활용함을 시사하였다.

---

## Perspective

본 연구는 사슴 뿔 재생 과정의 포괄적 단일세포 지도를 제공하며, ABPC(CX43+FGFR2+)라는 새로운 재생 전구세포 집단을 발견하고 그 기능을 검증한 획기적 연구이다. 주요 의의는 다음과 같다.

첫째, ABPC는 지방세포 분화능 없이 골·연골 이계열(osteochondrogenic) 분화능만을 보유한 독특한 줄기세포로, 기존 BMSC보다 우수한 증식 및 분화 능력을 나타내어 골·연골 재생 치료의 새로운 세포치료제 후보가 될 수 있다.

둘째, 포유류 부속기관 재생에서 blastema가 보존된 생물학적 특징임을 ABPC를 통해 입증하였다. ABPC는 생쥐 재생성 말단 지골(P3)에만 존재하고 비재생성 부위(P2)에는 없어, 포유류 재생 능력의 세포적 기반 이해에 중요한 통찰을 제공한다.

셋째, AGC의 공간적 전사체 지도는 뿔이 배아 장골 성장판과 유사한 분화 구배를 따르되, 혈관신생 유전자가 풍부하여 무혈관성인 일반 연골과 구별되는 독특한 특성을 보여준다.

넷째, 인간 중간엽세포를 ABPC 유사 세포로 전환하는 기술은 향후 사지 재생이나 골격 손상 재생의학에 혁신적 가능성을 열어줄 수 있다.

향후 과제로는 ABPC의 분자 조절 기전 심층 규명, 이종이식에 따른 면역 거부 및 안전성 문제 해결, 윤리적·법적 고려사항 검토가 필요하다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
