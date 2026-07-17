---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p07.txt
raw_data:
  - "GEO: GSE164945"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Localized EMT reprograms glial progenitors to promote spinal cord repair (국소적 EMT가 아교 전구세포를 재프로그래밍하여 척수 재생을 촉진한다)

## Citation (NLM)
Klatt Shaw D, Muraleedharan Saraswathy V, Zhou L, McAdow AR, Burris B, Butka E, Morris SA, Dietmann S, Mokalled MH. Localized EMT reprograms glial progenitors to promote spinal cord repair. Dev Cell. 2021;56(5):613-626. doi:10.1016/j.devcel.2021.01.017

**DOI:** [https://doi.org/10.1016/j.devcel.2021.01.017](https://doi.org/10.1016/j.devcel.2021.01.017)

---

## Background

포유류에서는 재생을 저해하는 흉터(scar) 형성이 척수(SC) 재생을 방해하며, 반응성 흉터경계 성상교세포(scar-bordering astrocyte)가 살아남은 뉴런과 비뉴런성 병변 중심부를 분리한다. 반면 성체 제브라피시는 손상 부위를 가로질러 재생을 촉진하는 아교세포 다리(glial bridge)를 형성하는 특수 아교세포를 지녀, 완전 척수 절단 후 6~8주 내에 마비를 회복한다. 선행 연구는 결합조직성장인자 a(ctgfa)가 손상 후 뇌실막 방사형 아교(ERG) 전구세포에서 발현되는 핵심 브리징 인자임을 밝혔다.

제브라피시의 아교 브리징은 포유류 말초신경 손상 후 슈반세포(Schwann cell) 매개 복구와 형태적·기능적으로 유사하며, 슈반세포는 상피성에서 가소성이 높은 중간엽성 운명으로 부분 재프로그래밍된다. 본 연구는 제브라피시 브리징 아교의 분자 정체성을 규명하고, 포유류 아교와의 종 간 비교를 통해 재생능 차이를 결정하는 유전자 조절 네트워크를 찾고자 하였다.

---

## Key Experiment Methods

1. ctgfa:mCherry 리포터 계통과 gfap:EGFP를 결합하여 브리징 아교를 표지하고, 손상 후 5일(5 dpi)에 ctgfa+gfap+ 세포를 FACS 분리.
2. 완전 척수 절단 후 분리 세포의 FACS-seq(심층 RNA-seq)과 5, 10, 21 dpi 및 비손상 대조군의 벌크 척수 RNA-seq 수행.
3. 제브라피시 브리징 아교를 마우스 복구 슈반세포 및 마우스 흉터경계 성상교세포 데이터와 종 간 전사체 비교.
4. 120개 상피/중간엽 EMT 표지자를 FACS-seq·qRT-PCR로 평가; twist1a, Cdh1, Cdh2, Vimentin을 RNAscope와 면역조직화학으로 분석.
5. gfap:EGFP 척수 조직(1 wpi)의 단일핵 RNA-seq(10x Genomics, 33,185개 핵)로 아교 이질성 해상.
6. 성체 제브라피시에서 9개 이상의 전사인자에 대한 대규모 in vivo CRISPR-Cas9 F0 돌연변이 유발, 수영터널 기능회복 검사와 아교 다리 정량; egr1·junbb 안정 돌연변이 계통 확립.
7. 열유도 형질전환체: hsp70:dsRed-dnYap(우성음성 Yap)과 hsp70:Twist1a-2A-EGFP로 Yap 및 Twist1a의 소실·획득 기능 분석.

---

## Results

- FACS-seq로 재생촉진 제브라피시 브리징 아교의 첫 전사체를 규명; ctgfa가 농축되고 gfap 및 뉴런/희소돌기아교 표지자(neurod1, mbpa)는 고갈됨. EMT 유전자 vimentin, twist1, zeb2가 농축됨.
- 종 간 비교: 브리징 아교는 마우스 복구 슈반세포와 재생·상처치유 및 EMT 유전자(snai2, tgfb1, cdh1, ctgf/ccn2)를 공유하나 별개의 세포 운명이며, 마우스 흉터경계 성상교세포와도 상당한 전사체 중첩(농축 ~12%, 고갈 ~9%)을 보임(s100a10(A2 성상교세포 표지), stat3 포함).
- 복측 뇌실막 전구세포는 손상 후 EMT를 겪음: 상피 표지자 하향, 중간엽 표지자 농축; twist1a는 1~2 wpi에 복측 뇌실막 전구세포에 국소화, ctgfa+ 세포에서 Cdh2/Vimentin 상향·Cdh1 하향.
- snRNA-seq로 10개 아교 하위클러스터 해상; Glial-7, -8, -9가 브리징 아교(ctgfa+twist1a+, ctgfa+twist1b+, 증식성 하위군)에 해당하며 중간엽 전이와 축삭유도(axon guidance) 시그니처를 보임.
- CRISPR-Cas9 스크리닝으로 아교 브리징과 기능적 척수 복구에 필요한 유전자 조절 네트워크(bach1a/b, egr1, junbb, spi1a, taz/yap1)를 기능적으로 검증; egr1·junbb 소실 시 twist1a 발현 감소.
- Yap 신호: Yap이 복측 뇌실막 전구세포에서 우선적으로 핵 내 활성화됨; dnYap 발현은 기능회복을 저해하고 아교 다리를 ~50% 감소시키며 ctgfa·twist1a 발현을 감소시킴. 따라서 Yap은 ctgfa 의존 브리징과 twist1a 구동 EMT의 상류에 위치.
- Twist1a 획득 기능(열유도)은 기능회복을 향상시키고 아교 다리와 뇌실막 증식을 2배로 증가시켜, EMT 활성화가 재생을 촉진하기에 충분함을 입증.

---

## Perspective

- **의의**: EMT를 재생능이 있는 제브라피시 아교와 재생능이 없는 포유류 아교를 구별하는 특징으로 규명하고, 아교 브리징과 기능적 척수 복구에 필요·충분한 Yap → ctgfa/twist1a 다중 노드 유전자 조절 네트워크를 정의한다. 포유류 아교를 브리징/중간엽 표현형으로 전환하면 흉터를 완화하고 축삭 재성장을 지원할 수 있다는 가능성을 제시한다.
- **한계**: 기전 규명이 정해진 전사인자 집합에 집중되었으며, Yap 상류의 기계적/Hippo 감지 기전과 포유류 성상교세포로의 직접적 전이 가능성은 아직 확립되지 않음. 종 간 비교는 기존 공개 데이터에 의존함.
- **향후 방향**: 이 EMT 구동 네트워크를 포유류 아교에서 활성화하면 브리징과 회복이 촉진되는지 검증; 복측 뇌실막 전구세포 니치와 운동뉴런 도메인 방향의 계보 제한을 추가 규명.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- GEO: GSE164945


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
