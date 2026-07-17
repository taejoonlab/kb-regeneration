---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p08.txt
---

# Fibroblast growth factor signaling induces a chondrocyte-like state of peripheral nerve fibroblast during aging

## Citation (NLM)
Stefanovska D, Sassu E, Tekman M, Naghsh Nilchi A, Haider S, Domisch C, Hossfeld M, Perez-Feliz S, Miarka L, Schneider-Warme F, Arnold SJ, Prinz M, Grüning B, Preissl S, Hortells L. Fibroblast growth factor signaling induces a chondrocyte-like state of peripheral nerve fibroblast during aging. Nat Commun. 2025;16:10020. doi:10.1038/s41467-025-65297-8

**DOI:** [https://doi.org/10.1038/s41467-025-65297-8](https://doi.org/10.1038/s41467-025-65297-8)

---

## Background
노화 과정에서 말초신경은 세포외기질(ECM) 침착 증가를 포함한 구조적·세포적 변화를 겪으며, 이는 신경 전도 속도와 전반적 기능을 저하시키고 표적 장기(골격근, 심장, 장)에 영향을 주며 질병 위험을 높인다. 이러한 노화 유발 변화의 세포·분자 기전은 잘 알려져 있지 않다. 최근 노령 마우스 좌골신경(sciatic nerve)에서 연골성 프로테오글리칸(예: CSPG4) 침착이 증가한다는 보고가 있었으나, 신경 섬유아세포가 이 ECM 재구성에 어떻게 기여하는지는 불분명했다.

FGF(fibroblast growth factor) 신호는 노화 관련 근육내 지방 침착, 섬유화, 혈관 석회화에 관여하며 연골세포 분화를 유도하는 것으로 알려져 있으나, 말초신경계(PNS) 노화에서의 역할은 알려지지 않았다. 연골세포 마커인 SOX9는 건강한 신경의 endoneurial 섬유아세포와 신경 손상 후 satellite glial cell에서 발현되며, 혈관 석회화·심장 섬유화 같은 퇴행성 과정에도 관여한다. 본 연구는 단일핵 RNA 시퀀싱(snRNA-seq)으로 노화 마우스 좌골신경의 세포 상태·구성 변화를 규명하고, FGF 신호가 연골세포 유사(chondrocyte-like) 섬유아세포 상태를 유도하는지 검증한다.

---

## Key Experiment Methods
1. 세 연령(2–3, 15–16, 20–30개월) 마우스 좌골신경의 snRNA-seq; FACS 기반 핵 분리; 19,175개 핵을 19개 1차 클러스터로 분류, 대식세포·섬유아세포·지방세포는 2차 재클러스터링.
2. 마커 기반 클러스터 주석 및 기존 어린 마우스(P60) 데이터셋 재분석으로 연골세포 유사 섬유아세포 집단 확인.
3. 마우스 좌골신경 절편 면역형광 및 세포 계수(마커: CD45, CD68, MRC1, GRN, TGFβR1, SOX9, CSPG4, GLUT1, KCNC2, FABP4, FGF2, γH2AX, VIM) 및 fluoromyelin 표지.
4. Sox10-CreERT2;R26tdTomato 마우스로 Schwann 세포 계보 추적, Schwann 세포 및 중간엽(VIM+/SOX10−) 세포의 노쇠(γH2AX) 평가.
5. CellChat 세포-세포 상호작용 추론 및 STRING 단백질 연관 분석으로 FGF 신호(지방세포→섬유아세포) 후보 도출.
6. Monocle 유사시간(pseudotime) 궤적 분석(endo-/peri-/epineurial 섬유아세포를 기원, 연골세포 유사 섬유아세포를 종점으로).
7. 사람 perineurial 섬유아세포(hPnFbs) in vitro 실험: 초기 계대(3–4) vs 노쇠(계대 8–9); FGF2, FGF1(+heparin), 조합을 14일 처리 및 FGF2 제거 후 7일 관찰; 지표는 EdU, SOX9, FOXC2, CSPG4, γH2AX.
8. 젊은(17–33세) vs 고령(55–68세) 공여자 사람 말초신경 FFPE 샘플에서 검증.

---

## Results
- snRNA-seq로 좌골신경에서 19개 세포 클러스터를 확인했고, 그중 연골세포 계보 마커 Sox9·Foxc2·Cspg4를 공동 발현하고 perineurial 마커 Slc2a1/Glut1은 낮게 발현하는, 이전에 기술되지 않은 섬유아세포 집단을 발견했다.
- 지방조직 세포와 연골세포 유사 섬유아세포는 15개월 이상 마우스 신경에서 더 흔해졌으며, endo-/peri-/epineurial 섬유아세포의 상대적 수는 변하지 않았다.
- 대식세포 표현형은 노화에 따라 변화: 젊은 마우스에서는 상주 정상상태형(Cx3cr1, Mrc1)이 우세, 15–16개월에는 식균형(Cd44, C1qa, Grn), 20–30개월에는 만성 염증형(Tgfβr1, Kynu)이 정점을 이루었고, 단백질 계수와 미엘린 식균 증가로 확인됨.
- 연골세포 유사 섬유아세포의 GO 분석은 피부 형태형성(Col1a1/Col1a2, pro-fibrotic)과 연골세포 발생/분화(Sox9, Sox6, Sox5) 강화를 보였다. SOX9+ 세포 밀도와 CSPG4 면적은 20–30개월에서 유의하게 증가.
- Pseudotime 및 in vivo 계수 결과, 연골세포 유사 상태의 가장 가능성 높은 기원은 perineurial 섬유아세포(PnFbs, GLUT1+)로, epineurial(KCNC2+) 섬유아세포보다 우세했다.
- CellChat은 지방세포→(PnFbs/연골세포 유사) 상호작용 증가를 예측했고, Fgf2는 지방세포에서 높게 발현(최상위 Fgf2-Fgfr1/Fgfr2), FGF2 분비 FABP4+ 지방세포 밀도가 노령 신경에서 증가. CSPG4는 FGF2와 직접 결합하여 신호를 증폭할 수 있다.
- In vitro: FGF2는 초기 계대 hPnFbs에서는 연골세포 유사 상태를 유도하지 않았고(오히려 DNA 손상에 보호적), 노쇠 hPnFbs에서는 100 ng/ml FGF2가 SOX9+/FOXC2+ 공동 발현을 유의하게 증가시켰다. 이 효과는 FGF2 제거 시 가역적이었으며, CSPG4는 FGF2로 증가하지 않아 다른 신호의 관여를 시사.
- 고농도 FGF1은 FGF2 효과를 재현하지 못했고 FGF2 유도 활성화를 차단(공유 수용체에 대한 경쟁적 억제 제안); 저농도 FGF1은 차단에 불충분.
- 고령 공여자 사람 신경은 젊은 공여자에 비해 FGF2+ 및 SOX9+/FGF2+ 세포가 유의하게 많고 핵 밀도가 낮아 임상적 관련성을 뒷받침.

---

## Perspective
본 연구는 마우스 좌골신경 노화에 대한 최초의 snRNA-seq 지도를 제공하며, FGF2에 의해 유도되는 노화 관련 perineurial 섬유아세포의 연골세포 유사 상태와 식균형→만성 염증형 대식세포 전환을 규명한다. CSPG4/콘드로이틴 황산 프로테오글리칸은 신경계에서 억제성 반흔 생물학의 핵심이므로, FGF2 신호에 반응해 연골성 ECM을 침착하는 신경 섬유아세포의 발견은 신경 퇴행·복구 전반에 폭넓은 함의를 갖는다. FGF1이 FGF2를 길항한다는 발견은 FGF1을 말초신경 항노화 분자 후보로 제시한다. 한계로는 fluoromyelin/형광현미경이 미세한 미엘린 변화를 놓칠 수 있고(전자현미경 필요), 사람 코호트가 혼합신경과 순수 감각신경을 포함하며 규모가 작고, in vitro에서 FGF2가 CSPG4 침착을 유도하지 못해 프로테오글리칸 축적을 다른 신호가 조절함을 시사하는 점이 있다. 향후 Schwann 세포·신경섬유에 대한 FGF2 효과 검증과 노화 관련 신경 기능장애의 초기 유발인자 규명이 필요하다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
