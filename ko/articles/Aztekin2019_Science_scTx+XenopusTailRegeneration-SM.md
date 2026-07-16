---
tags: [2026-07]
extract: 2026-07-16
---

# Identification of a regeneration-organizing cell in the Xenopus tail (Supplementary Materials)

## Citation (NLM)
Aztekin C, Hiscock TW, Marioni JC, Gurdon JB, Simons BD, Jullien J. Identification of a regeneration-organizing cell in the Xenopus tail. Science. 2019;364(6441):653-658. doi:10.1126/science.aav9996 [Supplementary Materials, Materials and Methods, Figs. S1-S11, Tables S1-S3]

**DOI:** [https://doi.org/10.1126/science.aav9996](https://doi.org/10.1126/science.aav9996)

---

## Background
본 문서는 재생 중인 *Xenopus laevis* 꼬리에서 재생 조직화 세포(ROC)를 규명한 *Science* 원저 논문의 부록(Supplementary Materials)이다. 재생 가능·불가능 올챙이의 scRNA-seq을 통해 절단면으로 재배치되어 특수화된 상처 표피를 형성하고 재생 신호 중심으로 작용하는 LEF1+/TP63+ 표피 세포 유형을 밝힌 본 연구의 상세 재료 및 방법과 부록 그림·표 설명을 제공한다.

---

## Key Experiment Methods
1. **올챙이 사육 및 재생 분석:** 0.1X MMR에서 사육; 재생 가능 NF 40-41기, 불가능 NF 46-47기; 꼬리 약 30-50% 절단; 7 dpa에 채점(excellent/good/partial/none)하여 재생 지수(3/2/1/0점)로 환산.
2. **단일세포 해리 및 시퀀싱:** trypsin으로 해리, 생존 단일세포(PI 음성, Hoechst 양성) 선별(Sony SH800s); 10X Genomics 라이브러리를 Illumina HiSeq 4000으로 시퀀싱.
3. **데이터 처리:** CellRanger v2.1.0로 *X. laevis* 9.1 유전체(Xenbase)에 정렬; TPX(전사체/10^4) 정규화; 유사사배수체 특성상 대립유전자별(Gene.L / Gene.S) 발현 유지.
4. **시각화/클러스터링:** 고변이 유전자(Fano factor) 선택; UMAP; fuzzy-simplicial-set 그래프 + walktrap 클러스터링; 마커 유전자로 46개 클러스터 주석(그림 S1), 그중 23개는 광의 라벨.
5. **차등 존재비:** cydar 질량세포측정 방식을 따른 edgeR, 1 dpa 재생 가능 vs. 불가능 비교.
6. **GO / 유전자세트 농축:** scran findMarkers로 ROC 마커; 인간 상동유전자 GO 농축; AUCell scGSEA; Seurat CellCycleScoring으로 세포주기 상 추정.
7. **미세수술/이식:** "large"(꼬리싹 전구세포 + 피부) 및 "small"(피부만) 이식편을 숙주 몸통에 이식.
8. **면역형광:** TP63, EGFP, PCNA, PHH3, NCAM1, COL2A1 항체; pbin7Lef:GFP 올챙이 생체 이미징.
9. **화학적 교란:** DPI, SU5402(FGF), SB-505124(TGFβ)로 ROC 이동 평가.
10. **유전적 제거:** Krt.L:CFP-NTR 형질전환 + metronidazole(MTZ); NTR/MTZ 제거와 이식 결합.

---

## Results
- **그림 S1:** 46개 클러스터의 세포 상태 규명(피부, 면역/적혈구, 체절, 신경계); 신경 분화 마커 Hes1(전구세포/바닥판), Neurod4(분화 중 뉴런), Tubb3(최종 뉴런).
- **그림 S2:** 생물학적 반복이 UMAP에서 혼합되어 아틀라스 재현성 확인.
- **그림 S3:** 추정 세포주기 상이 전구세포, 최종 분화 세포, 분열 중 적혈구(GATA1:GFP+ / PCNA+ / PHH3+)를 구분.
- **그림 S4:** 시료 쌍별 비교로 발생성·절단·재생 특이적 변화 구분; 차등 존재비 분석에서 ROC 변화가 1 dpa의 가장 유의한 재생 특이적 사건으로 순위화.
- **그림 S5:** ROC를 절단면의 재생 특이적 표피 세포(TP63+/LEF1+)로 확인; 절단 후 제거되었다가 재생 가능 올챙이에서만 상처 표피에 재출현.
- **그림 S6-S7:** Krt.L:NTR/MTZ가 뚜렷한 표적외 효과 없이 ROC를 특이적으로 제거; 유전적 제거 또는 수동 적출이 재생을 감소시키며, ROC 제거 정도가 재생 결과와 상관.
- **그림 S8:** DPI와 SB-505124(TGFβ)는 ROC 이동을 차단하나 FGF 억제(SU5402)는 차단하지 않음.
- **그림 S9:** ROC는 높은 리간드를, 전구세포는 수용체를 발현(FGF, BMP, WNT, TGFβ, Notch-Delta 전반에 걸친 상보적 리간드/수용체 쌍).
- **그림 S10:** ROC 전사체가 사지 발생 유전자 및 GO 항목에서 농축.
- **그림 S11:** ROC 함유 부위 이식이 이소성 꼬리형(large) 또는 지느러미형(small) 구조 유도; 공여체 ROC의 Krt.L:NTR/MTZ 제거는 돌출 길이를 유의하게 감소.
- **표 S1-S3:** scRNA-seq QC 요약(>13,000 세포), 정중선 표피의 기발표 ROC 마커 유전자, 세포주기/scGSEA 분석용 유전자 목록.

---

## Perspective
부록은 ROC 발견의 계산적·실험적 엄밀성을 문서화한다: 재현 가능한 반복 구조, ROC를 지배적 재생 특이적 변화로 지목하는 차등 존재비 순위, 그리고 유전적 제거·수동 적출·화학적 교란·이식이라는 직교적 기능 검증이다. 이들은 ROC가 특수화된 상처 표피를 형성하고 리간드를 분비하는 신호 중심으로 작용한다는 본 결론을 뒷받침한다.

부록에 언급된 한계로는 차등 존재비 검정의 낮은 반복수(n=2, 검정 통계량 과장), 약 절반의 클러스터를 명확히 주석하지 못한 점, 그리고 대립유전자별 해석이 필요한 유사사배수체 *X. laevis* 유전체 의존이 있다. 향후 아틀라스 기반 접근을 다른 재생 종으로 확장하는 것이 과제이다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
