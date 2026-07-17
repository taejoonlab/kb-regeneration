---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p08.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Identification of a discrete subpopulation of spinal cord ependymal cells with neural stem cell properties

## Citation (NLM)
Stenudd M, Sabelström H, Llorens-Bobadilla E, Zamboni M, Blom H, Brismar H, Zhang S, Basak O, Clevers H, Göritz C, Barnabé-Heider F, Frisén J. Identification of a discrete subpopulation of spinal cord ependymal cells with neural stem cell properties. Cell Rep. 2022;38(9):110440. doi:10.1016/j.celrep.2022.110440

**DOI:** [https://doi.org/10.1016/j.celrep.2022.110440](https://doi.org/10.1016/j.celrep.2022.110440)

---

## Background

척수 중심관을 덮는 상의세포(ependymal cell)는 생리적 조건에서는 다른 세포 유형을 만들지 않지만, 이 집단에는 시험관 내 신경줄기세포(NSC) 특성을 지닌 세포가 존재하며, 손상 후에는 흉터를 형성하는 성상세포(astrocyte)의 대부분과 일부 재수초화 희소돌기아교세포(oligodendrocyte)를 생성한다. 상의세포 유래 성상세포는 조직 손상을 제한하고 뉴런 생존을 지원하며, 상의세포의 손상 반응을 조절하는 것은 치료적 잠재력을 지닌다. 기존 연구는 형태·표지자 이질성을 시사했고 신경구 형성능이 풍부한 아집단이 보고되었으나, 그 신경구는 효율적으로 자가재생하지 못했고 어떤 세포가 실제로 줄기세포 잠재력을 가지며 척수 손상 후 자손을 생성하는지는 알려지지 않았다.

이 Report는 Troy(Tnfrsf19)를 발현하는 별개의 아집단(ependymal A, EpA 세포)을 규명하고, 시험관 내 및 손상 후 줄기세포 행동을 특성화한다.

---

## Key Experiment Methods

1. Rosa26-tdTomato 또는 Rosa26-Confetti 리포터 배경의 Troy-CreER(Tnfrsf19) knock-in 마우스에서 유전적 fate mapping; RNAscope in situ hybridization으로 재조합 세포의 Tnfrsf19 전사체 확인.
2. 범상의세포 표지자(FoxJ1, Sox2, Sox9, Vimentin, Nestin), 초고해상도/3D-SIM 현미경, Ki67 증식 평가로 EpA 세포의 정체·위치·형태 특성화.
3. 연속 계대 신경구 분석으로 자가재생 검증 및 성상세포·뉴런·희소돌기아교세포로의 시험관 내 분화.
4. 척수 손상(dorsal funiculus incision 및 crush lesion)과 EdU 표지; 재조합 자손(Sox9+ 성상세포, Sox10/NogoA/Myrf+ 희소돌기아교세포)을 15주까지 정량; 손상 1주·2개월·15개월 전 재조합 유도 시점 실험.
5. R26-Confetti 리포터를 이용한 저빈도 확률적 재조합으로 손상 후 개별 EpA 클론 추적하는 클론 분석.
6. 손상 3일 후 손상/비손상 척수에서 FACS로 분리한 재조합 세포의 droplet 기반 단일세포 RNA-seq; UMAP, RNA velocity(scVelo)와 Monocle 3 궤적 분석, SCENIC 유전자조절네트워크/AUCell regulon 분석, signaling entropy(LandSCENT) 점수화.

---

## Results

- EpA 세포는 척수 상의세포의 약 8.2%(한 분절 전체 세포의 약 0.1%)를 차지하며, 등쪽 상의극에 풍부하고, 종종 혈관과 접촉하는 기저 돌기를 뻗으며, 범상의세포 표지자를 균일하게 발현하면서도 고도로 분화되고 증식이 낮은 상태로 보인다.
- 일차 신경구에서 EpA 재조합률은 상의세포 수준과 일치했으나(농축 없음), 2차 계대부터 자가재생 신경구의 대부분이 EpA 세포에서 유래하여, EpA 세포가 시험관 내 광범위 자가재생 능력의 거의 전부를 담당함을 나타냈다. EpA 유래 신경구는 성상세포·뉴런·희소돌기아교세포를 생성했다.
- Dorsal funiculus incision 또는 crush 손상 후 EpA 세포는 이동성 Sox9+/PDGFRβ- 자손을 생성했고, 재조합 집단은 약 5배 확장되었으며, 상의층 내 EpA 세포 수는 유지되었고(자가재생), 재조합 성상세포와 희소돌기아교세포가 15주에 존재했다. 생체 내에서 상의세포 유래 뉴런은 관찰되지 않았다. 재조합 시점(손상 15개월 전까지)에 관계없이 유사한 자손이 생성되어, EpA 정체가 일시적이지 않고 안정적임을 시사했다.
- 클론 분석은 이동성 EdU+/Sox2+ 자손을 지닌 20개 EpA 클론을 확인했고, 이동은 주로 등쪽/외측이며 rostrocaudal 확산은 제한적이었다. 20개 중 17개 클론에서 동일 색상의 인접 founder 상의세포가 발견되어, 생체 내 단일세포 수준의 자가재생을 입증했다.
- scRNA-seq는 인접한 세 클러스터(EpA1-3)를 분해했다. EpA1(비손상+손상)은 운동성 섬모/분화 상의세포 유전자(Foxj1, Fam183b, Rarres2, Tmem212)를 가장 높게 발현했고, EpA2/EpA3는 거의 전적으로 손상 척수에서 유래했다. RNA velocity/pseudotime은 EpA1→EpA2→EpA3 순서로, signaling entropy(분화 잠재력의 대리 지표) 증가, 리보솜/번역 유전자(EpA2) 상승, 이어 세포주기 유전자(EpA3)를 보였으며, 성상세포(Gfap, Aldh1l1)와 희소돌기아교세포(Olig1/2) 계통 유전자를 점진적으로 획득했다.
- SCENIC는 EpA1에서 높은 상의세포 regulon(Rfx2/Rfx3), EpA2에서 줄기/신경생성 regulon(Sox4, Sox11, Tead2, Gata3), EpA3에서 증식/신경생성 regulon(Pole3, Brca1, Ezh2)을 드러냈다. EpA2/EpA3는 뇌실하영역 NSC 및 transit-amplifying 시그니처 유전자 발현을 획득하여, 줄기세포 유사 상태로의 역분화를 나타냈다.

---

## Perspective

본 연구는 EpA 세포를 성체 척수의 별개의 잠재적 줄기세포 집단으로 규명한다. 이는 고도로 분화된 상의세포로서, 손상 후 역분화(상의 프로그램 상실, signaling entropy 획득)를 거쳐 성상세포와 희소돌기아교세포를 생성하는 자가재생·다능성 줄기세포 유사 상태가 된다. 이는 뇌졸중 후 실질 성상세포의 손상 유도 신경생성 재프로그래밍 및 하등 척추동물에서 관찰되는 교세포 주도 CNS 재생과 유사하여, 포유류 교세포에 진화적으로 보존되었으나 제한된 잠재력이 있음을 시사한다. 희소한(약 0.1%) 표적 가능 세포 집단의 정의는 척수 복구를 위한 재생 치료의 합리적 표적을 제공한다. 저자들이 인정한 한계: 생체 내 단일세포 수준의 다능성은 입증되지 않았으며(희소하고 느린 희소돌기아교세포 생성을 고려할 때 더 큰 클론 분석과 더 긴 손상 후 기간 필요), EpA 세포에 줄기세포 잠재력을 부여하며 다른 상의세포와 구별하는 분자적 기반은 여전히 불명확하다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
