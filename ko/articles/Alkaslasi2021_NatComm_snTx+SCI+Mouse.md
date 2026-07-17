---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
---

# Single nucleus RNA-sequencing defines unexpected diversity of cholinergic neuron types in the adult mouse spinal cord

## Citation (NLM)
Alkaslasi MR, Piccus ZE, Hareendran S, Silberberg H, Chen L, Zhang Y, Petros TJ, Le Pichon CE. Single nucleus RNA-sequencing defines unexpected diversity of cholinergic neuron types in the adult mouse spinal cord. Nat Commun. 2021;12(1):2471. doi:10.1038/s41467-021-22691-2

**DOI:** [https://doi.org/10.1038/s41467-021-22691-2](https://doi.org/10.1038/s41467-021-22691-2)

---

## Background

척추동물의 운동 제어는 척수의 콜린성 뉴런에 의존하며, 이는 크게 세 종류로 나뉜다: 골격근 운동뉴런(MN), 내장(신경절전 자율) 운동뉴런, 콜린성 개재뉴런. 100년 넘게 연구되었음에도 이들 뉴런의 완전한 이질성과 성체에서의 구별되는 기능적 역할은 규명되지 않았다. 아형 정의는 임상적으로 중요한데, 척수성 근위축증과 ALS 같은 운동뉴런 질환이 특정 MN 아형을 선택적으로 침범하기 때문이다(예: 빠르게 발화하는 알파 MN이 먼저 변성되는 반면 감마 MN과 느린 알파 MN은 상대적으로 저항성).

콜린성 뉴런은 전체 척수 세포 중 드물고 운동뉴런의 큰 크기로 인해 기존 단일세포 접근법으로는 잘 포획되지 못했다. 저자들은 표적화된 단일핵 RNA 시퀀싱(snRNAseq) 전략을 개발하여 성체 마우스 척수 콜린성 뉴런을 농축·포괄적으로 분류하고 전사체 아틀라스를 구축하였다(www.spinalcordatlas.org).

---

## Key Experiment Methods

1. **유전적 표지 및 핵 농축**: Chat-IRES-Cre::CAG-Sun1-sfGFP 마우스로 콜린성 핵을 핵막 부착형 GFP로 영구 표지.
2. **부위별 절개**: 척수를 경추, 흉추, 요천추 부위로 분리하여 개별 처리하고 차등 바코딩으로 문미-미측 축을 따라 세포 유형 매핑.
3. **핵 분리 및 FACS**: 밀도 구배 원심분리 후 GFP+/DRAQ5+ 단일 핵을 형광활성 세포분류.
4. **snRNAseq**: 10X Genomics Chromium 플랫폼, Illumina HiSeq 시퀀싱; 34,231개 핵 특성화 후 16,042개 Chat 발현 콜린성 핵으로 필터링.
5. **클러스터링 및 마커 분석**: 전사체 클러스터와 최상위 마커 식별; 골격근 MN, 알파 MN, 개재뉴런, 내장 MN의 하위 클러스터링.
6. **검증**: 다중 형광 in situ 혼성화(RNAScope/ISH), 면역염색(SV2B 단백질), C-bouton/VGLUT1 해부학적 기준, 특정 근육으로부터의 역행성 추적(FastBlue).

---

## Results

- 오염된 비콜린성 클러스터 22개(누출성/발생성 Cre) 제거 후 16,042개 Chat+ 핵이 **21개의 전사적으로 구별되는 아형**으로 분해됨—기존에 알려진 것보다 훨씬 큰 다양성. 성별 특이적 차이는 관찰되지 않음.
- **세 주요 부류**가 마커와 위치로 배정됨: 콜린성 개재뉴런(Pax2; I1–I8), 내장 MN(Zeb2; V1–V10), 골격근 MN(S1–S3). **Tns1**이 골격근 MN 선택적 마커로 부상(복측각, Chat 및 Prph와 공발현); **Fbn2**가 내장 MN 일반 마커(Zeb2 음성 클러스터 V8 포함); **Slc6a1**은 개재뉴런 집합 표지.
- **골격근 MN**: S2(Rbfox3+) = 알파, S3(Esrrg/Gfra1+) = 감마, 알파·감마 마커를 모두 발현하는 S1 = 베타 가능성("Type 3") MN. 신규 특이 마커: Sv2b, Stk32a, Glis3(알파), Nrp2(감마), Gpr149(Type 3). Sv2b/Stk32a는 Rbfox3보다 제한적이고 특이적이며 SV2B는 단백질 수준에서 검증됨.
- **알파 MN 아형**: 재클러스터링 시 부위별 패턴을 갖는 8개 아형. Cpne4는 손가락 지배 MN, Erbb4는 횡격막(phrenic) MN, Grm5는 가자미근 투사 MN에 상대적으로 농축—전사체 정체성과 근육 표적을 연결.
- **콜린성 개재뉴런**: 8개 클러스터. Pitx2+ partition cell은 I5(Tox+)와 I6(Tox−)로 분리. 드문 클러스터 I8은 중심관 근처에서 Piezo2와 Reln을 공발현—기계감각 채널 Piezo2가 중추 콜린성 개재뉴런에서 발현되는 놀라운 소견.
- **내장 MN**: 전사인자, 신경펩티드(Ccbe1, Sst, Penk), ECM 단백질로 구별되는 16개 하위 클러스터. 놀랍게도 내장 MN이 흉추·요천추뿐 아니라 미측 경추 부위(통상 없다고 여겨짐)에도 풍부. 클러스터 분포는 매우 부위 특이적(예: C/T의 Dach2/Gpc3/Sema5a; L/S 천추의 방광/장 조절 신경절전 뉴런 Sst; 경추에만 있는 Bnc2)이어서 장기 제어를 위한 해부학적-전사체적 특화를 시사.

---

## Perspective

본 연구는 성체 마우스 척수 콜린성 뉴런의 포괄적 전사체 아틀라스를 제공하여 세 부류 전반의 예상치 못한 다양성을 밝히고, 더 선택적인 신규 마커(골격근 MN의 Tns1; 알파 MN의 Sv2b/Stk32a; 내장 MN의 Fbn2)를 제시한다. ALS에서 상실이 궁극적으로 치명적인 횡격막 지배(phrenic) 알파 MN 아형의 마커를 규명함으로써, 퇴행성 질환에서의 MN 차등 취약성 연구와 운동뉴런 하위집단 선택적 표적화 도구를 제공한다.

한계: 아형 배정(특히 알파/베타/감마)은 마커 발현과 해부학에 근거하며, 추정 베타("Type 3") MN의 확정적 규명에는 전기생리학이 필요하나 수행되지 않았다. 일부 배아기 마커는 성체에서 유지되지 않았다. 향후 방향은 발화 특성과 전사체 아형의 전기생리학적 상관, 중추 콜린성 뉴런에서 Piezo2의 기능 연구, 운동뉴런 질환의 세포유형 취약성 규명을 위한 아틀라스 활용을 포함한다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
