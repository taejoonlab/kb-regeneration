---
tags: [2026-07]
extract: 2026-07-16
---

# Single-Cell Transcriptomics and Fate Mapping of Ependymal Cells Reveals an Absence of Neural Stem Cell Function

## Citation (NLM)
Shah PT, Stratton JA, Stykel MG, Abbasi S, Sharma S, Mayr KA, Koblinger K, Whelan PJ, Biernaskie J. Single-Cell Transcriptomics and Fate Mapping of Ependymal Cells Reveals an Absence of Neural Stem Cell Function. Cell. 2018;173(4):1045-1057. doi:10.1016/j.cell.2018.03.063

**DOI:** [https://doi.org/10.1016/j.cell.2018.03.063](https://doi.org/10.1016/j.cell.2018.03.063)

---

## Background

상의세포(ependymal cell)는 뇌실계를 덮는 다섬모 상피세포로, 성체 뇌실-뇌실하영역(V-SVZ) 신경줄기세포(NSC) 니치의 일부를 구성한다. 상의세포 자체가 신경생성 능력을 획득할 수 있는 잠재적 NSC인지에 대해서는 오랫동안 논란이 있었는데, 이는 상의세포와 인접한 GFAP+ type B NSC가 여러 표지자(CD24, Sox2, Nestin, CD133)를 공유하고 둘 다 방사교세포(radial glia)에서 유래하여 생체 내에서 전향적으로 구분하기 어려웠기 때문이다. 기존에 사용된 FoxJ1 프로모터도 출생 후 V-SVZ의 NSC 일부를 표지하여, 상의세포의 신경생성능을 주장한 이전 연구들을 혼란스럽게 만들었다.

이 "Matters Arising" 논문은 신경 계통을 배제하고 상의세포만 특이적으로 표지하는 형질전환 시스템을 도입한 뒤, 단일세포 RNA-seq, 시험관 내 실험, 손상/성장인자 자극을 통해 상의세포가 줄기세포로 행동하는지를 직접 검증한다.

---

## Key Experiment Methods

1. aSMACreERT2::ROSA26 (eYFP 또는 tdTomato) 형질전환 마우스("aSMA::R26") 제작으로 tamoxifen 유도성 V-SVZ 상의세포 표지; 섬모 및 세포 정체성 표지자(acetylated-tubulin, CD133, FoxJ1, Sox2, Nestin, GFAP, Ki67)와 en-face pinwheel 분석으로 정체 검증.
2. 배아기(E17), 출생 후(P3+4), 성체(P40/41) 시점 유도로 2~5개월간 계통추적하여 표적 특이성과 후각구 신경생성 기여도 규명.
3. aSMA::eYFP 양성/음성 세포를 FACS로 분리하여 NSC 촉진 조건(FGF2+EGF, VEGF+FGF2+EGF, E13 NSC 공배양, conditioned media)에서 신경구 배양; 비상의세포(mural cell) 오염 배제를 위해 aSMACreERT2::ROSA26tdTomato/Sox2-GFP 이중 형질전환 리포터 개발.
4. FACS로 분리한 상의세포 vs 신경줄기/전구세포의 단일세포 RNA-seq(10X Chromium v2, 약 1,700 세포), 그래프 기반 클러스터링, tSNE, PAGODA 경로/유전자세트 과분산 분석.
5. 생체 내 자극: EdU 표지와 함께 뇌실 내 VEGF+bFGF 주입, 성체·신생 마우스에 collagenase 유도 선조체 뇌내출혈(ICH) 뇌졸중을 가해 손상 유도 활성화 검증.

---

## Results

- aSMA::R26는 다섬모 CD133+/FoxJ1+/Sox2+/Nestin+ 상의세포를 특이적으로 표지(뇌실벽 세포의 71%)했으며, 대부분 GFAP 음성·비증식성(Ki67 음성)이었다. P3+4 유도는 미성숙하지만 상의세포로 확정된 세포를 표지했고 이들은 알려진 rostro-caudal/dorso-ventral 성숙 패턴을 따랐다.
- FACS로 분리한 성체 상의세포는 어떤 NSC mitogen 조건에서도 증식하거나 생존하지 못한(0/600 세포) 반면, 대조군인 aSMA 음성 Sox2-GFP+ 세포는 왕성하게 자가재생 신경구를 형성했다.
- scRNA-seq: 상의세포(Acta2, Foxj1)는 신경 계통 세포와 뚜렷이 분리된 클러스터를 형성했다. 정지기 NSC 유전자(Clu, Gja1, Sox9, S100b; 2,375개 공유 유전자)를 다수 공유했음에도 섬모 관련 유전자가 풍부했고 기능적 줄기성은 없었다.
- 희소한 Flt1 발현 클러스터는 Luo 등(2015)이 보고한 "상의세포" 혈관신생 시그니처(Slco1a4, Spock2, Cldn5, Kdr, Fn1)를 재현했으나 섬모 유전자가 결여되었으며, VEGFR1(Flt1)/FN1은 실제 상의세포에서 검출되지 않아 이 희소 집단이 상의세포 전체를 대표하지 않음을 시사했다.
- 뇌실 내 VEGF+bFGF나 선조체 출혈성 뇌졸중 모두 상의세포의 증식·박리·신경생성을 유도하지 못했고, 상의세포는 GFAP만 일시적으로 상승시켰다. 증식·신경생성(EdU+ GFAP+, Dcx+) 반응은 오로지 상의세포하부의 비재조합 세포에서만 나타났다.

---

## Perspective

NSC 계통을 엄격히 배제하는 표지 전략을 이용해, 본 연구는 성체 V-SVZ 상의세포가 잠재적 NSC가 아니라 매우 안정적이고 비신경생성적인 세포임을 강력히 뒷받침하며, 상의세포 오염 표지로 혼란되었을 가능성이 큰 이전 주장들(예: Luo et al., 2015; Carlén et al., 2009)에 정면으로 반박한다. 니치의 신경생성 잠재력은 GFAP+ type B 세포에 있음을 명확히 하고 상의구획의 깨끗한 분자 시그니처를 정의했다. 한계로는 상의세포의 약 71%만 표지하는 단일(aSMA) 드라이버에 의존한 점(표지를 피한 희소 집단 가능성 잔존)과, 재생/신경생성 양상이 다를 수 있는 척수 상의세포가 아닌 뇌 V-SVZ에 초점을 둔 점이 있다. 이 결과는 뇌 상의세포를 줄기세포로 각성시키려는 치료 전략에 신중을 기할 것을 시사한다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
