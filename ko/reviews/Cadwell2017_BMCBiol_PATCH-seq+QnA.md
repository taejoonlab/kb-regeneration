---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
---

# Q&A: using Patch-seq to profile single cells

## Citation (NLM)
Cadwell CR, Sandberg R, Jiang X, Tolias AS. Q&A: using Patch-seq to profile single cells. BMC Biol. 2017;15:58. doi:10.1186/s12915-017-0396-0

**DOI:** [https://doi.org/10.1186/s12915-017-0396-0](https://doi.org/10.1186/s12915-017-0396-0)

---

## Overview
개별 뉴런은 유전자 발현, 형태, 전기생리학적 특성에서 크게 다르지만, 이 세 차원을 단일 세포 수준에서 동시에 평가할 수 있는 기법은 드물었다. 본 Q&A 형식의 글은 저자들이 개발한 **Patch-seq** 기법을 소개한다. Patch-seq는 전세포 패치클램프(whole-cell patch clamp) 기록과 단일세포 RNA 시퀀싱(scRNA-seq), 면역조직화학을 결합하여 개별 뉴런의 전사체·형태·생리 특성을 통합적으로 프로파일링한다.

기존 scRNA-seq가 분리(dissociated)된 세포를 사용하는 것과 달리, Patch-seq는 살아있는 조직 절편이나 온전한 동물 내(in situ/in vivo)에서 단일 세포를 연구할 수 있어, 세포의 해부학적 위치·형태·전기적 특성·연결성·기능 정보를 동시에 확보한다. 저자들은 생쥐 대뇌피질 뉴런에 이 기법을 적용했으며, Linnarsson·Harkany 그룹(Fuzik et al.)도 병행하여 독립적으로 유사 기법을 개발했다.

이 기법은 신경계와 같은 복잡한 조직의 세포 유형을 분류·주석(annotate)하고, 질병 연관 유전자를 발현하는 기능적 세포 유형을 규명하며, 가소성 중 단일 세포의 전사 변화를 연구하는 데 폭넓게 활용될 수 있다.

---

## Key Topics
- **Patch-seq란**: 전세포 패치클램프 기록 후 세포 내용물을 피펫으로 흡인하여 scRNA-seq에 사용, 조직 절편에 남은 세포 형태를 면역조직화학으로 시각화하는 다중양식(multimodal) 프로파일링.
- **프로토콜 차이**: 저자 프로토콜(Smart-seq2 기반 full-length cDNA)과 Fuzik et al. 프로토콜(UMI 기반 STRT). 공통 변형점 — RNase-free 준비, 큰 피펫 팁, 소량 내부 용액, EGTA 첨가. 저자 프로토콜은 glycogen과 RNase 억제제를 추가(cDNA 수율 약 3배 증가).
- **형태 직접 회수**: 내부 용액에 biocytin 첨가 및 생리적 삼투압 조정으로 기록 후 직접 형태 회수 가능.
- **기존 기법과의 비교**: RT-PCR(소수 유전자만), 마이크로어레이(제한된 동적 범위)에 비해 우수. 세포당 ~7000 유전자 검출, 세포 간 상관 ~0.6으로 분리 세포 scRNA-seq에 필적.
- **실용 정보**: 처리량(하루 30–40 샘플, 형태 회수 시 10–15개), 세포당 비용 약 $21, in vivo 패칭의 난점, RNase 오염·시료 수집 문제 진단.
- **대안 전략**: 분리 세포 고처리량 scRNA-seq로 분자적 세포 유형 규명 후 transgenic(Cre) 계통으로 형태·생리 특성화(단, 드라이버 계통 특이성 한계).

---

## Key Findings
- Patch-seq는 단일 뉴런의 전사체·형태·전기생리 특성을 동시에 연결하는 강력한 도구로, 특히 복잡한 신경계 조직의 세포 유형 분류와 분자적 세포 유형과 표현형의 연결에 유용하다.
- 엄격한 RNase-free 조작이 성공의 절대적 핵심이며, 건강한 세포·안정적 기록·적절한 흡인이 고품질 RNA 확보에 중요하다.
- Smart-seq2 기반 접근은 Allen Brain Science Institute 등 참조 데이터베이스와 비교 가능하다는 이점이 있으나, droplet/microfluidic 기반 시퀀싱과는 호환되지 않는다(in situ 패칭 필요).
- 분자생물학과 전기생리학 전문성이 모두 필요하므로 상보적 기술을 가진 연구자 간 협업에 적합하다.

---

## Perspective
이 Q&A는 Patch-seq의 원리·프로토콜·실무적 고려사항을 실용적으로 정리하여, 신경계 세포 유형의 다차원적 특성화를 위한 방법론적 표준을 제시한다. 의의는 게놈 전반의 발현 데이터를 갖춘 포괄적 세포 유형 지도(cell type atlas) 구축의 토대를 제공하고, 질병 연관 유전자를 발현하는 특정 기능적 세포 유형을 식별함으로써 신경정신질환 이해에 기여할 수 있다는 점이다. 한계로는 낮은 처리량(패치클램프 숙련 요구), 시퀀싱 방법 간 비교의 어려움, in vivo 적용의 기술적 난점이 있다. 향후 방향은 패칭 자동화, 형태 회수 시간 단축, 그리고 다중 동시 기록·transgenic·바이러스·optogenetic 기법과의 결합을 통한 세포 유형 특이적 연결성·가소성의 분자 기전 규명이다.

---

## Key References
- Cadwell CR, Palasantza A, Jiang X, et al. (2016) Electrophysiological, transcriptomic and morphologic profiling of single neurons using Patch-seq. *Nat. Biotechnol.* 34:199–203.
- Fuzik J, Zeisel A, Mate Z, et al. (2016) Integration of electrophysiological recordings with single-cell RNA-seq data identifies neuronal subtypes. *Nat. Biotechnol.* 34:175–183.
- Zeisel A, Munoz-Manchado AB, Codeluppi S, et al. (2015) Cell types in the mouse cortex and hippocampus revealed by single-cell RNA-seq. *Science* 347:1138–1142.
- Tasic B, Menon V, Nguyen TN, et al. (2016) Adult mouse cortical cell taxonomy revealed by single cell transcriptomics. *Nat. Neurosci.* 19:335–346.
- Macosko EZ, Basu A, Satija R, et al. (2015) Highly parallel genome-wide expression profiling of individual cells using nanoliter droplets. *Cell* 161:1202–1214.
- Jiang X, Shen S, Cadwell CR, et al. (2015) Principles of connectivity among morphologically defined cell types in adult neocortex. *Science* 350:aac9462.
- Picelli S, Bjorklund AK, Faridani OR, et al. (2013) Smart-seq2 for sensitive full-length transcriptome profiling in single cells. *Nat. Methods* 10:1096–1098.
- Kodandaramaiah SB, Franzesi GT, Chow BY, et al. (2012) Automated whole-cell patch-clamp electrophysiology of neurons in vivo. *Nat. Methods* 9:585–587.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
