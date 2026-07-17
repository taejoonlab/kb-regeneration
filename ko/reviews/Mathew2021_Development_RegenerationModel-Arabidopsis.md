---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p06.txt
---

# Model systems for regeneration: Arabidopsis

## Citation (NLM)
Mathew MM, Prasad K. Model systems for regeneration: Arabidopsis. Development. 2021;148(6):dev195347. doi:10.1242/dev.195347

**DOI:** [https://doi.org/10.1242/dev.195347](https://doi.org/10.1242/dev.195347)

---

## Overview
이 논문은 Development 저널의 "Model systems for regeneration" 시리즈에 속한 PRIMER로, 모델 식물 애기장대(Arabidopsis thaliana)를 재생(regeneration) 연구 모델로서 소개한다. 식물은 손상 부위로 동원되는 특수 세포가 없고 세포가 단단한 세포벽에 둘러싸여 있음에도 불구하고, 특정 세포유형·조직·기관의 재생부터 전체 개체의 재구축에 이르는 다양한 재생 반응을 보이는 비할 데 없는 다중스케일 재생 능력을 가진다.

동물의 재생 반응이 대개 특정 세포 계통에 제한되는 것과 달리, 식물의 재생 반응은 상당히 편재적(ubiquitous)이다. 식물은 세포 이동(cell migration) 없이도 뛰어난 가소성을 나타내며, 서로 다른 개체의 두 부분을 접목(grafting)하여 키메라를 형성하는 능력도 가진다. 애기장대는 작은 유전체, 재배 용이성, 짧은 생활사, 풍부한 종자 생산, 그리고 정교한 분자·유전·세포생물학 도구(돌연변이체, CRISPR-Cas9, IGE, DAP-seq, 호르몬 센서 등)를 갖추어 재생 중 세포 리프로그래밍 기전을 규명하기에 이상적인 모델이다.

저자들은 애기장대의 두 가지 큰 재생 양식 — 조직배양 유도 재생(tissue culture-induced)과 기계적 손상 유도 재생(mechanical injury-induced) — 을 중심으로, 배아·신초(shoot)·뿌리(root) 발생 연구에서 축적된 지식이 재생 기전 이해에 어떻게 기여하는지, 그리고 실험적·계산적 접근의 결합이 어떻게 더 깊은 통찰을 제공하는지 개괄한다.

---

## Key Topics
- **조직배양 유도 재생 (de novo organogenesis):** callus(캘러스)를 경유하는 간접 재생과 이를 우회하는 직접 재생. de novo 신초 재생과 뿌리 재생. auxin:cytokinin 비율이 뿌리/신초 운명을 결정(Skoog & Miller, 1957).
- **Callus 형성과 다능성(pluripotency) 획득:** ALF4의 auxin 신호 조절, xylem pole pericycle(XPP) 세포 기원, 뿌리 줄기세포 조절자(PLT1, PLT2, SCR, WOX5)의 동원.
- **PLT 유전자의 2단계 기전:** PLT3/5/7이 먼저 뿌리 줄기세포 조절자를 활성화해 재생 능력(competence)을 부여하고, 이후 CUC2 등 신초 촉진 인자를 활성화. 재생 능력 획득과 재생 완성이 분리됨.
- **Trans-differentiation:** callus 없이 측근 원기(LRP) 내 QC 세포가 좁은 발생 창(window) 동안 auxin/cytokinin에 반응해 신초로 직접 전환.
- **체세포 배발생(somatic embryogenesis):** BBM(=PLETHORA4)이 LEC1/2를 통해 WOX2/WOX3 활성화. ATAC-seq·RNA-seq·ChIP-seq로 auxin이 발생 단계 특이적 크로마틴 접근성을 조절함을 규명.
- **기계적 손상 유도 재생:** 뿌리 분열조직의 소규모(개별 세포·QC 복원)·대규모(절단된 뿌리 끝 복원) 재생. PLT2 gradient가 재생 경계를 지정. auxin·jasmonic acid가 ERF115–CYCD6;1–RBR-SCR-SHR 네트워크를 통해 줄기세포 활성화. 지상부의 관다발(vascular) 재생과 auxin canalization 가설(PIN1 극성화).

---

## Key Findings
- 애기장대 뿌리 끝 절단 후 복원은 배아 경로(embryonic pathway)를 따르며, 절단면 세포에서 auxin과 cytokinin 발현 영역이 잠시 중첩되어 MONOPTEROS 등 초기 배아 유전자가 발현되고 뿌리 줄기세포가 활성화된다(Efroni et al., 2016).
- 뿌리 분열조직 내에는 재생 가능/불가능을 나누는 경계가 존재하며, 이는 gradient로 발현되는 전사인자 PLT2의 용량(dosage)에 의해 지정된다. PLT2의 자가조절 루프(auto-regulatory loop)가 기관의 성장(growth)과 재생 잠재력(regeneration)을 구별한다(Durgaprasad et al., 2019).
- callus 매개 신초 재생과 trans-differentiation 모두에서 뿌리 줄기세포 조절자의 일시적 발현이 공통적으로 요구된다. plt3/5/7 돌연변이체는 외부 cytokinin이 충분해도 LRP 전환에 실패한다.
- callus 매개 신초 재생 시 SAM의 de novo 조립은 배발생 중 SAM 발생과는 구별되는 경로를 따르며, 재생 세포의 자기조직화(self-organization) 성질에 의해 유도된다.
- 재생 조절자들이 정상 발생에서도 요구되어, 재생 기전과 발생 기전 간 상호작용의 좋은 예를 제공한다.

---

## Perspective
애기장대는 정교한 유전·세포·유전체 도구와 배아·신초·뿌리 발생에 대한 풍부한 지식을 바탕으로, 재생 중 세포 리프로그래밍의 세포·분자 기전을 심층 규명할 수 있는 이상적 모델이다. 다양한 재생 반응(뿌리 끝 복원, QC 재생, 관다발 재생, 체세포 배발생)이 auxin을 중심으로 한 호르몬 신호와 보존된 줄기세포 조절 네트워크로 수렴한다는 점이 강조된다. 다만 callus의 이질성(heterogeneity)과 자기조직화의 분자적 본질은 아직 충분히 규명되지 않은 한계로 남아 있다. 향후 실험적·계산적 접근의 결합과 다른 식물종으로의 확장이 재생의 보편 원리와 종 특이적 변이를 밝히는 데 기여할 것으로 전망된다. 식물 재생 모델은 세포 이동에 의존하지 않는 리프로그래밍·transdifferentiation·다능성 획득이라는 개념을 통해 동물(척수 포함) 재생 연구에 비교생물학적 통찰을 제공할 수 있다.

---

## Key References
- Iwafuchi-Doi M, et al. — 언급된 발생·리프로그래밍 관련 연구.
- Skoog F, Miller CO (1957) auxin:cytokinin 비율에 의한 뿌리/신초 운명 결정.
- van den Berg C, et al. (1995) 뿌리 분열조직의 위치 신호와 QC 재생. *Nature*.
- Xu J, et al. (2006) QC ablation 후 auxin 재분포에 의한 새 QC 재생.
- Efroni I, et al. (2016) 뿌리 끝 절단 복원이 배아 경로를 따름 (lineage tracing·single-cell RNA-seq·live imaging).
- Kareem A, et al. (2015) PLT3/5/7의 2단계 신초 재생 기전. *Curr Biol*.
- Durgaprasad K, et al. (2019) PLT2 자가조절 루프가 성장과 재생 잠재력을 구별.
- Rosspopoff O, et al. (2017) LRP QC 세포의 가소성과 신초 trans-differentiation.
- Zhou W, et al. (2019) auxin·jasmonate–ERF115·CYCD6;1–RBR-SCR-SHR 네트워크에 의한 뿌리 재생.
- Kadokura S, et al. (2018) 어린 잎 원기 기저부에서 유래하는 체세포 배발생 (RNA-seq·live-imaging).
- Wang FX, et al. (2020) 체세포 배발생 중 auxin에 의한 단계 특이적 크로마틴 접근성 조절 (ATAC-seq·RNA-seq·ChIP-seq).
- Hajný J, et al. (2020) 인산화 PIN1 극성화에 의한 auxin canalization과 관다발 재생.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
