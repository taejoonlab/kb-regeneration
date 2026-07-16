---
tags: [2026-07]
extract: 2026-07-16
---

# Mapping the Global Chromatin Connectivity Network for Sox2 Function in Neural Stem Cell Maintenance

## Citation (NLM)
Bertolini JA, Favaro R, Zhu Y, Pagin M, Ngan CY, Wong CH, et al. Mapping the Global Chromatin Connectivity Network for Sox2 Function in Neural Stem Cell Maintenance. Cell Stem Cell. 2019;24(3):462-476. doi:10.1016/j.stem.2019.02.004

**DOI:** [https://doi.org/10.1016/j.stem.2019.02.004](https://doi.org/10.1016/j.stem.2019.02.004)

---

## Background

SOX2는 다능성(pluripotency)에 필수적인 전사인자이면서 신경줄기세포(NSC) 유지와 정상적인 뇌 발생에도 결정적이다. 사람에서 SOX2 돌연변이는 우성 신경계 질환(해마·눈 결함, 뇌전증, 학습장애)을 일으키며, 마우스에서 Sox2 결손은 해마 형성저하, 소뇌증, 복측 전뇌 고갈, 무안구증을 유발하는데 이 중 일부는 NSC 자기재생 결함에서 비롯된다. Sox2가 결손된 NSC는 장기 배양에서 자기재생에 실패한다.

전사 조절은 프로모터와 원거리 enhancer 사이의 DNA 루핑을 통해 이루어지며, 이는 세포 유형 특이적인 게놈 전역 상호작용 네트워크("connectome")를 형성한다. 단일 전사인자가 이러한 게놈 전역 상호작용 네트워크의 기능을 어느 정도로 결정하는지는 알려져 있지 않았다. 본 연구는 ChIP와 염색질 상호작용 분석(ChIA-PET)을 이용해 뇌 유래 NSC에서 게놈 전역 SOX2 결합 영역과 Pol II 매개 장거리 상호작용을 규명하고, NSC 자기재생을 좌우하는 SOX2 의존성 유전자를 찾고자 한다.

---

## Key Experiment Methods

1. E11.5에 조건부로 Sox2가 제거된 마우스(MUT)와 대조군의 신생아(P0) 전뇌에서 NSC 배양 확립.
2. Pol II ChIA-PET(원래의 pooled 방식 및 개선된 in situ ChIA-PET)으로 WT/MUT NSC의 게놈 전역 Pol II 매개 장거리 염색질 상호작용 매핑(3반복: wTR1-3, mTR1-3).
3. WT NSC의 SOX2 ChIP-seq, WT/MUT NSC의 히스톤 변형(H3K27ac, H3K4me1) ChIP-seq으로 활성/poised enhancer 분류(peak-calling 및 chromHMM).
4. 상호작용 anchor/node를 프로모터(TSS ±2.5 kb 이내) 또는 비프로모터(enhancer)로 분류하고, SOX2 결합을 후성유전 표지 및 상호작용과 통합.
5. 제브라피시에서 transgenic enhancer-reporter(GFP) 분석으로 SOX2 결합 원거리 anchor의 전뇌 enhancer 활성 검증; anti-Sox2 morpholino 및 Sox2 mRNA 주입으로 교란.
6. WT/MUT NSC의 RNA-seq로 유전자 발현과 상호작용 범주 상관 분석; 발현 그룹과 상호작용 유형의 co-association 점수화.
7. WT/MUT NSC에 lentiviral Socs3(GFP 공발현) 과발현, 성장 곡선 및 FACS 기반 장기 자기재생 회복 분석.

---

## Results

- Sox2 결손은 게놈 전역 염색질 연결성을 크게 감소시켰다: 정규화된 유의 상호작용이 WT의 백만 intra-molecular PET당 약 6-10K에서 MUT의 약 2-3K로 감소했으며, 감소 정도는 loci마다 매우 다양했다(일부 급감, 일부 불변, MUT에서 드물게 새 loop 출현).
- 이 감소는 Pol II 면역침전 효율 차이 때문이 아니었다: WT ChIA-PET Pol II 결합 영역의 약 92%가 MUT에서 유지되었고 Pol II 밀도 프로파일도 매우 유사했다.
- SOX2 결합 부위는 프로모터에는 드물고 대부분 인트론/유전자간 원거리 영역에 위치했으며 90% 이상이 enhancer 표지(주로 H3K27ac+)를 지녔다. WT 상호작용의 약 35-46%가 최소 한 anchor에 SOX2 결합 부위를 포함했다. SOX2 양성 후성유전 표지 원거리 영역은 SOX2 음성 표지 영역보다 상호작용에 훨씬 더 많이 관여했다.
- SOX2 의존성 원거리 anchor는 새로운 전뇌 enhancer를 예측했다: 17개 리포터 구성체 중 15개가 발생 중 제브라피시 전뇌로 GFP를 유도했고 내인성 ortholog 패턴과 일치했다. anchor는 알려진 VISTA 전뇌 enhancer와 겹쳤으며 MUT에서는 VISTA 중첩이 급감했다.
- 프로모터-enhancer(P-E) 상호작용, 특히 SOX2 양성 P-E 상호작용에 관여하는 유전자가 가장 높은 발현을 보였고, 유전자당 P-E 상호작용 수가 늘수록 발현이 증가했다.
- Sox2 손실은 약 1,000개 유전자를 하향 조절했다. MUT에서 유의하게 발현이 감소한 유전자는 WT의 "프로모터-SOX2 결합 enhancer" 상호작용에 크게 편중되어 있었던 반면, 프로모터에서의 SOX2 결합은 발현 변화와 약하게만 연관되었다. P-P 상호작용은 경미한 발현 감소와만 상관이 있었다.
- Socs3(Jak/Stat 억제자, 다중 연결된 SOX2 표적, MUT에서 10-15%로 감소)의 lentiviral 과발현은 MUT NSC에서 강하게 선택 부화되어 장기 자기재생 결함을 회복시켰다. WT NSC는 추가로 선택되지 않아 WT에서는 내인성 SOCS3가 제한 요인이 아님을 시사했다.
- Sox2 손실은 enhancer 히스톤 표지(H3K27ac/H3K4me1)를 실질적으로 변화시키지 않아, SOX2가 표지를 확립하기보다는 상호작용/발현에 작용함을 시사했다(E11.5 결손, 표지가 이미 확립된 이후일 수 있음).

---

## Perspective

본 연구는 SOX2가 NSC에서 enhancer 연결성 네트워크를 통해 유전자 발현을 조절하는 주요 인자임을 확립하고, 단일 서열 특이적 전사인자가 게놈 전역 장거리 염색질 상호작용을 형성할 수 있음을 보였다. 프로모터 결합이 아닌 SOX2 결합 원거리 enhancer가 SOX2 의존성 전사를 주로 이끌며, 단일 하류 표적(Socs3)이 자기재생을 회복시킨다는 발견은 NSC 유지와 신경발생 질환에 관여하는 유전자·enhancer를 규명하는 경로를 제공한다.

한계로는 어떤 유전자도 완전히 침묵되지 않고 상호작용이 완전히 소실되기보다 감소한다는 점(드문 상호작용 PET의 검출 민감도 문제로 특정 단일 상호작용의 완전 소실 입증이 어려움), 그리고 Sox2 손실 후에도 enhancer 표지가 유지되어 SOX2가 상호작용을 생성하는지 안정화하는지가 미해결로 남는다는 점이 있다. 최근 enhancer-promoter 매개자로 규명된 YY1(NPC 특이적 상호작용에 결합)과의 관계, SOX2 파트너 복합체(NurD, SWI/SNF, CHD7, SMRT/NCOR)의 기여가 향후 과제로 제시된다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
