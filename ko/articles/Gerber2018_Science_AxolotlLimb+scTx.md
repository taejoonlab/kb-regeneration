---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p03.txt
raw_data:
  - "GEO: GSE106269"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Single-cell analysis uncovers convergence of cell identities during axolotl limb regeneration

## Citation (NLM)
Gerber T, Murawala P, Knapp D, Masselink W, Schuez M, Hermann S, Gac-Santel M, Nowoshilow S, Kageyama J, Khattak S, Currie JD, Camp JG, Tanaka EM, Treutlein B. Single-cell analysis uncovers convergence of cell identities during axolotl limb regeneration. Science. 2018;362(6413):eaaq0681. doi:10.1126/science.aaq0681

**DOI:** [https://doi.org/10.1126/science.aaq0681](https://doi.org/10.1126/science.aaq0681)

---

## Background

액솔로틀(Ambystoma mexicanum)을 비롯한 도롱뇽류는 사지 전체를 재생할 수 있는 유일한 사지동물이다. 절단 후 절단면 근처의 세포들이 blastema라 불리는 일시적 조직으로 모여 새로운 사지의 전구세포 공급원 역할을 한다. 측판 중배엽(lateral plate mesoderm) 유래인 결합조직(connective tissue, CT) 세포는 blastema에 가장 많이 기여하는 계보로, 뼈·연골·힘줄·periskeleton·진피/간질 섬유아세포를 포함하며 위치 정보를 감지하여 적절한 사지 부위 재생을 유도한다.

핵심 미해결 질문은 성숙한 CT 세포가 배아 사지 전구세포 유사 상태로 분자적으로 "재프로그래밍"되는지, 아니면 CT 내에 미리 존재하는 줄기세포가 선택적으로 blastema를 형성하는지였다. 기존에는 성체 조직에서 blastema 전구세포를 식별·분리할 수 없어 분자적 연구가 어려웠다. 본 연구는 Cre-loxP 계보추적과 단일세포 RNA 시퀀싱(scRNA-seq)을 결합하여 성숙 CT의 이질성과 blastema 상태로의 전환을 추적한다.

---

## Key Experiment Methods

1. Prrx1 사지 인핸서 하에 tamoxifen 유도성 Cre-ERT2를 발현하는 생식계열 형질전환 액솔로틀 계통(Prrx1:Cre-ER;Caggs:lp-Cherry)을 제작하여 CT 세포를 유전적으로 표지·추적; 항-PRRX1 항체로 pan-CT 마커임을 검증.
2. CT 하위 집합(뼈·periskeleton·힘줄)을 표지하는 두 번째 driver 계통(Col1a2:ER-Cre-ER;Caggs:lp-Cherry) 제작.
3. 고처리량 droplet 기반 scRNA-seq(10x Genomics)로 성체 사지와 후기 blastema 분석; 고전사체 커버리지 scRNA-seq(Fluidigm C1)로 FACS 분리한 mCherry+ CT 세포를 재생 시간축(0, 3, 5, 8, 11, 18 dpa 및 완전 재생)을 따라 분석.
4. 배아 사지 단계(stage 28 limb field, stage 40·44 limb bud)의 scRNA-seq로 재생과 발생을 비교.
5. tSNE 클러스터링, diffusion pseudotime, SPRING, mock bulk 상관분석, 세포간 이질성 지표 등 전산 분석.
6. 표지/비표지 개체 간 상완골(humerus) 이식 실험으로 근위부 대 원위부 세포 공급원 규명.
7. Brainbow 형질전환 클론 계보추적으로 단일 CT 세포의 다능성 검증.

---

## Results

- 미손상 성체 상완 CT의 scRNA-seq에서 8개 클러스터 식별: tenocyte(Tnmd), periskeletal 세포(Col8a2), 활발히 증식하는 세포(Ccnb1), 5개 섬유아세포성 CT 하위집단(fCT I–V). 세포 아틀라스와 마커 세트 제공.
- blastema 형성 중 이질적인 분화 CT 세포들이 비교적 균질한 전구세포 상태로 "깔때기(funnel)"처럼 수렴; 세포간 이질성은 미손상 → 초기 blastema → 11 dpa까지 점진적으로 감소하다가 재분화가 시작되는 18 dpa에 다시 증가.
- 미손상 조직에서 blastema 유사 세포가 발견되지 않았고 세포 기여에 수적 편향이 없어, blastema 형성이 기존 줄기세포 집단의 선택이 아니라 성숙 CT의 탈분화(dedifferentiation)에 의한 것임을 시사.
- 전사 동태: blastema 형성 중 ECM 유전자 하향조절; 3–5 dpa 염증(Il11, Cxcl2) 및 MMP(Mmp8, Mmp13); 8 dpa 증식 유전자; 11–18 dpa 재패터닝(Hoxa13, Hoxd12) 및 ECM 재확립(Matn4); 18 dpa 골격 유전자(Hoxd13, Col2a1, Sox9).
- CT 재프로그래밍은 배아 발생과 구별되는 blastema 특이적 상태를 거친 후 배아 limb bud 유사 프로그램으로 수렴; stage 40/44 limb bud 전사체와의 상관은 11 dpa에 최고.
- 근위부 대 원위부 재생의 세포 공급원 상이: Col1a2 계통 세포(periskeleton/힘줄)는 주로 절단면의 기존 뼈를 연장, 섬유아세포성 CT 세포는 원위 골격 분절을 de novo 재생. 이식 실험 결과 이 공간적 편향은 내재적 분절 제한이 아니라 callus 연관성 때문.
- 후기 blastema(18/25/38 dpa) 궤적에서 배아 사지/세포주기 마커(Prdx2, Nrep, Ccnb1)를 발현하는 다능성 전구세포가 비골격 및 골격(연골/뼈) 계보로 분지; 성체 CT 아형은 38 dpa까지 재출현.
- Brainbow 클론 추적으로 단일 CT 세포가 골격·periskeletal·섬유아세포·힘줄 세포를 생성함을 확인 — 다능성 CT/골격 전구세포 확립.

---

## Perspective

본 연구는 성숙하고 이질적인 결합조직 세포가 복잡한 척추동물 기관 재생 동안 공통의 다능성 limb bud 유사 전구세포로 탈분화하는 과정의 분자 지도를 제공하며, 오랜 논쟁을 "기존 줄기세포 선택"이 아니라 "재프로그래밍" 쪽으로 결론짓는다. 단일세포 전사체와 클론 계보추적으로 뒷받침되는 수렴-후-발산("funneling") 모델은 blastema 형성을 분자적 재프로그래밍으로 재해석한다.

의의: 성체 세포가 사지 형태발생을 조율할 수 있는 배아 사지 잠재력으로 재프로그래밍될 수 있음을 보여주어 재생공학에 시사점을 준다. 저자들이 지적한 한계·향후 방향으로는 탈분화에 필요한 전환 상태의 구성요소 규명, 재생 관련 유전자와 그 크로마틴 구조의 조절 메커니즘 연구가 있다. 또한 포유류의 제한된 재생능이 CT를 이러한 배아 상태로 재프로그래밍하지 못하는 데서 기인할 수 있다는 가설을 제기한다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- GEO: GSE106269


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
