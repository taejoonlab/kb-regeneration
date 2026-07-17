---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
---

# Genomic Rewiring of SOX2 Chromatin Interaction Network during Differentiation of ESCs to Postmitotic Neurons

## Citation (NLM)
Bunina D, Abazova N, Diaz N, Noh KM, Krijgsveld J, Zaugg JB. Genomic Rewiring of SOX2 Chromatin Interaction Network during Differentiation of ESCs to Postmitotic Neurons. Cell Syst. 2020;10(6):480-494. doi:10.1016/j.cels.2020.05.003

**DOI:** [https://doi.org/10.1016/j.cels.2020.05.003](https://doi.org/10.1016/j.cels.2020.05.003)

---

## Background

세포 분화에는 염색질 구조, 전사, 단백질 생산의 협응된 변화가 필요하다. 세포 유형 특이적 유전자 발현은 전사인자(TF)가 유전자 조절 네트워크를 통해 이끌며, TF의 DNA 결합은 염색질 접근성, 히스톤 변형, 상호작용 파트너의 가용성에 의해 조절된다. 분화를 분자 수준에서 이해하려면 각 조절 층뿐 아니라 그들 간의 상호작용까지 규명해야 한다.

기존 신경 분화 연구 대부분은 한두 개 조절 층만 프로파일링했고, 단백질-염색질 결합(ChIP-seq)은 대개 제한된 수의 인자에 대해서만 측정되어 TF 활성을 조절하는 상호작용 파트너를 놓쳤다. 다능성 TF(OCT4, SOX2, NANOG)의 interactome이 규명되었으나 이들이 염색질 상에서 기능적으로 상호작용한다는 직접 증거는 없었다. 본 연구는 마우스 ESC에서 유사분열후(postmitotic) 글루타메이트성 뉴런으로의 분화 전반에 걸쳐 단백질체·전사체·염색질 접근성을 가설 배제(hypothesis-free) 다중 오믹스로 프로파일링하여 조절 재배선(rewiring)의 일반 원리를 SOX2 중심으로 밝힌다.

---

## Key Experiment Methods

1. 마우스 ESC의 유사분열후 글루타메이트성 뉴런 분화(Bibel 프로토콜; day 10에 약 84-88% 뉴런), ESC(day 0), 다능성 이탈(day 2-4, LiF 제거), 신경 전구세포(day 6-8, retinoic acid), 성숙 뉴런(day 10-12) 시점 채취.
2. 여러 시점에서 ATAC-seq(염색질 접근성), RNA-seq(전사체), TMT-표지 LC-MS 단백질체 분석; 오염 세포 마커 부재로 뉴런 순도 검증.
3. Multi-Omics Factor Analysis(MOFA)로 잠재 인자(latent factor) 추론; RNA/단백질 log2 fold change의 k-means 군집화; Fisher 정확검정으로 층간·시점간 연관 분석.
4. diffTF로 결합 부위 염색질 접근성 총합 변화로부터 차등 TF 활성 추정; TF footprinting.
5. day 0과 day 10의 SOX2 ChIP-seq(공개 ESC 데이터셋과 결합); 공개 히스톤 표지(H3K4me1/3, H3K27ac, H3K36me3, H3K27me3, H3K9me3)와 통합하여 SOX2 결합 조절 그룹 분류; 차등 결합 및 motif 분석.
6. SOX2 ChIP-SICAP(염색질 결합 단백질 선택적 분리) 및 ChIP-MS로 ESC 대 뉴런의 염색질 결합 SOX2 interactome 규명.
7. 공개 ChIP-seq(ChIP-Atlas) 통합 co-occupancy 분석; 3개 게놈 loci에서 SOX2/ATRX 기능의 CRISPR 검증.

---

## Results

- MOFA는 3개 잠재 인자를 식별했다: LF1(세 층 공통)은 초기 대 후기 분화를 분리, LF2는 RNA 변화(전구세포→뉴런, 시냅스/활동전위/세포주기), LF3은 초기 ATAC 변화를 포착.
- ATAC peak(111,200/117,852)과 유전자(15,645/18,877) 대부분이 최소 한 비교에서 차등이었으나, 차등 발현 단백질은 440개(<10%)에 불과했다. RNA와 단백질은 협응적 동역학을 보인 반면, 프로모터 접근성은 발현과 대체로 무상관이었고(많은 프로모터가 유전자 유도 훨씬 이전에 접근 가능), 유전자내/enhancer 요소는 매우 동적이었다.
- 시점간 연관: 염색질 변화는 초기에, 전사체/단백질체 변화는 최종 전구세포→뉴런 단계로 갈수록 증가했다. day 4의 접근성은 day 8의 RNA와 연결되었고, 다능성 이탈/신경 유도 시 확립된 RNA 패턴이 다음 단계의 단백질 발현과 연결되었다.
- diffTF는 활성이 유의하게 변하는 TF 296개를 찾았다. "신경 TF" 그룹(예: SOX5, EBF1)은 증가하고 "다능성 TF" 그룹(예: MYC, NRF1)은 감소했다. 알려진 억제자 Zeb1과 Msx1은 활성과 발현의 역상관을 보였다.
- SOX2는 주목할 예외였다: motif가 신경 클러스터 프로모터에 농축되었으나 diffTF 활성과 RNA는 분화 중 감소했다(NANOG/OCT4와의 다능성 역할과 일치). 다능성 이탈 시 사라진 OCT4와 달리 SOX2 단백질은 유사분열후 뉴런에서도 높게 유지되었다.
- SOX2는 ESC enhancer에서 신경 프로모터로 재배치되었다: SOX2 peak 14,362개 중 ESC 특이 peak은 OCT4:SOX2 motif와 원거리/인트론 요소에 농축, 신경 특이 peak은 HOX 및 ARID3B motif에 농축되어 프로모터에 위치하고 "뉴런 운명 결정"/"전뇌 발생" 유전자 근처에 있었다. SOX2는 ESC에서 이미 접근 가능한 영역에만 결합하여 뉴런에서 pioneer factor가 아님을 나타냈다.
- ChIP-SICAP은 염색질 결합 SOX2 상호작용 단백질 92개(ESC)와 105개(뉴런)(57개 공유)를 식별했고, TF·coTF·후성유전 remodeler에 농축되었다. OCT4/SALL4/RIF1은 ESC 특이, 신경 상호작용자는 FABP7, TOP2B, CTBP2를 포함했다. 줄기세포→신경 인자 전환이 관찰되었고(예: TRIM28 ESC 선호; ADNP, MYEF2 뉴런 선호), 결합 변화는 대체로 단백질 발현을 반영했다(R=0.7).
- Co-occupancy 분석: 대부분의 ESC SOX2 peak이 다른 TF와 공동 결합(OCT4 98%, KDM1A 79%, SMAD2 68%, SALL4 59% 등)했다. 뉴런에서는 ATRX(49%)와 KDM1A(46%)만 실질적으로 겹쳤고, ChIP-SICAP 기준 염색질 상에서 SOX2와 상호작용하는 것은 ATRX뿐이어서 ATRX가 뉴런에서 주요 직접 염색질 결합 SOX2 상호작용자였다. SOX2-ATRX 공동 결합은 활성 enhancer 표지 증가 및 인근 유전자 발현 증가와 상관했고 3개 loci에서 CRISPR로 검증되었다.

---

## Perspective

본 연구는 통합 다중 오믹스(전사체·단백질체·염색질 접근성)가 신경 분화 중 유전자 조절을 해부하는 데 유용함을 보이며, 다능성 인자 SOX2가 게놈적으로 "재배선"됨을 밝혔다. 즉 OCT4 공동 결합 ESC enhancer에서 신경 프로모터로 재배치되며, 이는 그 염색질 결합 단백질 interactome이 다능성 인자에서 염색질 remodeler ATRX로 전환됨에 의해 유도된다. 뉴런에서 SOX2가 미리 접근 가능한 영역에만 결합(비-pioneer)하고 SOX2-ATRX 공동 결합이 신경 유전자를 활성화한다는 발견은 단일 TF가 세포 상태 특이적인 상반된 기능을 획득하는 기전을 제공한다.

본 지식베이스와의 연관성은 신경 분화 패러다임과 SOX2의 신경발생 역할(농축 GO 항목 중 전뇌·등쪽 척수 발생 포함)에 있다. 한계로는 단백질체로 정량된 TF 수가 적어(352개 중 43개, diffTF 추론 필요) co-occupancy가 공개 ChIP-seq에 의존(상호작용자 일부만 데이터 가용)한다는 점, 기능 검증이 3개 CRISPR loci에 국한된다는 점, 생체 척수/뇌 조직이 아닌 in vitro 글루타메이트성 뉴런 모델을 사용했다는 점이 있다. 상호작용자 게놈 위치의 광범위한 매핑과 생체 검증이 향후 방향이다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
