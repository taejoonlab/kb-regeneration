---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
---

# A CRISPRi/a platform in human iPSC-derived microglia uncovers regulators of disease states

## Citation (NLM)
Dräger NM, Sattler SM, Huang CT, Teter OM, Leng K, Hashemi SH, Hong J, Aviles G, Clelland CD, Zhan L, Udeochu JC, Kodama L, Singleton AB, Nalls MA, Ichida J, Ward ME, Faghri F, Gan L, Kampmann M. A CRISPRi/a platform in human iPSC-derived microglia uncovers regulators of disease states. Nat Neurosci. 2022;25(9):1149-1162. doi:10.1038/s41593-022-01131-4

**DOI:** [https://doi.org/10.1038/s41593-022-01131-4](https://doi.org/10.1038/s41593-022-01131-4)

---

## Background

미세아교세포(microglia)는 뇌 발달과 항상성의 핵심이며, 알츠하이머병(AD)을 비롯한 신경학적 질환의 주요 유발 요인으로 부상하고 있다. AD에서는 질환 관련 유전 변이가 미세아교세포에서 작용할 가능성이 높다. 질환에서 미세아교세포의 역할을 이해하고 치료적으로 표적화하려면, 질환 관련 유전 변이와 미세아교세포 기능 변화 사이의 간극을 메워야 한다. 그러나 미세아교세포는 건강 및 질병 상태에서 다수의 뚜렷한 기능적 상태를 취하며, 이 상태를 조절하는 분자 기전은 체계적으로 이해되지 않았다.

CRISPR 기반 기능유전체학(pooled CRISPR 간섭 CRISPRi, CRISPR 활성화 CRISPRa)을 iPSC 기술과 결합하면 인간 세포에서 세포 유형 특이적 유전자 스크린이 가능하다. 그러나 성숙한 미세아교세포는 렌티바이러스 형질도입이 어렵고, 대부분의 분화 프로토콜이 길어 집단 병목(bottleneck)이 생겨 sgRNA 라이브러리 대표성이 왜곡되기 때문에, iPSC 유래 미세아교세포에서는 이러한 스크린이 구현되지 못했다. 본 연구는 전사인자 기반의 신속한 미세아교세포 분화 프로토콜과 유도성 CRISPRi/a를 통합하여, 인간 미세아교세포에서 pooled 유전자 스크린을 가능하게 한다.

---

## Key Experiment Methods

1. **iTF-Microglia 생성**: 6개 전사인자(PU.1, MAFB, CEBPα, CEBPβ, IRF5, IRF8)를 doxycycline 유도성으로 발현하도록 AAVS1 및 CLYBL safe-harbor 부위에 통합한 iPSC 주를, GM-CSF, IL-34, M-CSF, TGF-β를 사용하는 8일 3단계 프로토콜로 미세아교세포 유사 세포로 분화.
2. **기능적 특성화**: 형광 비드 및 랫 synaptosome 식균작용(± Cytochalasin D), LPS 자극 후 RNA-seq 및 사이토카인 어레이, iPSC 유래 글루탐산성 뉴런과의 공배양.
3. **유도성 CRISPRi/a**: 항시성 및 유도성(DHFR-degron, TMP 안정화) dCas9-BFP-KRAB(CRISPRi)와 dCas9-VPH(CRISPRa)를 CLYBL에 통합; TFRC 녹다운과 CXCR4 과발현으로 검증.
4. **"Druggable genome" pooled 스크린**(~2,325개 유전자, 유전자당 sgRNA 5개 + NTC 500개): 생존/증식 스크린(0일 vs. 15일), 미세아교세포 활성화 스크린(세포표면 CD38 기반 FACS), CRISPRi/CRISPRa 병렬 식균작용 스크린(pHrodo-synaptosome 흡수 기반 FACS).
5. **CROP-seq 스크린**: 39개 hit 유전자를 표적하는 sgRNA 라이브러리를 8일차 iTF-Microglia 58,302개의 scRNA-seq와 결합하여, 유전자 교란과 전사 상태를 연결.

---

## Results

- 8일 iTF-Microglia 프로토콜은 표준 마커(GPR34, IBA1, P2RY12, CSF1R, CX3CR1, TREM2)를 발현하는 분지형 미세아교세포 유사 세포를 생성했으며, 전사체는 다른 iPSC 유래 미세아교세포 프로토콜과 유사하고 병목 없이 대규모 pooled 스크린에 적합했다.
- iTF-Microglia는 기능적이었다: synaptosome을 식균(액틴 의존적)하고, LPS에 대해 아메보이드 형태와 면역 유전자(C3, CXCL10, IL32, SAA1, NF-κB) 유도 및 사이토카인 분비(IL-6, IL-8, CXCL10)로 반응했으며, iNeuron과 공배양되었다.
- **생존 스크린**: CSF 수용체 계열 유전자(CSF1R, CSF2RB, CSF2RA) 녹다운이 뉴런·iPSC가 아닌 미세아교세포 생존을 강력하고 특이적으로 감소시켰고, CSF1R 필수성은 8일차부터 뚜렷해졌다. 생존에 영향을 주는 유전자는 미세아교세포·뉴런·iPSC 간에 달랐다. CDK8과 TGFBR2 녹다운은 미세아교세포 분화를 교란했다.
- **활성화(CD38) 스크린**: 전사 조절인자 CDK12와 MED1, 그리고 미토콘드리아 Complex I 서브유닛(NDUFA8, NDUFS5) 녹다운이 CD38 표면 수준을 증가시켰다.
- **식균작용 스크린**: CRISPRi와 CRISPRa hit 간 중첩이 거의 없었다. PFN1(ALS 유전자)은 상반된 효과를 보였고, CSF1R 및 INPP5D 녹다운은 식균작용을 증가시켰으며, CD209 과발현은 기질 특이성을 보이며 synaptosome 식균작용을 크게 증가시켰다. PFN1 과발현은 F-actin을 증가시키고 면역/AD 위험 유전자 발현을 변화시켰다.
- **CROP-seq**: iTF-Microglia는 인간 뇌에서 관찰되는 상태들을 반영하는 전사 상태 스펙트럼을 취했으며, 스크린은 특정 상태의 조절인자를 규명했다. osteopontin(SPP1) 발현으로 특징지어지는 질환 관련 상태가 CSF1R 억제에 의해 선택적으로 고갈되었다.

---

## Perspective

본 연구는 이 세포 유형에서 CRISPR 스크리닝의 기존 장벽을 극복한, 확장 가능하고 신속하며 유전적으로 조작 가능한 인간 iPSC-미세아교세포 플랫폼을 확립했다. pooled 손실·획득 기능 스크린을 단일세포 판독과 결합함으로써, 유전자 교란을 미세아교세포 생존·활성화·식균작용 및 무엇보다 개별 질환 관련 전사 상태에 체계적으로 연결했다. 특히 CSF1R 억제로 고갈되는 SPP1+ 상태를 규명하여, 약물 표적 가능 표적을 특정 미세아교세포 상태와 연결했다.

한계로는 불완전한 유도성 CRISPRi 시스템(예: PICALM은 항시성 시스템으로는 녹다운되나 유도성으로는 되지 않음), 일차 인간 미세아교세포와 여전히 구별되는 전사체(iPSC 유래 미세아교세포의 일반적 한계), 개체발생(ontogeny)이 아닌 전사인자 강제 분화에 의존한다는 점이 있다. 이 플랫폼은 미세아교세포 상태의 기능적 특성화와 치료적 표적화를 위한 자원을 제공하며, CNS 손상과 신경퇴행 전반에서 미세아교세포가 공유하는 역할을 고려할 때 CNS 복구·재생 연구와도 관련된다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
