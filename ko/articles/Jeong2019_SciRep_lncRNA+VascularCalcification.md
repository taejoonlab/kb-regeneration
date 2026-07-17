---
tags: [2026-07, Ossification]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
---

# Long noncoding RNAs in vascular smooth muscle cells regulate vascular calcification

## Citation (NLM)

Jeong G, Kwon DH, Shin S, Choe N, Ryu J, Lim YH, Kim J, Park WJ, Kook H, Kim YK. Long noncoding RNAs in vascular smooth muscle cells regulate vascular calcification. Sci Rep. 2019;9(1):5848. doi:10.1038/s41598-019-42283-x

**DOI:** [https://doi.org/10.1038/s41598-019-42283-x](https://doi.org/10.1038/s41598-019-42283-x)

---

## Background

혈관 석회화는 칼슘-인산 대사 불균형으로 혈관벽에 하이드록시아파타이트 결정이 병적으로 축적되는 현상이다. 이는 혈관 탄성을 떨어뜨리고 심근 허혈, 심부전, 부정맥의 위험을 높인다. 과거에는 수동적 퇴행 과정으로 여겨졌으나, 현재는 골형성과 특징을 공유하는 능동적 세포 매개 과정으로 인식된다. 성숙 혈관평활근세포(VSMC)는 수축성 표현형에서 골모세포성/연골성 표현형으로 '표현형 전환(phenotype switching)'을 겪으며 Runx2, BMPs, Msx2 등 골모세포 관련 인자를 상향조절하고 수축 마커를 하향조절한다. 심혈관 질환에서 microRNA 연구는 활발하나 긴 비암호화 RNA(lncRNA)의 혈관 석회화 역할은 보고된 바 없었다. 본 연구는 VSMC 석회화 중 차등발현되는 lncRNA를 발굴하고 그 기능을 규명하고자 하였다.

---

## Key Experiment Methods

**1. 석회화 모델 및 RNA 시퀀싱**
- 일차 배양 랫트 VSMC에 2 mM 무기인산(Pi)을 6시간, 3일, 6일 처리하여 석회화 모사
- Ribo-Zero total RNA-seq(HiSeq 2500, paired-end, 중복); Ensembl + RefSeq 주석 병합(참조 lncRNA 8,357개); Cufflinks 조립으로 신규 랫트 lncRNA 1,201개 발굴

**2. 후보 lncRNA 선정 및 특성 분석**
- 세 기준: Pi 처리 시 차등발현, 종간 유전자좌 보존, 석회화 관련 알려진 인접 유전자 → 4개 후보(Snhg1, Linc00116, Snhg16, Lrrc75a-as1)
- qRT-PCR 검증; 5′/3′ RACE로 전장 전사체 구조; A10 세포 세포분획으로 국소화; CPC/CPAT 암호화잠재력 평가(Linc00116은 중등도 암호화잠재력으로 제외)

**3. 기능적 획득/소실 실험**
- A10 혈관평활근세포에서 후보 lncRNA 과발현(pcDNA3) 및 Lrrc75a-as1의 2개 siRNA 넉다운
- 비색 분석 및 Alizarin red S 염색/정량으로 칼슘 침착 측정
- 골모세포 관련 인자 Runx2, Msx2, Bmp2 qRT-PCR

**4. 조절 네트워크 분석**
- miRNA 표적 예측(miRNA_Targets)을 VSMC 석회화 miRNA 프로파일과 교차 → miR-29a-3p, miR-24-3p
- ENCODE ChIP-seq으로 인간 LRRC75A-AS1 프로모터의 VSMC 관련 전사인자(SRF, CREB1, STAT3) 분석

---

## Results

**석회화 중 수백 개 lncRNA가 변화, 4개 후보 선정**
RNA-seq에서 Pi 처리 VSMC의 수백 개 lncRNA가 차등발현되었고, 경로 분석에서 VSMC 수축 유전자 하향조절(표현형 전환 성공)이 확인되었다. 4개 후보(Snhg1, Linc00116, Snhg16, Lrrc75a-as1)가 선정 기준을 통과하여 qRT-PCR로 검증되었다. Lrrc75a-as1, Snhg16, Linc00116은 세포질에, Snhg1은 핵에 국소화되었다.

**Lrrc75a-as1은 칼슘 침착의 음성 조절자**
후보들은 Pi에 의해 하향조절되었다. Lrrc75a-as1(및 약하게 Snhg16) 과발현은 A10 세포의 칼슘 침착을 감소시켰다. Lrrc75a-as1의 효과가 가장 강하여 후속 연구 대상으로 선정되었다. 두 siRNA에 의한 Lrrc75a-as1 넉다운은 칼슘 침착을 증가시켰으며 Alizarin red S 염색 증가로 확증되었다.

**Lrrc75a-as1은 골모세포 관련 인자를 억제**
Lrrc75a-as1 과발현은 골모세포 관련 인자 Runx2, Msx2, Bmp2 mRNA를 현저히 감소시켰다 — VSMC 전환분화를 구동하는 바로 그 골형성 스위치 — 이는 Lrrc75a-as1이 골모세포성 표현형 프로그램을 약화시켜 작용함을 나타낸다.

**제안된 조절 기전**
세포질 lncRNA로서 Lrrc75a-as1은 miRNA 스펀지로 작용할 것으로 예측된다. 47개 예측 파트너 중 miR-29a-3p와 miR-24-3p(둘 다 VSMC 석회화/표현형 전환에 관여)가 결합부위를 지녔다. 프로모터 ChIP-seq은 석회화 관련 전사인자 SRF, CREB1, STAT3를 상류 조절자로 지목하였다. 인간/마우스 상동 유전자좌에는 snoRNA(Snord49a/b, Snord65)도 존재하여 추가적 기능 층위의 가능성을 시사한다.

---

## Perspective

본 연구는 혈관 석회화를 직접 조절하는 lncRNA를 최초로 규명한 보고로, Lrrc75a-as1을 골모세포 관련 인자 Runx2·Msx2·Bmp2를 하향조절하여 칼슘 축적을 억제하는 음성 조절자로 확립하였다.

이 발견은 골형성 표현형 전환 개념을 통해 본 볼트의 골화(ossification) 주제에 정확히 부합한다. VSMC 석회화는 골형성 프로그램(Runx2/BMP2/Msx2)을 재현하며, Lrrc75a-as1은 바로 이 골모세포성 전환분화에 대항한다. 이는 볼트의 골·이소성 골화 논문 전반에서 관찰되는 골모세포 계통 전사 프로그램과 병렬을 이루되, 이 경로에 비암호화 RNA 제동을 건다.

기전적 세부는 미해결로 남아 있다. Lrrc75a-as1의 직접적 칼슘 조절 표적은 미상이며, 제안된 miR-29a-3p/miR-24-3p 스펀징 및 SRF/CREB1/STAT3 프로모터 조절은 실험적 검증이 필요하다. 그럼에도 이 lncRNA는 혈관 석회화 및 관련 심혈관 질환의 잠재적 치료 표적으로 제안된다.


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
