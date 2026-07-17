---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
---

# Mapping the Global Chromatin Connectivity Network for Sox2 Function in Neural Stem Cell Maintenance

## Citation (NLM)
Bertolini JA, Favaro R, Zhu Y, Pagin M, Ngan CY, Wong CH, et al. Mapping the Global Chromatin Connectivity Network for Sox2 Function in Neural Stem Cell Maintenance. Cell Stem Cell. 2019;24(3):462-476. doi:10.1016/j.stem.2019.02.004

**DOI:** [https://doi.org/10.1016/j.stem.2019.02.004](https://doi.org/10.1016/j.stem.2019.02.004)

---

## Background

SOX2 전사인자는 신경줄기세포(NSC) 유지와 뇌 발생에 필수적이다. 사람에서 SOX2 돌연변이는 우성 신경계 질환(해마·눈 결함, 뇌전증, 학습장애)을 일으키고, 마우스에서 Sox2 결실은 해마 형성저하와 소두증을 포함한 유사 결함을 야기하며 일부는 NSC 자가재생 결함에서 기인한다. Sox2 결실 NSC는 장기 배양에서 자가재생에 실패한다.

전사 조절은 프로모터와 원위 인핸서 사이의 DNA 루핑을 통해 매개되며, 세포 유형 특이적 3차원 네트워크("connectome")를 형성한다. 단일 전사인자가 세포 특이적 전사를 제어하는 유전체 전역 상호작용 네트워크의 기능에 어느 정도 영향을 미치는지는 알려지지 않았다. 이 연구는 SOX2가 NSC에서 Pol II 매개 장거리 염색질 상호작용 네트워크를 어떻게 형성하는지, 그리고 어떤 하류 유전자가 Sox2 의존적 장기 자가재생을 매개하는지를 규명한다.

---

## Key Experiment Methods

1. **NSC 모델**: 조건부(E11.5) Sox2 결실 마우스(MUT)와 대조(WT) 동배의 신생아(P0) 전뇌 유래 뇌 NSC 배양.
2. **ChIA-PET**(paired-end tag 시퀀싱을 이용한 염색질 상호작용 분석): 항-Pol II 항체로 WT 대 MUT NSC의 유전체 전역 장거리 염색질 상호작용을 매핑. 원래 프로토콜(TR1)에 더해 분자 내 결찰 효율이 높은 개선된 *in situ* ChIA-PET(TR2, TR3)를 개별 전뇌에 적용.
3. **ChIP-seq**: SOX2(WT NSC), 히스톤 변형 H3K27ac·H3K4me1(WT·MUT)에 대해 수행하여 활성·대기(poised) 인핸서를 정의(peak-calling과 chromHMM 분절화).
4. **RNA-seq**: WT·MUT NSC 전사체를 분석하여 상호작용과 유전자 발현을 연관.
5. **제브라피시 형질전환 인핸서 분석**: SOX2 결합 원위 anchor를 최소 프로모터 + GFP 상류에 클로닝하여 전뇌 리포터 활성 및 항-Sox2 morpholino / Sox2 mRNA에 의한 조절을 검정.
6. **기능 구제**: MUT NSC에 Socs3(SOX2 표적, Jak/Stat 억제자)를 렌티바이러스로 과발현하고, 성장 곡선과 GFP+ 세포의 FACS 추적.

---

## Results

- Sox2 결실은 Pol II 매개 장거리 염색질 상호작용을 유전체 전역에서 상당히 감소시켰다(정규화된 유의 루프가 WT 약 6-10K에서 MUT 약 2-3K로 감소). 반면 Pol II 결합 영역은 대부분 유지되었다(92%). 변화는 불균일하여 일부 유전자좌에서는 급격히 감소하고 다른 곳에서는 거의 변화가 없었으며, 때로 MUT 세포에서 새로운 루프가 나타났다.
- SOX2 결합 부위는 프로모터에는 드물고 대부분 원위 인트론/유전자간 영역에 있었으며, 90% 이상이 활성 인핸서 표지(주로 H3K27ac+)를 지녔다. SOX2 결합·후성유전 표지 원위 영역은 무작위 유전자좌 및 비-SOX2 결합 표지 영역에 비해 상호작용 anchor에 크게 농축되었다.
- WT NSC 전체 상호작용의 약 35-46%가 anchor에 SOX2 결합 부위를 지녔으며, SOX2는 특히 프로모터-인핸서(P-E) 상호작용의 원위 인핸서 anchor에 농축되었다.
- SOX2 의존적 상호작용 anchor는 신규 전뇌 인핸서를 예측했다: 검정한 원위 anchor 17개 중 15개가 발생 중 제브라피시 전뇌로 GFP를 유도했고 내인성 오솔로그 발현과 일치했으며, 일부는 VISTA 인핸서와 겹쳤다(MUT 세포에서는 anchor 겹침이 급감).
- P-E 상호작용, 특히 SOX2 결합 인핸서와의 상호작용에 참여한 유전자는 발현이 높았다. Sox2 소실은 약 1,000개 유전자의 발현을 감소시켰다. MUT에서 유의하게 발현이 감소한 유전자(group 1)는 프로모터-SOX2 결합 인핸서 상호작용과 특이적으로 강하게 공동연관된 반면, 프로모터에서의 SOX2 결합과 P-P 상호작용은 기능적 관련성이 훨씬 낮았다.
- **Socs3** 과발현 — MUT NSC에서 강하게 하향조절된 다중연결 SOX2 표적 — 이 장기 자가재생 결함을 구제했다: Socs3 형질도입 MUT NSC는 장기간 성장을 지속(점진적으로 약 100% GFP+로 농축)한 반면, 비형질도입 MUT NSC는 8-12 계대에서 고갈되었다.
- Sox2 소실은 후성유전 인핸서 표지(H3K27ac/H3K4me1)를 실질적으로 변화시키지 않아, SOX2가 이 표지의 확립/유지보다는 상호작용/전사에 작용함을 시사한다(Sox2는 표지가 이미 설정되었을 수 있는 E11.5에 결실됨).

---

## Perspective

이 연구는 SOX2가 NSC에서 Pol II 매개 프로모터-인핸서 장거리 상호작용에 농축되고 이를 유지함으로써 유전자 발현의 주요 조절자임을 확립하며, 이는 상호작용을 재편하면서도 전사 효과는 중간 정도인 구조 단백질(CTCF/Cohesin)과 대조된다. 이 연결성 네트워크를 정의함으로써 NSC 유지 및 신경발생 장애와 관련된 인핸서·유전자를 규명하는 경로를 제공한다(여러 원위 anchor가 사람 뇌질환 유전자와 연결됨). SOCS3가 자가재생 구제에 충분함을 기능적으로 규명한 것은 핵심 하류 효과자를 특정한다.

한계와 미해결 질문으로는: 시퀀싱 깊이에 의존하기 때문에 특정 상호작용의 완전한 소실(대 빈도 감소)을 증명하기 어렵다는 점; 상호작용 소실이 anchor에서의 SOX2 제거에서 직접 기인하는지 아니면 SOX2 제어 전사인자의 탈조절을 통해 간접적으로 기인하는지; 상호작용을 매개하는 SOX2 파트너 복합체(NurD, SWI/SNF, CHD7, SMRT/NCOR)와 YY1과의 관계; 그리고 SOX2 없이도 인핸서 표지가 지속되어 상호작용 안정화 기전이 미해결로 남는다는 점이 있다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
