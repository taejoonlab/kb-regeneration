---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
---

# A Single-Cell Atlas Depicting the Cellular and Molecular Features in Human Anterior Cruciate Ligamental Degeneration: A Single Cell Combined Spatial Transcriptomics Study

## Citation (NLM)
Yang R, Xu T, Zhang L, Ge M, Yan L, Li J, Fu W. A Single-Cell Atlas Depicting the Cellular and Molecular Features in Human Anterior Cruciate Ligamental Degeneration: A Single Cell Combined Spatial Transcriptomics Study. eLife. 2023;12:e85700. doi:10.7554/eLife.85700

**DOI:** [https://doi.org/10.7554/eLife.85700](https://doi.org/10.7554/eLife.85700)

---

## Background
전방십자인대(ACL) 퇴행은 만성 무릎 통증, 불안정성 및 골관절염 발병에 기여하지만, 세포 및 분자 기전은 잘 알려져 있지 않다. 세포외 기질(ECM)은 인대 기능의 물리적 기반이며, ACL 퇴행에는 ECM 재구성, 콜라겐 무질서화 및 연골样 화생이 포함된다. 이전 연구들은 개별 세포 유형이나 경로에 초점을 맞추었으나, 퇴행 중 인대 세포 이질성과 세포 간 상호작용에 대한 포괄적인 단일세포 수준의 이해가 부족했다. 본 연구는 건강한 및 퇴행된 인간 ACL의 단일세포 및 공간 전사체 아틀라스를 구축하여 인대 퇴행의 발병 기전을 규명한다.

## Key Experiment Methods
1. 10× Genomics 플랫폼을 이용한 4개 건강한 및 4개 퇴행된 인간 ACL 검체에서 49,356개 세포의 단일세포 RNA 시퀀싱(scRNA-seq)
2. 세포 아집단의 공간 분포 매핑을 위한 정상 및 병변 인대 검체의 공간 RNA 시퀀싱(spRNA-seq)
3. 섬유아세포 아클러스터링 및 10개 아집단(Fib.1-Fib.10) 동정과 차등 유전자 발현 분석
4. Monocle3를 이용한 가상시간(pseudotime) 궤적 분석으로 계통 프로그램 재구성 및 퇴행 중 동적 전사 변화 규명
5. CellPhoneDB 및 CellChat을 이용한 리간드-수용체 상호작용 분석으로 세포 간 신호 전달 네트워크 매핑
6. SCDC 도구와 GSVA를 이용한 bulk RNA-seq 디컨볼루션 분석으로 세포 유형 비율 검증
7. 주요 마커(FGF7, TGFβ1, APOE, TOP2A, ACTA2, MYH11, CD90)의 공간 검증을 위한 다중 면역형광(OPAL) 염색
8. 차등 발현 유전자의 기능적 해석을 위한 Gene Ontology (GO), KEGG 및 Gene Set Enrichment Analysis (GSEA)

## Results
- 4개 주요 세포 클래스 동정: 섬유아세포(66.14%), 면역세포(16.25%), 주위세포(pericytes, 9.78%), 내피세포(7.83%); 퇴행 ACL은 더 높은 면역세포 비율과 더 낮은 주위세포 비율을 보임
- 섬유아세포 아클러스터링에서 10개 아집단 확인: Fib.1/2 (ECM 재구성 관련, 질병에서 증가), Fib.3 (항상성 관련, 질병에서 감소), Fib.4 (상주 섬유아세포, 감소), Fib.5 (구조 섬유아세포), Fib.6 (연골세포 유사), Fib.8 (세포주기 세포, 증가), Fib.9 (염증 관련, 증가), Fib.10 (손상 수복)
- 가상시간 분석에서 두 개의 상반된 궤적 확인: cell fate1 (Fib.2, Fib.9)은 염증성 손상과 ECM 분해 특징; cell fate2 (Fib.10)은 상처 수복과 ECM 조립 특징
- 퇴행 ACL에서 내피세포 아집단 증가로 혈관신생 나타남; 주위세포1(근세포 유사)은 증가, 주위세포2(섬유아세포 유사)는 감소
- 대식세포가 가장 풍부한 면역세포였으며 퇴행에서 증가, ECM 재구성 유전자(PRG4, FN1, HTRA1)와 보체 경로 상향 조절
- CellChat 분석에서 FGF와 TGF-β 신호가 핵심 경로로 동정: Fib.9는 섬유아세포 아집단의 FGFR1에 작용하는 FGF7 발현; 대식세포는 섬유아세포와 내피세포의 TGFBR1/2에 작용하는 TGFB1 발현
- 공간 전사체학에서 질병 특이적 섬유아세포(Fib.9)와 면역세포가 퇴행 검체에서 더 많고 넓게 분포하며, 공간적 근접성이 세포 간 상호작용을 가능하게 함을 확인
- 면역형광으로 퇴행 ACL에서 Fib.8 (TOP2A+, TGFB1+) 및 Fib.9 (APOE+, FGF7+) 집단의 증가 검증

## Perspective
본 연구는 인간 ACL 퇴행의 첫 포괄적인 단일세포 및 공간 아틀라스를 제공하며, 질병이 특정 섬유아세포 아집단(Fib.1, Fib.2, Fib.9)에 의해 주도되고 FGF7-FGFR1 및 TGFB1-TGFBR2 신호 축을 통해 조절되는 ECM 재구성이 특징임을 밝혔다. 두 개의 상반된 궤적(염증성 손상 vs. 수복)의 확인은 치료 전략이 수복 경로로 균형을 이동시키는 것을 목표로 할 수 있음을 시사한다. 핵심 표적에는 ECM 재구성 조절을 위한 FGF7-FGFR1 및 TGFB1-TGFBR2 상호작용이 포함된다. 질병 특이적 섬유아세포와 면역/내피세포의 공간적 근접성은 인대 미세환경이 퇴행 진행에서 중요함을 강조한다. 향후 연구에서는 더 큰 코호트에서 이러한 결과를 검증하고 특정 섬유아세포 아집단이나 신호 전달 경로를 조절하는 표적 개입을 탐색해야 한다.

---

*Processed by **qwen3.6-plus** (OpenCode Go) on 2026-06-07*
