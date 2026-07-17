---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p05.txt
---

# 방사아교세포 후손의 단일세포 시퀀싱이 성체 제브라피시 뇌에서 신생 신경세포의 다양성을 밝히다 (Single cell sequencing of radial glia progeny reveals the diversity of newborn neurons in the adult zebrafish brain)

## Citation (NLM)
Lange C, Rost F, Machate A, Reinhardt S, Lesche M, Weber A, Kuscha V, Dahl A, Rulands S, Brand M. Single cell sequencing of radial glia progeny reveals the diversity of newborn neurons in the adult zebrafish brain. Development. 2020;147(1):dev185595. doi:10.1242/dev.185595

**DOI:** [https://doi.org/10.1242/dev.185595](https://doi.org/10.1242/dev.185595)

---

## Background
제브라피시는 광범위하고 뚜렷한 성체 신경발생을 나타내며, 이는 손상 후 중추신경계를 재생하는 능력의 기반이 된다. 성체 신경발생이 해마 과립하대(subgranular zone)와 측뇌실의 상의하대(sub-ependymal zone)에 국한된 포유류와 달리, 경골어류는 신경축(neuraxis) 전반에 걸쳐 새로운 신경세포를 생성한다. 성체 제브라피시 종뇌에서 방사아교세포(RG) 신경 줄기세포는 뇌실대(ventricular zone)에 존재하며 인접한 실질(parenchyma)로 통합되는 신경세포를 생성한다. 종뇌 손상 후 효율적인 복구는 RG 증식, 신경세포 생성, 신생 신경세포(NBN) 통합을 통해 진행된다.

그럼에도 불구하고 성체 신생 신경세포의 세포 정체성과 생물학적 특성은 대부분의 뇌 영역에서 밝혀지지 않았으며, 기존 연구는 주로 신경세포로 분화가 결정된 후손보다 RG에 초점을 맞추었다. 본 연구는 항상성 상태의 성체 제브라피시 전뇌(forebrain)에서 RG, RG 유래 NBN, 성숙 신경세포(MN)를 전향적으로 분리하고 전사체적으로 특성화하여 신생 신경세포의 다양성과 분화 궤적을 이해하고자 했다.

---

## Key Experiment Methods
1. 이중 형질전환 리포터 어류를 이용한 단기 계통 추적: RG 리포터 her4.1:mcherry(또는 새로 생성한 gfap:nls-mcherry 계통)를 신경세포 리포터 elavl3:gfp와 결합. NBN은 RG 전구체로부터 안정한 mCherry 단백질을 물려받는 mCherry-low/GFP-양성 세포로 식별된다.
2. 분리된 전뇌에서 RG(mCherry-high/GFP-음성), NBN(mCherry-low/GFP-양성), MN(mCherry-음성/GFP-양성)을 정량화·분리하기 위한 유세포 분석(FACS) 및 Image Stream 이미징 유세포 분석.
3. 성체 생성 신경세포의 농축과 그 일과성 동역학을 검증하기 위한 EdU 펄스체이스 표지(12시간 간격 주입; 2시간, 7일, 4주에 분석).
4. 분류된 RG, NBN, MN 세포(QC 통과 264개 세포)의 단일세포 RNA 시퀀싱(SMARTSeq2), 이후 Louvain 클러스터링, t-SNE, PCA.
5. 분화 궤적을 재구성하기 위한 확산 지도(diffusion-map)/확산 유사시간(diffusion pseudotime) 분석.
6. 제브라피시와 마우스 전사체를 공유 오솔로그(orthologue) 쌍으로 변환하고 성체/발생 중 마우스 해마 데이터(Hochgerner et al., 2018)에 대해 계층적 클러스터링하는 종간 세포 유형 상동성 분석.
7. 클러스터 특이 마커(tubb5, ebf3a, msi2b, tbr1b)에 대한 in situ hybridization과 전뇌에서 NBN 집단을 국재화하기 위한 EdU/HuC-D 공표지.

---

## Results
- RG 유래 NBN은 물려받은 형광 단백질을 통해 전향적으로 분리할 수 있다; NBN은 살아있는 전뇌 세포의 ~10.9%를 차지하며, 진정한 RG(8.7%)와 수적으로 비슷하고, MN이 지배적이다(72.1%).
- EdU 펄스체이스는 NBN이 성체 생성 신경세포로 농축되어 있으며, 최소 7일 동안(그러나 4주 이하로) her4.1:mCherry를 일과성으로 보유함을 확인했다.
- 단일세포 시퀀싱은 5개의 클러스터를 식별했다: RG, 두 개의 순수 신생 신경세포 클러스터(NBN.1, NBN.2), 혼합 NBN/MN 클러스터, 그리고 희소돌기아교전구세포(OPC) 클러스터 — RG가 신경세포 및 희소돌기아교 후손을 모두 생성함을 나타낸다.
- 각 클러스터는 구별되는 마커를 지녔다(예: RG: fabp7a, her4.1, glula; NBN.1: tubb5, cd99l2, cnp; NBN.2: ebf3a, tbr1b, msi2b; OPC: olig2, aplnra).
- 유사시간 순서화는 NBN.1을 RG와 가장 밀접하게 관련된 상태로 배치했으며, MN 클러스터 또는 NBN.2 클러스터로 각각 이어지는 분기점을 나타냈다.
- 종간 상동성 분석은 제브라피시 RG가 마우스 상의세포/어린 성상세포/RGL-NSC와, NBN.1이 미성숙 과립세포 및 추체 신경세포와, NBN.2/MN이 성숙 신경세포와 함께 클러스터링됨을 보여주었다 — 포유류 해마와 신경발생 세포 유형의 보존을 입증한다.
- 증식(ccnd1, mki67, mcm5)은 RG 클러스터에 국한되었다; 증식 중인 RG는 신경발생 운명 결정인자(ascl1a, sox4a)와 NBN.1 마커(tmsb, stmn1b)로 농축되어, 증식 중인 RG 대부분이 신경발생으로 결정되어 있음을 나타낸다.
- 공간 분석: tubb5+ NBN.1 세포는 종뇌의 뇌실/뇌실주위 대(glutamatergic 투사 신경세포 정체성)에 국재하는 반면, ebf3a/msi2b/tbr1b+ NBN.2 세포는 간뇌의 복측 각내핵(entopeduncular nucleus, vENT)에 국재한다 — EdU/HuC-D 공표지로 확인된 이전에 보고되지 않은 성체 신경발생 부위이다.

---

## Perspective
본 연구는 제브라피시 전뇌에서 성체 신생 신경세포를 최초로 전향적으로 분리하고 단일세포 전사체적으로 특성화하여, 새로운 마커를 확립하고 RG 후손 간의 내재적 이질성을 밝힌다. 제브라피시와 포유류의 성체 신경발생 세포 유형 간에 입증된 상동성은, 손상이나 신경퇴행 후 포유류 뇌 복구의 핵심 장애물인 신경세포 생성과 통합을 이해하기 위한 모델로서 제브라피시를 뒷받침한다. 성체 종뇌에서 glutamatergic 투사 신경세포가 생성되며, 별개의 NBN 집단이 간뇌 vENT에 추가된다는 발견은 성체 신경발생의 지도를 확장한다.

한계로는 시퀀싱된 세포 수가 비교적 적다는 점(QC 통과 264개, 특히 MN이 적음), 클론 추적이 아닌 단기 집단 수준 계통 추적에 대한 의존, 항상성(비손상) 전뇌에 국한된 분석 — 따라서 이 NBN 집단들이 재생 중 어떻게 행동하는지는 아직 검증되지 않았다 — 이 있다. 놀랍게도 큰 NBN 집단의 생물학적 역할과 그 통합 기전은 여전히 알려지지 않았다. 향후 방향으로는 이 프레임워크를 손상/재생 중인 뇌에 적용하고 식별된 마커를 조작하여 NBN 기능을 탐구하는 것이 포함된다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
