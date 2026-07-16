---
tags: [2026-07]
extract: 2026-07-16
---

# Mapping microglia states in the human brain through the integration of high-dimensional techniques

## Citation (NLM)
Sankowski R, Böttcher C, Masuda T, Geirsdottir L, Sagar, Sindram E, Seredenina T, Muhs A, Scheiwe C, Shah MJ, Heiland DH, Schnell O, Grün D, Priller J, Prinz M. Mapping microglia states in the human brain through the integration of high-dimensional techniques. Nat Neurosci. 2019;22(12):2098-2110. doi:10.1038/s41593-019-0532-y

**DOI:** [https://doi.org/10.1038/s41593-019-0532-y](https://doi.org/10.1038/s41593-019-0532-y)

---

## Background

미세아교세포(microglia)는 중추신경계(CNS)의 조직 상주 대식세포로서, 국소 면역반응을 조율하고 다양한 신경학적·정신의학적 질환에 관여한다. 건강한 뇌에서는 미세환경 감시, 시냅스 가소성 조절, 사멸 세포 제거 등의 기능을 수행하며, 질병 상태에서는 면역 기능을 담당한다. 신경퇴행성·신경염증 질환의 전장유전체연관연구(GWAS)에서 다수의 위험 관련 단일염기다형성(SNP)이 미세아교세포와 연관되어, CNS 질환에서 선천면역세포의 중요성이 부각되고 있다.

그럼에도 인간 미세아교세포에 대한 지식은 부족했고, in vivo에서 특화된 미세아교세포 아집단의 존재에 대한 증거도 드물었다. 인간 뇌 미세아교세포 상태의 단일세포 구성—영역별·기능별 이질성—은 건강한 인간 뇌 조직 확보의 어려움과 다수 세포를 풀링해야 하는 기존 방법의 한계 때문에 규명되지 못한 상태였다. 본 연구는 단일세포 RNA 시퀀싱(scRNA-seq)과 비행시간 질량세포측정법(CyTOF)을 결합하여, 항상성 및 질병 상태에서 인간 뇌의 미세아교세포 상태를 정의한다.

---

## Key Experiment Methods

1. **인간 미세아교세포 scRNA-seq**: 뇌전증(n=10), 악성 신경교종(n=4), 전이(n=1) 수술을 받은 성인 15명의 대조 뇌 영역에서 FACS로 분리한 CD45+DAPI− 세포 4,564개 중 4,396개 미세아교세포를 3′-말단 기반 mCEL-Seq2 프로토콜로 프로파일링.
2. **RaceID3 클러스터링**: 희귀 집단 검출에 적합한 비지도 클러스터링으로 9개 주요 클러스터(C1–C9) 도출.
3. **신경망 분류기**: 전체 세포의 70%로 학습하여 공개된 독립 데이터셋(Masuda, Velmeshev, Schirmer, Jäkel, Mathys)의 미세아교세포를 정의된 클러스터에 배정, 교차 검증.
4. **유전자 온톨로지(GO) 농축 분석**(clusterProfiler): 클러스터별 차등발현유전자로 기능적 상태 추론.
5. **영역·연령 비교**: 측두엽 회백질 vs. 백질(15명 중 11명), 연령대 3구간(<30, 30–50, >50세) 비교.
6. **단백질 수준 검증**: 면역조직화학(IBA1, P2RY12, TMEM119, HLA-DR, CD68, CD74, SPP1) 및 CyTOF.
7. **신경교종 분석**: IDH 야생형 원발성 교모세포종(GBM) 4례 대 연령 대응 대조군 4례의 미세아교세포 scRNA-seq, StemID2 및 Monocle 유사시간(pseudotime) 분석, CyTOF 검증.

---

## Results

- 인간 미세아교세포는 뚜렷이 구분되는 세포 유형이라기보다 연속적인 전사 상태 스펙트럼을 이룬다. 모든 클러스터가 단핵구·희소돌기아교세포와 명확히 구별되는 하나의 확산된 "미세아교세포 구름"을 형성했다.
- 항상성 클러스터 C2, C3(핵심 signature 유전자 CX3CR1, TMEM119, CSF1R, P2RY12, P2RY13, SELPLG, MARCKS)는 15명 모두에서 기여했으며, C2는 추가로 높은 MHC-II 및 항바이러스 유전자(HLA-DRA, CD74, IFI44L)를 발현했다.
- C6/C7 클러스터는 낮은 CX3CR1과 높은 대사·인테그린 유전자(SPP1, APOE, LPL)를 보였고, 소규모 클러스터 C1, C5, C8, C9는 케모카인/사이토카인 유전자(CCL2, IL1B, CD83)를 발현했다.
- 분류기는 독립 데이터셋 전반에서 클러스터 배정을 재현하여, 전염증성 클러스터의 in vivo 관련성을 확인했다.
- **영역별 이질성**: 백질 미세아교세포는 MHC-II 고발현 클러스터(C2, C5–C7)에 농축되고 HLA-DR, CD68, APOE, EMR1이 더 높았으며, 회백질 미세아교세포는 MHC-II 저발현 클러스터(C3, C8)에 농축되었다. IHC와 CyTOF로 확인.
- **연령 의존성**: SPP1(osteopontin) 고발현 클러스터 C6/C7는 50세 초과 대상에서 농축되었고, SPP1+IBA1+ 세포는 연령 증가 및 백질에서 증가했다.
- **신경교종 관련 미세아교세포(GAM)**: 핵심 유전자(CX3CR1, SELPLG) 하향조절과 염증·대사·저산소 유전자(CD163, APOE, LPL, IFI27, IFITM3, HIF1A, VEGFA) 상향조절의 질환 관련 signature를 획득했다. 유사시간 분석(StemID2, Monocle)은 항상성 → 노화 관련 → GAM으로 이어지는 궤적을 제시했고, CyTOF로 고유한 신경교종 관련 클러스터가 확인되었으며 GAM은 노화 관련 미세아교세포와 전사적으로 유사했다.

---

## Perspective

본 연구는 두 가지 직교적 고차원 기법(scRNA-seq와 CyTOF)을 in situ 검증과 통합함으로써, 건강한 뇌와 질병 뇌의 인간 미세아교세포에 대한 단일세포 해상도 지도를 최초로 제공한 연구 중 하나다. 인간 미세아교세포가 공간적·연령적으로 형성된 전사 연속체를 따라 존재하며, 신경교종이 미세아교세포를 노화 관련 염증/대사 상태로 재편함을 확립했다. 이는 미세아교세포 아집단 특이적 치료 개발을 위한 자원이 된다.

한계로는 대상자 수가 적고, 수술 환자의 "대조" 접근 조직에 의존(진정한 건강 뇌와 동일하지 않을 수 있음)하며, 일부 비교 데이터셋의 세포 수가 적고, 외부 검증 세트에서 분류기 정확도가 낮아진다는 점(프로토콜 차이 mCEL-Seq2 vs. nuc-seq, 환자 연령 차이 반영)이 있다. 향후 더 큰 코호트, 추가 뇌 영역, 정의된 상태의 기능적 특성화가 필요하다. CNS 손상·재생 연구 관점에서는, 영역·질환별로 정의된 미세아교세포 상태의 틀이 CNS 내 glia 반응을 이해하는 데 직접적으로 관련된다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
