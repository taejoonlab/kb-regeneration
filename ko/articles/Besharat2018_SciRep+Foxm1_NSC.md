---
tags: [2026-07]
extract: 2026-07-16
---

# Foxm1은 신경 줄기세포에서 stemness 촉진 microRNA 네트워크를 조절한다

## Citation (NLM)
Besharat ZM, Abballe L, Cicconardi F, Bhutkar A, Grassi L, Le Pera L, Moretti M, Chinappi M, D'Andrea D, Mastronuzzi A, Ianari A, Vacca A, De Smaele E, Locatelli F, Po A, Miele E, Ferretti E. Foxm1 controls a pro-stemness microRNA network in neural stem cells. Sci Rep. 2018;8:3523. doi:10.1038/s41598-018-21876-y

**DOI:** [https://doi.org/10.1038/s41598-018-21876-y](https://doi.org/10.1038/s41598-018-21876-y)

---

## Background
신경 줄기세포(NSC)는 자가재생(self-renewal)과 다분화능(multipotency)을 특징으로 하며, 이는 전사인자와 후성유전학적 조절에 의해 결정된다. NSC 유지 기전의 이해는 중요한데, 이는 언젠가 조직 손상 복구나 신경퇴행성 질환(파킨슨병, 헌팅턴병, 다발성 경화증) 또는 척수 손상에서 재생 능력을 향상시키는 데 활용될 수 있기 때문이다.

소뇌 NSC는 유지를 위해 Hedgehog-Gli(Hh-Gli) 신호전달을, 자가재생을 위해 Nanog 발현을 필요로 한다. 저자들은 이전에 Gli1/Gli2가 Nanog를 직접 조절하고, Hh-Gli 유도 Nanog가 세포주기 정지 및 분화를 촉진하는 유전자를 억제하는 일련의 microRNA를 조절함을 보였다. 본 연구에서는 차세대 mRNA·miRNA 시퀀싱을 이용하여 초기 출생 후 소뇌 NSC에서 이 Hh-Gli 유도 분자 네트워크를 더 탐구하고, Hh 조절 자가재생에 관여하는 추가 분자 인자를 동정하고자 하였다.

---

## Key Experiment Methods
1. **mRNA-seq 및 miRNA-seq**(paired-end polyA+ RNA-seq): 줄기세포 선택 배지에서 배양한 출생 후 4일(P4) 생쥐 소뇌 NSC와 분화 유도 후(Diff-NSC) 비교, 각 3반복.
2. **기능/GO 분석**: DAVID 플랫폼으로 차등 발현 전사체 분석.
3. **RT-qPCR 검증**: 생쥐 NSC 및 정상 인간 신경 전구세포(NHNP)에서, Smoothened 억제제 cyclopamine-KAAD 처리로 Hh 신호 억제 후 포함.
4. **Foxm1 siRNA 넉다운** 및 neurosphere 형성 분석으로 자가재생 평가.
5. **qPCR-ChIP 분석**: Gli1, Gli2, Nanog, Foxm1의 프로모터/miRNA 프로모터 점유 및 AcH3(전사 활성화 표지) 측정, 추정 결합 부위 부위 특이적 돌연변이 유발.
6. **Luciferase 리포터 분석**: NSC 및 293T 세포에서 Foxm1 프로모터.
7. **LNA 매개 miRNA 고갈**(miR-130b, miR-301a, miR-19a, miR-15b): 단독 및 조합, neurosphere 분석.

---

## Results
- NSC와 Diff-NSC 사이에 988개 유전자가 차등 전사되었고, GO 분석은 세포주기, DNA 복제, p53 신호전달(NSC 자가재생의 알려진 음성 조절자)을 강조.
- Foxm1은 분화 전 NSC에서 가장 뚜렷하게 농축된 Hh-Gli 조절 전사인자였다. cyclopamine-KAAD로 Hh를 억제하면 생쥐 NSC와 인간 NHNP 모두에서 Foxm1 mRNA가 감소. 757 아미노산 Foxm1-201 isoform이 우세.
- ChIP 및 luciferase 분석은 Gli1과 Gli2가 Foxm1 프로모터(추정 Gli 결합 부위 8개)를 직접 점유하고 활성화하며, Diff-NSC보다 NSC에서 점유가 더 높음을 보임.
- Foxm1 넉다운은 neurosphere 형성을 유의하게 손상시키고 분화 표지자(βIII-tubulin, S100b)를 상향조절했으나 증식·세포자멸 표지자는 영향을 주지 않았고, Hh 억제와 부가적 효과는 없었다.
- miRNA-seq는 80개의 차등 발현 miRNA를 동정했고, NSC에서 상향조절된 40개 중 20개가 추정 Foxm1 결합 부위를 가졌다. ChIP은 miR-130b, miR-301a, miR-15~16 및 miR-17~92 클러스터 구성원에서 유의한 Foxm1 동원을 확인.
- miR-130b, miR-301a, miR-19a(및 선택적으로 miR-15b)의 LNA 조합 고갈은 neurosphere 형성을 유의하게 손상시키고 분화 표지자를 상향조절한 반면, 단일 넉다운은 그렇지 않았다.
- 이 miRNA들은 p53 경로로 수렴하며, 여러 개가 Trp53inp1(p53 경로 구성 요소)을 추정 표적으로 하여 Foxm1을 stemness 유지에 필요한 p53 억제와 연결한다.
- Nanog는 Foxm1 프로모터(추정 부위 4개; s2-s3가 기능적으로 필요)에 결합했고, Foxm1 자체도 Nanog를 표적함이 알려져 있어 양방향 Nanog-Foxm1 상호작용을 드러냄. Nanog와 Foxm1 조절 miRNA 네트워크는 miR-17~92 클러스터를 제외하고 대부분 겹치지 않았다.

---

## Perspective
본 연구는 소뇌 NSC 자가재생을 조절하는 새로운 Hh-Gli-Nanog 유도 Foxm1-microRNA 네트워크를 정의하며, Foxm1은 Nanog와 함께 stemness 촉진 miRNA를 상향조절하여 p53 경로 억제(Trp53inp1 경유)로 수렴하는 두 번째 전사 활성인자로 작용한다. 이는 NSC 자가재생을 견고하게 유지하는 조합적·부분적으로 중복된 "우회 축(bypass axis)"을 제안한다. 의의: NSC에서 stemness와 분화 간 미세조정에 대한 이해를 심화하며, 이는 NSC를 치료/재생 인자로 활용할 가능성과 관련된다. 한계: miR-130b와 miR-301a가 Trp53inp1을 하향조절하는 능력은 향후 직접 검증이 필요하고, 다른 miRNA 기전을 배제할 수 없으며, 결과는 주로 출생 후 생쥐 소뇌 NSC에서 도출되었다. Hh-Gli-Foxm1 축은 암에서의 확립된 역할을 감안할 때 소뇌 종양 생물학에도 함의를 갖는다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
