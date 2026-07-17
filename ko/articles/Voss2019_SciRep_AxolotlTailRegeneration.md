---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p09.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# HDAC Regulates Transcription at the Outset of Axolotl Tail Regeneration

## Citation (NLM)
Voss SR, Ponomareva LV, Dwaraka VB, Pardue KE, Al Haj Baddar NW, Rodgers AK, Woodcock MR, Qiu Q, Crowner A, Blichmann D, Khatri S, Thorson JS. HDAC Regulates Transcription at the Outset of Axolotl Tail Regeneration. Sci Rep. 2019;9:6751. doi:10.1038/s41598-019-43230-6

**DOI:** [https://doi.org/10.1038/s41598-019-43230-6](https://doi.org/10.1038/s41598-019-43230-6)

---

## Background
아홀로틀(Ambystoma mexicanum) 같은 재생능이 뛰어난 도롱뇽은 흉터 없이 조직을 복구하며, 척수를 포함한 꼬리 등 부속기를 재생할 수 있다. 재생 과정에는 전사인자와 히스톤의 번역후변형을 포함한 복잡한 유전자 발현 변화가 동반된다. 손상 신호는 부분적으로 후성유전 기전(DNA 메틸화, 히스톤 아세틸화/탈아세틸화)을 통해 염색질 구조를 바꾸며 작용하는 것으로 여겨진다. 발프로산(VPA)과 트리코스타틴 A를 이용한 선행 연구들은 양서류 꼬리 재생에 손상 후 초기 수 시간 내 히스톤 탈아세틸화효소(HDAC) 활성이 필요함을 시사했으나, 이를 뒷받침하는 전사체 증거는 부족했다.

본 연구는 아홀로틀 배아 꼬리 절단 분석에서 후성유전 표적 화합물을 이용한 화학유전 스크리닝을 통해 재생에 필요한 후성유전 기전을 규명하고, HDAC 활성이 언제 필요한지를 전사 수준에서 정의하였다.

---

## Key Experiment Methods
1. 발생 42단계 아홀로틀 배아의 꼬리 절단(원위 꼬리 약 2 mm, 몸길이의 약 20% 제거) 분석, 절단 후 7일(dpa)에 평가.
2. 172종의 후성유전 표적 화합물(Structural Genomics Consortium 패널 + Selleckchem 라이브러리)을 10 μM(및 20 μM 재검증)에서 스크리닝, 생존과 꼬리 패턴 형성을 평가.
3. class I HDAC 억제제 romidepsin과 belinostat(FDA 승인 항암제)를 이용한 시간대별 투여 실험: 절단 후 1분(mpa)부터 7 dpa 연속 처리까지 처리 창을 변화.
4. 마이크로어레이 분석(Ambystoma Affymetrix array): 대조군 대비 romidepsin/belinostat 처리 배아를 0, 12, 24, 48, 72 hpa에 분석; 추가로 3·6 hpa(0–3 hpa 처리)와 3 hpa(0–1 mpa 처리) 분석. 데이터는 GEO(GSE118515)에 등록.
5. 유전자 온톨로지 농축 분석(PANTHER); limma를 이용한 차등발현 분석(FDR <0.05, 1.5배 이상 변화 기준).
6. 절단면 부근 분열 세포를 3 hpa에 계수하는 EdU 세포증식 분석.

---

## Results
- 172종 중 55종이 재현성 있게 꼬리 재생을 억제했으며, HDAC 억제제가 가장 빈번한 히트 계열(18종)이었고 브로모도메인 억제제(8종)가 뒤를 이었다. 히트의 약 47%가 라이신 아세틸화의 writing/reading과 관련되었다.
- Romidepsin(class I HDACi)은 재생을 강력히 차단했으며, 절단 후 단 1분(≥1.0 μM) 처리만으로도 7 dpa에서 재생을 막기에 충분하여 좁은 손상 후 시간창을 정의하였다. 절단 24시간 전 전처리는 억제하지 못했다.
- Romidepsin 처리 배아는 7 dpa 이후 결국 재생을 재개했으나 비정상적이고 가변적인 꼬리지느러미 패턴을 보였으며, 처리 시간이 길수록 결함이 심했다. 21 dpa에서 재생된 척수 길이는 대조군과 차이가 없어, 약물이 꼬리지느러미 중간엽 전구세포에 특이적으로 작용하며 척수 재생에는 꼬리지느러미 성장이 필요함을 시사한다.
- 마이크로어레이: romidepsin은 3·6 hpa의 초기 전사를 변화시켜 다수의 전사조절자, 신호전달 인자, 패턴형성 유전자(Notch, BMP, Wnt, TGFβ, FGF, 레티노산 경로; Hox 유전자)에 영향을 주었다. 상향조절된 110개 유전자가 전사조절 단백질을 코딩한다. 효과는 매우 재현성이 높았다(0–3 hpa와 0–1 mpa 처리 간 r = 0.94).
- Romidepsin과 belinostat는 유사한 방향의 발현 변화를 유도했으며 romidepsin이 더 강력했다(용량 의존적, 조절 가능).
- EdU 계수 결과 3 hpa에서 분열 세포의 유의한 감소가 없어, 급성 재생 억제는 전반적 세포주기 정지에 의한 것이 아니었다.

---

## Perspective
본 연구는 성공적인 꼬리(및 척수) 재생을 가능하게 하는 초기 전사 반응을 형성하기 위해 손상 순간에 class I HDAC 활성이 필요함을 전사 수준에서 직접적으로 입증한다. 아홀로틀 배아를 후성유전 조절과 재생능을 연결하는 다루기 쉬운 화학유전 모델로 확립하고, 암(HDACi/브로모도메인 표적)과 조직 재생이 공유하는 기전 간 유사성을 제시한다. 한계로는 마이크로어레이 데이터의 상관적 성격, 풍부한 배아 증식 배경에서 어떤 특정 세포집단이 영향을 받는지 규명하지 못한 점, 직접적 히스톤 아세틸화 측정의 부재 등이 있다. 향후 방향으로는 세포유형 분해 분석, 브로모도메인 억제제 비교, 재생 특이적 신호가 HDAC 코리프레서 복합체를 탈억제하여 전사를 시공간적으로 조절하는지 검증하는 연구가 있다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
