---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p07.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# Transcriptome profile of rat genes in injured spinal cord at different stages by RNA-sequencing (RNA 시퀀싱을 통한 손상 시기별 쥐 척수 유전자 전사체 프로파일)

## Citation (NLM)
Shi LL, Zhang N, Xie XM, Chen YJ, Wang R, Shen L, Zhou JS, Hu JG, Lü HZ. Transcriptome profile of rat genes in injured spinal cord at different stages by RNA-sequencing. BMC Genomics. 2017;18:173. doi:10.1186/s12864-017-3532-x

**DOI:** [https://doi.org/10.1186/s12864-017-3532-x](https://doi.org/10.1186/s12864-017-3532-x)

---

## Background

척수손상(SCI)은 운동·감각 기능의 파괴적 소실을 초래하며 현재 효과적인 치료법이 없다. 외상성 SCI의 병리 변화는 즉각적인 1차 손상과 이후 여러 생물학적 과정에 걸쳐 광범위한 시간적 유전자 발현 변화를 일으키는 2차 손상 연쇄로 구성된다. 이러한 복잡성 때문에 SCI 기전 이해와 치료법 개발에는 전장(genome-wide) 전사체 분석이 필요하다.

기존 cDNA 마이크로어레이/유전자칩 연구는 해상도·동적 범위·정확도에 한계가 있었다. 본 연구는 고처리량 RNA 시퀀싱(RNA-Seq)을 이용해 급성·아급성·만성 단계에 걸친 성체 쥐 손상 척수의 시간적 전장 유전자 발현을 프로파일링하여 SCI 병리에 관여하는 핵심 유전자와 경로를 규명하고자 하였다. 쥐(rat) 타박 모델은 공동(cavity) 형성 및 흉터/염증 반응 등 병리가 마우스보다 인간 SCI에 더 유사하다고 여겨져 선택되었다.

---

## Key Experiment Methods

1. New York University Impactor를 이용한 타박성 SCI(암컷 SD 쥐 12마리, T9 추궁절제 후 10 g 막대를 25 mm 높이에서 낙하); 가짜수술 대조군은 추궁절제만 시행.
2. BBB(Basso, Beattie, Bresnahan) 운동 등급 척도로 손상 전부터 28 dpi까지 뒷다리 기능 평가.
3. 가짜수술 및 급성(1 dpi)·아급성(6 dpi)·만성(28 dpi) 단계에서 손상 중심부 주변 5 mm 척수 절편 채취(그룹당 n = 3).
4. RNA-Seq: TRIzol RNA 추출, NEBNext Ultra 라이브러리 제작, Illumina HiSeq 페어드엔드 시퀀싱(Novogene); 총 12개 cDNA 라이브러리.
5. 생물정보학: TopHat/Bowtie 정렬, HTSeq 카운팅, FPKM 정량, DESeq 차등발현 분석(조정 P < 0.05), GO(GOseq)·KEGG(KOBAS) 농축 분석, 계층적·K-means 클러스터링.
6. 선정한 약 10~13개 DEG(C1qb, Ccl2, Cxcl2, Enpp3, Il6, Lcn2, Ncf1, Pf4, Plau, Tspo)를 GAPDH 정규화 qRT-PCR로 검증.

---

## Results

- BBB 점수: 손상군 모두 1 dpi에 0점, 28 dpi에 약 11.67점으로 회복하여 중등도 손상에 해당.
- 가짜수술 대비 차등발현유전자(DEG): 급성(1 dpi) 1,797개(상향 1,223/하향 574), 아급성(6 dpi) 6,590개(상향 3,460/하향 3,130), 만성(28 dpi) 3,499개(상향 1,866/하향 1,633). 아급성기(6 dpi)에서 전사체 변화가 최대.
- PCA에서 낮은 분산과 생물학적 반복 간 밀집 클러스터링 확인; qRT-PCR이 RNA-Seq 발현 패턴을 검증.
- 계층적·K-means 클러스터링으로 7,632개 DEG를 8개 하위클러스터로 분류; 변화 유전자 대부분이 6 dpi에서 발현 극값 도달.
- GO 농축: 면역반응, MHC 단백복합체, 항원 처리/제시, 번역/리보솜, 이온게이트 채널 활성, small GTPase 신호, 사이토카인/케모카인 활성에 가장 농축.
- KEGG 경로: 리보솜, 항원 처리·제시, 역행성 엔도카나비노이드 신호, 축삭유도, 도파민성/글루탐산성/GABA성 시냅스, 그리고 TNF, HIF-1, NF-κB, Toll-like receptor, NOD-like receptor, cAMP, 칼슘, 옥시토신, Rap1, B세포수용체, 케모카인 신호.
- 기존 SCI 유전자(Socs3, Il17, Tnf, Il6, Il1b, CD44, Fgf2, Mmp9, Bax) 확인 및 단계별 미보고 후보 제시: 급성(Csf2rb, Plin2, Gadd45g, Sbno2, Flnc, Bcl3, Glipr2, Trib1), 아급성(Plau, Hk3, Trem2), 만성(Tnfaip6, Ncf1, Asb15, Cp, Acp5, Clec4a3).

---

## Perspective

- **의의**: 급성·아급성·만성 단계에 걸친 쥐 SCI의 체계적·시간분해 전장 RNA-Seq 특성화를 제공하여, 알려진 병리 유전자를 확인하고 다수의 신규 후보 유전자·경로(예: 리보솜 생합성, 역행성 엔도카나비노이드, 옥시토신, Rap1 신호)를 향후 기전·치료 연구의 기반으로 제안.
- **한계**: 신규 후보에 대한 기능적 검증이 없는 서술적·상관적 생물정보학 연구이며, 표본 크기가 작고(그룹당 n = 3) 초기 사망률이 높음; 종·방법 차이로 기존 마우스/마이크로어레이 데이터와의 직접 비교가 제한됨.
- **향후 방향**: 새롭게 지목된 유전자·경로의 SCI 진행 및 재생에서의 기능적 규명; 인간과 유사한 병리를 지닌 쥐 모델을 활용한 기전·치료 개발.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
