---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
---

# Microglia coordinate cellular interactions during spinal cord repair in mice

## Citation (NLM)
Brennan FH, Li Y, Wang C, Ma A, Guo Q, Li Y, Pukos N, Campbell WA, Witcher KG, Guan Z, Kigerl KA, Hall JCE, Godbout JP, Fischer AJ, McTigue DM, He Z, Ma Q, Popovich PG. Microglia coordinate cellular interactions during spinal cord repair in mice. Nat Commun. 2022;13:4096. doi:10.1038/s41467-022-31797-0

**DOI:** [https://doi.org/10.1038/s41467-022-31797-0](https://doi.org/10.1038/s41467-022-31797-0)

---

## Background

외상성 척수손상(SCI)은 CNS 상주 미세아교세포(microglia)와 침윤하는 단핵구 유래 대식세포(MDM)가 주도하는 신경염증 반응을 유발한다. 활성화된 미세아교세포와 MDM은 생체 내에서 형태가 유사하고 표현형 표지자가 겹치기 때문에, 미세아교세포가 특이적으로 조율하는 손상 반응을 구분하는 것은 오랫동안 어려운 과제였다. 미세아교세포는 CNS 세포의 약 10%를 차지하며 신경세포 및 비신경세포와 지속적으로 상호작용하여 항상성을 유지한다.

본 연구는 미세아교세포 특이적 고갈(CSF1R 길항제 PLX5622)과 해부학적·조직병리학적·신경로 추적·bulk RNA-seq·단일세포 RNA-seq 기법을 결합하여, 세 가지 마우스 SCI 모델에서 미세아교세포가 조율하는 세포·분자 수준의 손상 반응을 규명하였다.

---

## Key Experiment Methods

1. PLX5622(CSF1R 길항제) 사료를 SCI 2주 전부터 손상 후 35일(dpi)까지 급여하여 미세아교세포를 약 99% 고갈시킴(75 kdyne T9 타박손상 모델).
2. 기능 회복 평가: Basso Mouse Scale(BMS) 점수·부점수, 수평 사다리 검사.
3. 조직학/면역염색: 수초(eriochrome cyanine, MBP), 신경섬유/축삭, GFAP(성상교세포 경계), P2RY12(미세아교세포) 대 F4/80/CD68(MDM), BrdU 증식, Oil Red O(지질), 병변 부피/길이 재구성.
4. 더 심한 모델에서의 재현: T9 및 L1 완전 겸자 압착손상.
5. 손상 척수의 bulk RNA 시퀀싱(7 dpi, vehicle 대 PLX5622); WebGestalt·Reactome 경로 분석, GeneMANIA 유전자 네트워크 분석.
6. 구제(rescue) 실험: 재조합 CCL2(rCCL2) + TLR2 작용제(PAM3CSK4)를 2-3 dpi에 척수 내·복강 내 주입하여 미세아교세포 의존 신호 복원.
7. 단일세포 RNA 시퀀싱(scRNA-seq): sham·7 dpi·28 dpi에서 21,016개 세포 분석; UMAP 군집화, Monocle 3 유사시간(pseudotime), CellChat 리간드-수용체 통신 분석.

---

## Results

- 미세아교세포는 최적 회복에 필수적이다: 고갈 시 운동 회복이 악화되었고(35 dpi에 지속적 족저 보행 달성 PLX 2/7 대 대조군 100%), 사다리 검사 오류가 증가하였으며, 수초·축삭 병리, 병변 부피·길이가 악화되었다.
- 미세아교세포가 없으면 MDM이 커다란 이소성 "거품형(foamy)" 군집을 형성해 보존된 백질로 이동하였고, 병변을 경계짓는 GFAP+ 성상교세포 경계가 약화되면서 성상교세포·NG2 세포 증식이 감소하였다. 이 표현형은 T9 및 L1 압착 모델에서도 재현되었다.
- Bulk RNA-seq: SCI의 주 효과는 유전자 발현 증가, 미세아교세포 고갈의 주 효과는 발현 감소였다. SCI로 상향되는 상위 유전자의 약 51%가 미세아교세포 없이는 증가하지 못했다. 미세아교세포 의존 유전자는 식균작용, 사이토카인 생산/반응, 세포내이입, 단백질 분비를 조절하며, 31개 유전자로 이루어진 핵심 네트워크가 확인되었고 Tlr2(중심 노드)와 Ccl2(가장자리 노드)가 핵심 허브였다.
- 구제: 미세아교세포 고갈 척수에 rCCL2 + TLR2 작용제를 주입하면 지질 식균, 교세포 반흔, MDM 억제(corralling)가 복원되고 회복이 향상되었다. 반대로 미세아교세포가 정상인 개체에서는 동일 처치가 결과를 악화시켰다.
- scRNA-seq로 14개 세포 유형과 11개 미세아교세포 아형(항상성, 증식, 지질 처리, 철 처리, 인터페론, 항원 처리 등)을 분리하였다. SCI 후 항상성 미세아교세포가 증식·지질 처리 아형으로 대체되었고, 지속적으로 증가한 유전자는 Apoe, Spp1, Fth1 등이었다.
- MDM은 10개 아형으로 나뉘었으며, 미세아교세포가 MDM의 모집과 기능적 표현형을 조절하였다. 미세아교세포가 없으면 MDM이 지질 결합/기질 재구성 상태로 치우쳐 무분별한 기질 분해에 대비된 상태가 되었다.
- 성상교세포는 3개 아형(수송체, 대사, 염증)으로 나뉘었고, SCI로 유도되는 염증 성상교세포 상태는 미세아교세포 의존적이었으며 SCI로 증가하는 성상교세포 유전자의 55%가 미세아교세포 없이는 증가하지 못했다.
- CellChat 분석으로 미세아교세포 의존 신호축을 규명하였다: 미세아교세포 Psap-성상교세포 Gpr37l1(교세포 보호), 7 dpi 미세아교세포 Spp1(osteopontin)-MDM Cd44/인테그린, 28 dpi Csf1r-Csf1.

---

## Perspective

본 연구는 다중 오믹스 접근을 통해 미세아교세포가 SCI 후 회복 반응의 필수 조율자로서 MDM 모집·표현형, 성상교세포 경계 형성, 지질 처리, 혈관 복구를 통합적으로 지휘함을 종합적으로 입증하였다. 기전적으로는 미세아교세포 고갈 척수의 회복을 구제하는 데 활용할 수 있는 CCL2/TLR2 "핵심" 신호 signature를 규명하였으나, 미세아교세포가 존재할 때는 동일 처치가 해로워 신호 네트워크가 정교하게 균형 잡힌 맥락 의존적 시스템임을 강조한다.

한계로는 약리학적 고갈 의존(대조 실험으로 주요 교란은 배제되나 표적 외/전신 효과 가능성), scRNA-seq의 포획 편향으로 미세아교세포·MDM 과대표집, 마우스 한정 실험이 있다. 향후 방향으로는 선택된 리간드-수용체 축을 시기·세포 특이적 치료로 전환하는 것과, 미세아교세포 의존 신호 복원이 다른 CNS 손상 및 신경질환에 일반화되는지 검증하는 것이 있다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
