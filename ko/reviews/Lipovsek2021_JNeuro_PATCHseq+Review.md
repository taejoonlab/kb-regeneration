---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p05.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Patch-seq: Past, Present, and Future

## Citation (NLM)
Lipovsek M, Bardy C, Cadwell CR, Hadley K, Kobak D, Tripathy SJ. Patch-seq: Past, Present, and Future. J Neurosci. 2021;41(5):937-946. doi:10.1523/JNEUROSCI.1653-20.2020

**DOI:** [https://doi.org/10.1523/JNEUROSCI.1653-20.2020](https://doi.org/10.1523/JNEUROSCI.1653-20.2020)

---

## Overview
단일세포 전사체(single-cell transcriptomics) 기술은 신경과학을 혁신하고 있으나, 뉴런 생물학을 포괄적으로 이해하기 위해서는 유전자 발현 데이터를 형태(morphology) 및 생리(physiology) 정보와 통합해야 한다. 이 미니심포지엄 리뷰는 이러한 요구에 대응하여 여러 연구그룹이 병렬적으로 개발한 "Patch-seq" 기법을 정리한다. Patch-seq는 전형적인 whole-cell patch-clamp 프로토콜을 변형하여, 개별 뉴런에서 전기생리 기록을 수행한 뒤 세포 내용물의 mRNA 시퀀싱과 동일 세포의 형태 재구성을 가능하게 하는 다중양식(multimodal) 방법이다.

저자들은 먼저 견고한 Patch-seq 실험을 가능하게 한 핵심 기술적 발전과, 생성된 풍부한 다중양식 데이터를 해석하기 위한 분석적 해법을 개괄한다. 이어서 Patch-seq가 신경과학의 새롭고 오래된 질문들을 해결하는 데 어떻게 적용되었는지 검토한다. 여기에는 (1) 해부학적 위치, 기능적 특성, 계통(lineage) 또는 이들의 조합에 근거한 특정 뉴런 집단의 표적 연구, (2) 다중양식 세포유형 아틀라스의 편찬 및 통합, (3) 형태적·기능적 다양성의 분자적 기반 규명이 포함된다.

Patch-seq는 분자신경생물학과 생리학의 교차점에 위치한 다중양식 접근법으로서, 유전자 발현을 뇌 기능과 직접 연결할 수 있는 독보적 위치를 점한다. 리뷰는 마지막으로 추가적 기술 개발 기회와 이 기법의 도입으로 이득을 볼 수 있는 연구 방향을 제시한다.

---

## Key Topics
- **실험 워크플로우 (Sample collection):** RNase-free 조건 유지, 피펫 팁 직경 및 내부 용액 조성 조정, 세포질(및 핵) 흡인. 최근에는 nucleated patch 기법으로 핵까지 추출하여 RNA 수율과 전사체 데이터 품질을 크게 개선. biocytin/rhodamine을 이용한 형태 재구성 및 생세포 이미징.
- **모델 시스템:** 급성 뇌 절편(acute slices), in vitro 배양(iPSC 유래 뉴런), in vivo 기록, 비인간 영장류·인간 조직, 비신경 세포(췌장 도세포)까지 확장.
- **cDNA 합성·라이브러리·시퀀싱:** droplet 기반 고처리량 방법(10x, Drop-seq)과는 비호환, 튜브/플레이트 기반. SMART-seq v4, Smart-seq2, UMI 기반, Smart-Seq3 등. 비용은 세포당 약 $20~90.
- **데이터 처리·분석:** dissociated scRNAseq/snRNAseq 파이프라인과 유사. exon+intron read 활용, off-target mRNA(주변 세포·neuropil, glia) 오염 정량, 참조 아틀라스로의 매핑, reduced-rank regression·coupled autoencoder·bottleneck network 등 다중양식 통계 도구.
- **응용:** 표적 세포 샘플링의 장점(위치·투사·감각반응·계통 연관), 다중양식 세포유형 아틀라스 통합의 "Rosetta stone" 역할, 형태·기능 다양성의 분자적 기반(예: Kcna1과 활동전위 폭 상관).

---

## Key Findings
- Patch-seq는 실험자가 전사체 샘플이 어느 세포에서 왔는지 정확히 알 수 있다는 결정적 장점을 제공하여, 전사체를 공간적 맥락·형태·연결성·기능적 표현형과 짝지을 수 있게 한다.
- 시각·운동 피질에서 수천 개 뉴런을 프로파일링한 최신 다중양식 분류 연구들은 알려진 전사체 세포유형의 대부분을 포괄하였다. 그러나 어떤 단일 특성(feature)도 세포유형을 명확히 규정하기에는 충분하지 않으며, 밀접하게 연관된 전사체 세포유형은 형태전기(morphoelectric) 공간에서 잘 분리되지 않는다.
- 선조체 개재뉴런에서는 전사체 gradient와 전기생리 표현형의 연속체(continuum)가 관찰되어, 등급화된(graded) 표현형이 뉴런 다양성의 특징일 수 있음을 시사한다.
- iPSC 유래 뉴런 배양에서 머신러닝 분류기가 전사 프로파일로부터 개별 뉴런의 전기생리적 상태를 예측할 수 있음이 입증되었다.
- 주요 도전 과제 세 가지: (1) 낮은 처리량, (2) 습득·숙달이 어려운 노동집약적 기법, (3) 다양한 데이터 양식 해석을 위한 학제간(interdisciplinarity) 필요성.

---

## Perspective
Patch-seq는 patch-clamp 실험이 가능한 모든 샘플에 적용될 수 있는 다재다능한 방법으로, 신경외과적으로 절제된 인간 조직, in vivo 기록 등으로 이미 확장되었다. 향후 방향으로는 G&T 프로토콜을 통한 유전체-전사체 동시 프로파일링, 크로마틴 접근성·DNA 메틸화 등 후성유전체 프로파일링, 단일세포 프로테오믹스, CRISPR 기반 유전자 발현 교란과의 결합이 제시된다. 또한 세포 상태 동역학, 시냅스 기능·가소성의 전사체 기전, 회로 조립·연결성 예측(multi-Patch-seq), 분자와 기능 간 인과관계 규명 등이 유망한 미개척 영역으로 논의된다. 한계로는 처리량, 기술 난이도, 형태 데이터를 특징 벡터로 표현하는 어려움이 강조된다. 이 리뷰는 척수/신경계 세포유형 아틀라스 구축과 신경 세포 정체성 정의라는 맥락에서 다중양식 프로파일링의 중요성을 뒷받침한다.

---

## Key References
- Cadwell CR, et al. (2016) Electrophysiological, transcriptomic and morphologic profiling of single neurons using Patch-seq. *Nat Biotechnol* (Patch-seq 초기 구현).
- Fuzik J, et al. (2016) Integration of electrophysiological recordings with single-cell RNA-seq data identifies neuronal subtypes. *Nat Biotechnol*.
- Bardy C, et al. (2016) Predicting the functional states of human iPSC-derived neurons with single-cell RNA-seq and electrophysiology. *Mol Psychiatry* (GSE159074).
- Cadwell CR, et al. (2017) Multimodal profiling of single-cell morphology, electrophysiology, and gene expression using Patch-seq. *Nat Protoc* (프로토콜 논문).
- Gouwens NW, et al. (2020) Integrated morphoelectric and transcriptomic classification of cortical GABAergic cells. (시각피질 GABA성 뉴런 4270세포, NEMO archive).
- Scala F, et al. (2020) Phenotypic variation of transcriptomic cell types in mouse motor cortex. (운동피질 1221세포).
- Kobak D, et al. (2018) Sparse reduced-rank regression for exploratory visualization of paired multivariate data (다중양식 통계 도구).
- Muñoz-Manchado AB, et al. (2018) Diversity of interneurons in the dorsal striatum revealed by single-cell RNA sequencing and Patch-seq (GSE106708).
- Camunas-Soler J, et al. (2020) Patch-seq of human pancreatic islet cells (GSE124742, 비신경 세포 적용).
- Bomkamp C, et al. (2019) Transcriptomic correlates of electrophysiological and morphological diversity (Kcna1-활동전위 폭 상관).

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
