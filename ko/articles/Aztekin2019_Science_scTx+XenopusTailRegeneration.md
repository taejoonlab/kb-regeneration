---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Identification of a regeneration-organizing cell in the Xenopus tail

## Citation (NLM)
Aztekin C, Hiscock TW, Marioni JC, Gurdon JB, Simons BD, Jullien J. Identification of a regeneration-organizing cell in the Xenopus tail. Science. 2019;364(6441):653-658. doi:10.1126/science.aav9996

**DOI:** [https://doi.org/10.1126/science.aav9996](https://doi.org/10.1126/science.aav9996)

---

## Background
포유류와 달리 *Xenopus laevis*(아프리카발톱개구리) 올챙이는 높은 재생 능력을 지녀 절단된 꼬리를 재생할 수 있다. 부속지(appendage) 재생은 일반적으로 특수화된 상처 표피(wound epidermis) 형성, 배아싹(blastema) 형성, 증식을 통한 성장의 세 단계로 나뉜다. 상처 표피는 여러 종(제브라피시, 아홀로틀 등)에서 재생에 필수적인 리간드 발현 구조이지만, 어떤 세포 유형이 이를 구성하는지, 그 기원과 발현 리간드는 무엇인지 불분명했다.

*Xenopus* 올챙이는 발생 단계에 따라 재생 가능(regeneration-competent) 시기와 재생 불가능(regeneration-incompetent) 시기가 자연적으로 존재하여 비교 연구에 이상적인 모델이다. 저자들은 단일세포 RNA 시퀀싱(scRNA-seq)으로 재생 중인 꼬리를 포괄적으로 프로파일링하여 재생의 핵심 조절자를 규명하고자 했다.

---

## Key Experiment Methods
1. **scRNA-seq 아틀라스**(10X Genomics, >13,000 세포): 재생 가능(NF 40-41기) 및 재생 불가능(NF 46-47기) 올챙이의 온전한 꼬리와 절단 후 1-3일(dpa) 시료를 조건당 2회 이상 생물학적 반복으로 분석.
2. **차원 축소 및 클러스터링**: UMAP과 그래프 기반 walktrap 알고리즘 사용, 알려진 마커 유전자로 46개 추정 세포 유형 주석.
3. **차등 존재비 분석**(edgeR/cydar 방식): 재생 가능 vs. 불가능 조건 비교로 재생 특이적 세포 유형 변화 탐색.
4. **위치 확인**: Xenbase in situ 데이터와 Lef1 리포터 라인(pbin7Lef:GFP) + TP63 면역염색.
5. **유전적 제거**: Krt.L 프로모터로 nitroreductase를 발현시키는 NTR/MTZ 시스템(F0 형질전환 올챙이) 및 후방 몸통 세포 수동 제거.
6. **생체 이미징**: Lef1 리포터 세포 추적; **화학적 교란**(ROS-DPI, TGFβ-SB-505124, FGF-SU5402)으로 세포 이동 평가.
7. **이식(grafting)**: 후방 꼬리싹 조직("large"/"small" 이식편)을 숙주 몸통에 이식하여 이소성 돌출 유도 검증; 리간드/수용체 쌍 scGSEA.

---

## Results
- scRNA-seq 아틀라스는 면역, 피부, 신경계, 체절(somite) 계통에 걸친 46개 세포 유형을 밝혔다. 전구세포는 G2/M·S기에, 최종 분화 세포는 G1기에 편향되었다.
- 비교 분석으로 발생성, 절단 특이적, 재생 특이적 변화를 구분했다. 절단 반응(재생 가능·불가능 공통)에는 척수 손상 유전자(Fgf10)와 대사 호르몬(Leptin)을 발현하는 운동뉴런 유사 세포 유형이 포함되었다.
- 가장 유의한 재생 특이적 변화는 이전에 알려지지 않은 표피 세포 유형으로, **재생 조직화 세포(regeneration-organizing cell, ROC)**로 명명되었다. ROC는 재생 지지 유전자(Wnt5a, Fgf10, Fgf20, Msx1, Bmpr1a)를 발현하며 LEF1+/TP63+ 세포로서 표피 정중선 가장자리에 위치했다.
- 절단 후 ROC는 절단면에서 제거되지만 후방 몸통에는 남아 있으며, 재생 가능 올챙이에서는 24시간 내에 절단면으로 **재배치/이동**하여 특수화된 상처 표피를 형성한다. 재생 불가능 올챙이에서는 절단면에 나타나지 않는다.
- **유전적(NTR/MTZ) 또는 수동 ROC 제거는 재생을 차단했다.** 후방 몸통 ROC가 재생을 개시하기 위해 이동해야 하는 결정적 시간 창(critical time window)이 존재한다.
- ROS 생성과 TGFβ 경로 활성이 ROC 이동에 필요했으나, FGF 억제는 이동에 영향을 주지 않았다.
- ROC는 FGF, BMP, WNT, NOTCH, TGFβ 경로의 리간드를 동시에 발현하고 전구세포는 해당 수용체를 발현하여, ROC가 전구세포 증식을 촉진하는 **신호 중심(signaling center)**으로 작용함을 시사한다.
- ROC는 사지 정단외배엽능선(AER)/정단상피모자(AEC)와 전사체적으로 유사하다(Sp8, Sp9, Msx2, Wnt5a). **ROC 함유 조직 이식은 이소성 돌출을 유도했다**(큰 이식편→꼬리형, 작은 이식편→지느러미형). 공여체 ROC 제거 시 돌출이 감소했고, 공여 ROC는 이소성 구조의 끝단에 위치했다.

---

## Perspective
본 연구는 꼬리 재생에 대한 단일세포 수준의 기계론적 관점을 제공한다: 단일 세포 유형(ROC)이 절단면으로 재배치되어 상처 표피를 형성하고 하위 전구세포의 증식을 촉진하는 신호 중심으로 작용하며, 새로운 다능성 전구세포 상태나 전분화(transdifferentiation)를 필요로 하지 않는다. 이 발견은 상처 표피가 절단 후 새로 생기는 별개 상태가 아니라 기존 세포의 이동으로 형성됨을 시사한다.

의의: 상처 표피를 정의하는 개별 세포 유형의 발견은 재생 치료에서 "조직화 세포 이식(organizer graft)" 개념을 제시한다. 한계·향후 방향: ROC 기반 기전이 다른 종(신생 마우스, 도롱뇽)에서 보존되는지 검증이 필요하며, 고전적 AER 조절자(Fgf2/4/8, Cx43)는 ROC에서 검출되지 않아 유사성이 불완전함을 나타낸다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
