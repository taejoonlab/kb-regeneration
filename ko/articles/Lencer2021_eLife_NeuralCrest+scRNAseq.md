---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p05.txt
---

# Single-cell RNA analysis identifies pre-migratory neural crest cells expressing markers of differentiated derivatives

## Citation (NLM)
Lencer E, Prekeris R, Artinger KB. Single-cell RNA analysis identifies pre-migratory neural crest cells expressing markers of differentiated derivatives. eLife. 2021;10:e66078. doi:10.7554/eLife.66078

**DOI:** [https://doi.org/10.7554/eLife.66078](https://doi.org/10.7554/eLife.66078)

---

## Background

신경능선(neural crest)은 척추동물에만 존재하는 일시적이고 이동성이 있는 줄기세포 유사 집단으로, 두개안면 연골/뼈, 말초신경계 뉴런과 신경교세포, 색소세포 등 다양한 유도체를 만든다. 신경능선세포(NCC)가 언제·어떻게 이러한 다양한 운명을 획득하는지는 오래된 발생학적 질문이다. 고전적 모델은 단계적 이분지(bifurcating) 운명 결정을 제시하며, 닭·개구리 연구는 이동성 NCC가 다능성이며 이동 환경의 신호가 필요하다고 본 반면, 제브라피시·메추라기 연구는 NCC가 이동 전에 이미 계통이 제한된다고 제시하였다.

단일세포 RNA 시퀀싱(scRNA-seq)은 발생 중 조직 내 전사체 이질성을 드러낼 수 있다. 본 연구는 제브라피시 몸통 신경능선세포(tNCC)가 이동 초기 단계에서 어떤 전사체 지형을 갖는지, 특히 이동성과 이동 전(pre-migratory) tNCC가 공존하는 시기(24 hpf)에 샘플링하여 세포가 이동 이전에 분화 프로그램을 개시하는지를 검증한다.

---

## Key Experiment Methods

1. 24 hpf(25-somite) 제브라피시 배아 몸통에서 tg(-4.9sox10:eGFP)+ 세포를 FACS로 분리(배아 80마리 pooling)한 뒤 10X Genomics scRNA-seq 수행(607세포 분석).
2. 비지도 클러스터링(Seurat), 마커 유전자 기반 주석, RNA velocity(Velocyto)로 발생 pseudotime/전이 추론.
3. 기존 48·68 hpf sox10:eGFP tNCC 아틀라스(Howard et al., 2021) 및 전체 배아 아틀라스(14/18/24 hpf, Wagner et al., 2018)와의 교차 데이터 통합.
4. 정량적 hybridization chain reaction(qHCR) in situ hybridization으로 xanthoblast 및 Rohon-Beard(RB) 계통의 신규 마커 검증(NCC 표지는 tg(sox10:TagRFP), RB 표지는 HNK-1 면역염색 활용).
5. NRD/prdm1a-/- 돌연변이 분석으로 후보 유전자를 NCC/RB 유전자조절네트워크(GRN) 내에 위치시킴.

---

## Results

- 24 hpf tNCC는 전사체적으로 이질적이며, 다능성 tNCC 전구세포(crestin, sox10, foxd3, tfap2a 및 후방 Hox 유전자)와 이막(otic)/측선, 간엽성(mesenchymal), 후방 아치 두개 NCC 집단 등을 포함하였다.
- 이동 전으로 추정되는 tNCC 상당수가 이미 색소 계통 프로그램을 발현: 범색소/멜라노포어 전구세포 클러스터(mitfa, gpr143, trpm1b)와, 분화된 xanthophore GRN(aox5, pax7a/b, gch)을 발현하는 xanthoblast 클러스터가 확인되었고, 여기에는 신규 마커 slc2a15a/b와 gjb8(cx30.3)이 포함되었다.
- RNA velocity 결과, tNCC 전구세포(cluster 1)가 xanthoblast 클러스터로 전이하는 강한 신호가 관찰되어 이동 이전 색소 분화 프로그램 개시 가설과 일치하였다.
- 별개의 Rohon-Beard 감각 뉴런 집단(isl1, isl2a/b, scrt2, prdm14, drgx)이 회수되었으며, RB는 sox10/sox10 전이유전자를 낮은 수준으로 발현해 NCC와의 신경판 경계(neural plate border) 공통 기원과 부합하였다. 신규 RB 마커로 fgf13a/b, cxcr4b, pou4f4가 제시되었다.
- 교차 데이터 통합으로 정체성이 확인됨: 24 hpf xanthoblast는 68 hpf 분화 xanthophore로 연결되며 유전자(gjb8, pax7a/b, aox5, slc2a15a/b)를 공유하였다. PNS 유도체 유전자는 이동 후 단계(48/68 hpf)에서만 나타나, NCC가 이동 이후까지 뉴런 분화를 지연시킴을 시사하였다.
- qHCR로 이동 전/초기 이동 배측 신경관 tNCC에서 slc2a15b·gjb8가 aox5와 공발현함을, HNK-1+ RB 뉴런에서 fgf13a·cxcr4b 발현을 확인하였다.
- prdm1a-/- 돌연변이에서는 배측 신경관의 slc2a15b, gjb8, fgf13a, cxcr4b 발현이 소실(비-NCC/RB 영역 발현은 유지)되어, 이들 유전자가 신경판 경계 특정자 Prdm1a의 하류에 위치함을 보였다.

---

## Perspective

본 연구는 일부 제브라피시 몸통 NCC가 이동 이전에 계통 특이적(xanthophore) 유전자조절네트워크를 개시한다는 증거를 제시하여, 고전적 계통 제한 세포 표지 연구를 확장하고 환경 신호 주도의 순수 이분지 모델에 도전하는 최근 마우스·닭 scRNA-seq 결과와 부합한다. 또한 xanthoblast 및 Rohon-Beard 뉴런 계통에 대한 신규 후보 마커(slc2a15b, gjb8, fgf13a/b, cxcr4b, pou4f4)를 제공하고, NCC와 RB의 발생학적 유사성 및 신경판 경계 공통 기원을 강화한다. 저자가 밝힌 한계로는 상대적으로 적은 세포 수(607세포)와 단일 시기 샘플링으로 다중 운명 공발현 세포 및 이동 선도(leader/trailblazer) 세포 검출이 제한되며, 이동 전 색소세포가 실제로 운명 고정되었는지는 기능적으로 검증되지 않았다는 점이 있다. 향후 더 이른 시기 샘플링, 후보 유전자 기능 검증, RB의 상동성/진화 규명을 위한 비척추동물 척삭동물 운동뉴런과의 비교가 제안된다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
