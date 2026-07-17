---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p04.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# hoxc12/c13 as key regulators for rebooting the developmental program in Xenopus limb regeneration

## Citation (NLM)
Kawasumi-Kita A, Lee SW, Ohtsuka D, Niimi K, Asakura Y, Kitajima K, Sakane Y, Tamura K, Ochi H, Suzuki KT, Morishita Y. hoxc12/c13 as key regulators for rebooting the developmental program in Xenopus limb regeneration. Nat Commun. 2024;15:3340. doi:10.1038/s41467-024-47093-y

**DOI:** [https://doi.org/10.1038/s41467-024-47093-y](https://doi.org/10.1038/s41467-024-47093-y)

---

## Background

기관 재생 과정에서, 손상에 대한 초기 반응(상처 치유, blastema 형성, apical ectodermal cap 형성) 이후의 형태형성(morphogenesis) 단계 동안 정상 발생과 유사한 유전자 발현 패턴이 재확립된다. 이는 "재생이 발생을 재현한다(regeneration recapitulates development)"는 개념을 뒷받침하며, 초기 손상 반응 이후 발생 프로그램을 재가동(reboot)하는 유전자의 존재를 예측하게 한다. 그러나 이러한 재가동 기전은 대부분 알려지지 않았다.

Xenopus는 생애 단계에 따라 재생 능력이 다르다는 점에서 유용한 모델이다. 유생은 완전한 사지를 재생하지만, 변태 후 froglet/성체는 초기 blastema를 형성함에도 연골·피부로 된 막대 모양의 "spike"만 형성한다. 이로 인해 Xenopus froglet/성체 사지는 재생 능력 향상 전략의 gain-of-function 모델로 널리 연구되어 왔다. 저자들은 유생 사지 재생 중 발생 프로그램을 재가동하는, 알려진 발생 유전자(shh, fgfs)와 구별되는 재생 특이적 인자를 탐색하고, 이를 유도하면 froglet 재생을 개선할 수 있는지 검증하고자 했다.

---

## Key Experiment Methods

1. **비교 전사체 분석**: Xenopus laevis 발생 중 사지 싹(8 샘플: St. 52, 52.5, 53, 54의 distal/proximal; devDi/devPi)과 유생 재생 blastema(2 시점의 distal/proximal 4 샘플; regDi/regPi) — 총 12 샘플 유형을 삼중 반복 시퀀싱, 주성분 분석(PCA) 및 차등발현유전자(DEG) 정량.
2. **3단계 스크리닝**: (1단계) 대응 쌍 간 차등발현 1488 유전자, (2단계) 재생 시 distal>proximal 발현 104 유전자, (3단계) 재생 특이성 점수(최대 8점)로 상위 10개 유전자 선별.
3. **RNAscope**: hoxc12.L, hoxc13.L, hoxa13.L(autopod 마커), hoxa11.L(zeugopod 마커) 공간 발현 분석.
4. **CRISPR/Cas9 녹아웃**: 이배체 Xenopus tropicalis에서 hoxc12, hoxc13 (ATG 표적) 각각 녹아웃; 왼쪽 뒷다리를 예정 무릎 부위(~St. 52)에서 절단, 오른쪽 뒷다리를 발생 대조군으로 사용; 발가락 수로 표현형 평가.
5. **마커 분석**: msx1(초기 blastema), 패턴형성 유전자(shh, hoxd13, hoxa13, hoxa11, fgf8)의 RNAscope/qPCR/bulk 전사체, hoxa13 정의 예정 autopod 영역의 PH3+ 세포 증식 계수.
6. **Gain-of-function**: heat-shock(hsp70) 유도성 hoxc12/c13을 2A 펩타이드로 GFP와 연결한 형질전환 Xenopus laevis 제작; froglet blastema에 국소 heat shock; 형태학적·조직학적(신경/근육)·전사체 분석.

---

## Results

- hoxc12와 hoxc13(전사인자)이 발현에서 가장 높은 재생 특이성을 보였으며, 재생 조직(regD1/regD2)에서의 발현 수준이 다른 샘플보다 수 배~10배 높았다. 둘 다 재생 blastema의 예정 autopod 영역에서 발현되었으나, 발생 중에는 hoxc12만 zeugopod에 국한된 명확한 발현을 보였다.
- hoxc12 또는 hoxc13 녹아웃은 사지 발생(결손 0/98, 0/69)과 초기 blastema 형성(정상적 상처 치유, 원뿔형 blastema, 정상 msx1 발현)에는 영향이 없었으나, 유생 재생에서 심각한 autopod 재생 결손(약 40~50% 이상, 발가락 수 감소)을 유발했다.
- hoxc12/c13은 축 패턴형성 유전자의 재활성화에 필요하다: 심각한 표현형의 녹아웃에서 shh, hoxd13(후방/원위)은 거의 발현되지 않았고, fgf8·hoxa13은 감소했으며, P-D 영역화가 실패했다(hoxa11이 비정상적으로 최원위부까지 발현). Bulk 전사체는 근위 인자(meis1/2)를 제외한 패턴형성 유전자의 광범위한 하향조절을 확인했고, 이는 hoxc13이 단일 경로가 아니라 유전자 집합의 재가동을 제어함을 시사한다.
- 증식(PH3+ 세포)은 녹아웃의 hoxa13 발현 예정 autopod 영역에서 특이적으로 유의하게 감소했다.
- Gain-of-function: froglet blastema에서 heat-shock으로 hoxc12/c13을 유도하면 AP 방향으로 넓어진 bulge가 형성되었고, 놀랍게도 인위적 heat shock 없이도 절단 스트레스로 transgene이 유도된 형질전환 froglet의 약 1/3(hoxc12Tg 10/30, hoxc13Tg 7/21)에서 원위 연골의 삼지/이지 분지 및 노 모양(paddle-like)이 나타났다. Tg 분지에서 세포 증식과 신경 양이 증가했으나(근육은 재생되지 않음), 전사체는 발생 사지 싹 상태로 이동했다.
- 과도한 heat-shock 발현은 분지를 억제하여, 적절한 발현 수준이 필요함을 시사한다. 분지된 연골에 명확한 관절이 없어, 완전 재생을 위해서는 hoxc12/c13 외 추가 재가동 인자가 필요하다.

---

## Perspective

이 연구는 특정 유전자(hoxc12/c13)가 단독으로 재생 특이적 방식으로 발생 프로그램의 재가동에 심대한 영향을 미칠 수 있음을 입증했다. 이들은 정상 발생이나 초기 blastema 형성에는 영향을 주지 않고, 초기 손상 반응 이후 형태형성 단계에서 작동한다. 이는 "재생이 발생을 재현한다"는 가설을 구체적인 분자적 방아쇠와 연결하며, 유도 발현을 통해 변태 후(froglet)의 매우 제한된 재생 능력을 부분적으로 회복시킴을 보여준다.

한계: gain-of-function은 재생을 부분적으로만 회복시켰다 — 분지 연골에 관절 유사 구조가 없었고, Tg 분지에서 근육이 재생되지 않았으며, 완전 재생은 달성되지 않아 추가 재가동 인자가 필요함을 시사한다. 녹아웃은 X. tropicalis를, 형질전환은 X. laevis를 사용했다. 향후 방향으로는 재가동 인자 전체 규명, hoxc12/c13의 상류 조절인자 및 정확한 수준 의존성, 그리고 이러한 재가동 전략을 포유류를 포함한 재생 능력이 낮은 종의 재생 향상으로 전환하는 것이 포함된다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
