---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p09.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Comprehensive profiling reveals mechanisms of SOX2-mediated cell fate specification in human ESCs and NPCs

## Citation (NLM)
Zhou C, Yang X, Sun Y, Yu H, Zhang Y, Jin Y. Comprehensive profiling reveals mechanisms of SOX2-mediated cell fate specification in human ESCs and NPCs. Cell Res. 2016;26(2):171-189. doi:10.1038/cr.2016.15

**DOI:** [https://doi.org/10.1038/cr.2016.15](https://doi.org/10.1038/cr.2016.15)

---

## Background

세포 유형 특이적 마스터 전사인자는 특정 유전자 조절 네트워크를 지휘하여 세포 정체성을 확립·유지하며, 동일한 인자라도 세포 유형과 발생 단계에 따라 상이한 역할을 수행한다. SOX2는 배아줄기세포(ESC)와 신경전구세포(NPC)에 필수적인 pioneer factor이나, 대부분의 기전 연구는 마우스 세포에서 수행되어 인간 ESC(hESC)와 인간 NPC(hNPC)에서의 역할은 잘 정의되지 않았고 논란이 있었다. 표준(canonical) Wnt 신호가 hESC의 자기재생을 촉진하는지 분화를 유도하는지에 대한 보고가 엇갈렸으며, 인간 세포에서 SOX2와 Wnt 신호의 관계는 미해결 상태였다.

이 연구는 유전적으로 동일한 hESC와 hESC 유래 hNPC 간에 SOX2의 DNA 결합, SOX2 조절 유전자, SOX2 단백질 상호작용체를 비교하는 포괄적 유전체 프로파일링을 수행하여, SOX2가 신경 분화 경로를 따라 세포 운명 결정을 어떻게 조절하는지를 규명한다. 이는 신경 줄기/전구세포 생물학 및 CNS 발생과 직접 관련된 주제이다.

---

## Key Experiment Methods

1. hESC(H9, SHhES2 계통)로부터 hNPC 생성 및 완전한 특성화.
2. 유전적으로 동일한 hESC와 hNPC에서 SOX2 및 Pol II ChIP-seq 수행, 공개된 히스톤 변형 ChIP-seq(H3K4me3, H3K4me1, H3K27me3, H3K27ac)과 통합하여 결합 부위를 active/poised/repressed 프로모터·인핸서로 분류.
3. SOX2 결핍(siRNA) hESC와 hNPC의 RNA-seq(hESC에서는 보상 대응을 위해 SOX3 동시 knockdown) 수행, ChIP-seq와 RNA-seq 결합으로 직접 기능 표적 식별.
4. 신경 분화 중 Notch 경로 구성원 및 proneural 유전자(DLL1, HES5, JAG1, HES3, NEUROD1, NEUROG1)의 시계열 ChIP-qPCR 및 RT-qPCR.
5. 기능적 Wnt 분석: Western blot(β-catenin, p-LRP6), 핵 분획, TOP/FOP luciferase reporter, 약리학적 조절(CHIR99021, Wnt3A, IWR1-e, IWP2, DKK1, Noggin).
6. Wnt 조절인자 SFRP2 및 WLS를 해부하는 구제 실험(siRNA/shRNA knockdown, 재조합 SFRP2 보충).
7. 면역침강 + 질량분석에 의한 SOX2 단백질 상호작용체; SOX2-H2A.Z 및 H2A.Z-PRC2 상호작용 co-IP 검증; 표적 프로모터(WLS, WNT5B)에서 H2A.Z, EZH2, 히스톤 마커 ChIP-qPCR.
8. 공개된 마우스 ESC/NPC SOX2 ChIP-seq와의 종간 비교.

---

## Results

- SOX2는 hESC에서 17,992개, hNPC에서 67,021개 부위에 결합(hESC 피크의 약 50%가 hNPC와 중첩)했으며 대부분 프로모터-원위(distal) 부위. 프로모터 결합은 활성 마커 및 자기재생/유지 과정과 연관되고, poised 인핸서 결합은 대체로 세포 유형 특이적이며 발생(CNS 포함) 프로그램과 연결됨.
- SOX2는 hESC에서 poised proneural 전사 프로그램을 점유. 신경 분화를 따라 SOX2는 Notch 경로 구성원(DLL1, HES5, JAG1, HES3; 단 HES1은 아님) 프로모터에 점차 결합하여, 신경 분화 및 hNPC 유지에서 SOX2를 Notch 신호의 상류에 위치시킴.
- SOX2는 4개의 세포 유형/단계 의존적 프로그램을 조절: (a) 공통 자기재생 보호 프로그램, (b) hESC에서의 proneural 프로그램, (c) hESC 특이적 비신경(중배엽/내배엽) 계통 억제, (d) hNPC에서의 CNS 분화 프로그램.
- hESC에서 SOX2는 표준 Wnt 신호를 억제하여 비신경 계통을 억압: SOX2/3 knockdown은 Wnt를 신속히 활성화(β-catenin, p-LRP6, TOP/FOP, Wnt 표적)했고, Wnt 억제제 IWR1-e(BMP 억제제 Noggin은 아님)가 그 결과인 계통 마커 상향조절을 OCT4 수준과 무관하게 소거.
- hNPC에서 SOX2는 표준 Wnt 신호를 억제하는 동시에 proneural 유전자(NEUROD1, NEUROG1)를 직접 활성화하여 신경 분화를 개시. 인간 신경 분화에서 Wnt의 억제적 역할은 마우스 성체 신경발생에서의 유도적 역할과 대조되어 종 특이적 기능을 시사.
- SOX2는 두 조절인자 — Wnt 길항제 SFRP2와 Wnt 분비 단백질 WLS — 의 직접적 전사 조절을 통해 Wnt 경로를 억제. SFRP2 보충 + WLS knockdown 병용이 SOX2/3 knockdown 분화 표현형을 구제.
- SOX2는 히스톤 변이체 H2A.Z(hESC에서 68개, hNPC에서 191개 파트너; 다수의 스플라이싱/염색질 인자)와 상호작용하여 PRC2를 동원하고 bivalent 발생 유전자를 poise. SOX2/3 knockdown은 표적 프로모터에서 H2A.Z 및 EZH2 점유와 H3K27me3를 감소시킴.
- 종간 비교에서 SOX2 결합 프로파일의 낮은 보존성(대부분 피크가 종 특이적)이 드러났으며, 보존된 프로모터 결합이 줄기세포 유지를 뒷받침하고 발산하는 원위 결합이 종 특이적 발생 조절을 뒷받침.

---

## Perspective

이 연구는 핵심 다능성/신경 마스터 인자인 SOX2가 서로 다른 신호 경로를 조절하고 히스톤 변이체를 동원하여 염색질 상태를 변화시킴으로써 세포 운명을 결정한다는 기전적 증거를 제공한다. hESC에서 Wnt 억제를 매개하는 신규 직접 SOX2 표적으로 WLS와 SFRP2를 식별하고, 신경 분화에서 SOX2를 Notch 신호 상류에 위치시키며, bivalent 발생 유전자의 SOX2-H2A.Z-PRC2 poising을 확립했다. 신경 줄기/전구세포 생물학 측면에서, SOX2가 인간 NPC로부터 신경 분화를 어떻게 준비(prime)하고 실행하는지를 명확히 했으며, 마우스와 반대되는 Wnt 역할은 인간 세포를 직접 연구할 필요성을 강조한다.

한계로는 in vitro hESC/hNPC 모델에 의존(in vivo CNS 아님)하고, off-target 및 보상 문제를 동반하는 siRNA/shRNA knockdown 사용(SOX2/3 동시 knockdown 필요), 일부 기전 주장에 대한 상관적 유전체 통합 분석이 있다. 저자들이 언급한 향후 방향으로는 SOX2가 WLS/SFRP2 조절을 통해 종양형성에 기여하는지 검증하고 SOX2-염색질 조절인자 네트워크를 추가 해부하는 것이 포함된다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
