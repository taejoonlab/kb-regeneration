---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p06.txt
---

# Foxm1 regulates neural progenitor fate during spinal cord regeneration

## Citation (NLM)
Pelzer D, Phipps LS, Thuret R, Gallardo-Dodd CJ, Baker SM, Dorey K. Foxm1 regulates neural progenitor fate during spinal cord regeneration. EMBO Rep. 2021;22(11):e50932. doi:10.15252/embr.202050932

**DOI:** [https://doi.org/10.15252/embr.202050932](https://doi.org/10.15252/embr.202050932)

---

## Background

포유류는 중추신경계(CNS) 재생 능력이 제한적이며 척수 손상은 대개 비가역적이다. 반면 *Xenopus*(개구리) 올챙이는 절단 후 척수를 포함한 꼬리 전체를 완전히 재생할 수 있다. 손상된 척수는 하루 안에 신경팽대부(neural ampulla) 형성으로 봉합되고 원래 그루터기(stump)에서 재생된다. 척수 재생의 핵심 특징은 Sox2/3+ 신경전구세포(NPC)의 재활성화로, 이는 척수 재성장과 새 신경세포 생성을 모두 유도한다. 아홀로틀에서는 절단 인접 "source zone"의 NPC가 신경생성 분열에서 증식 분열로 전환하며 광범위하게 증식한다(이 전환은 부분적으로 평면세포극성(PCP) 경로가 주도). 그러나 재생 중 자가재생/증식과 분화 사이의 균형이 어떻게 조절되는지는 잘 알려지지 않았다.

발생 중 증식→신경생성 분열 전환은 부분적으로 세포주기 각 단계의 상대적 길이 변화에 의존한다. 저자들은 분리한 척수에 대한 비편향적 RNA-seq 접근으로, G2/M 전환을 촉진하는 것으로 알려진 전사인자 Foxm1을 *X. tropicalis* 척수 재생 중 특이적으로 발현되는 후보 조절자로 확인하였다.

---

## Key Experiment Methods

1. **Bulk RNA-seq**: 절단 후 0, 1, 3일(dpa)에 분리한 척수를 GO 클러스터링 및 Ingenuity Pathway Analysis(IPA)로 상위 조절자 규명; 기존 whole-tail 재생 데이터와 비교.
2. **foxm1 발현 검증**: in situ hybridisation(ISH, whole-mount + 절편) 및 RT-qPCR 시간경과(0h–7d); 상위 신호 약리학적 검증 — NOX/ROS 억제제 DPI, FGFR 억제제 SU5402, Shh 억제제 cyclopamine.
3. **CRISPR/Cas9 녹아웃**: foxm1 gRNA(ATG 하류 129–152 염기 표적); 생식계열 전달 프레임시프트 돌연변이로 foxm1−/− 올챙이 생성; 모르폴리노(스플라이스 차단) 녹다운 병행.
4. **재생 분석**: foxm1+/+, +/−, −/− 꼬리 재성장을 3, 7 dpa에 비교; F0 모자이크 분석.
5. **증식/세포주기 분석**: EdU 표지 및 chase; Dual-Pulse S-phase Labelling(DPSL, EdU→BrdU)로 절대 세포주기 길이(Tc) 측정; PCNA 염색으로 S/G1-G2/M 판정; 성장분율(PCNA+Sox3+) 정량.
6. **단일세포 RNA-seq**(10X Genomics): 비손상(2,908 세포) 및 재생(0 vs 3 dpa) 척수; Seurat 배치보정, 클러스터 주석, pseudo-time(Monocle), 세포주기 추론.
7. **운명 분석**: 3 dpa EdU pulse 후 5 dpa 운명 판독(Sox3/EdU), Sox3/Myt1 면역형광으로 전구세포 vs 신경세포 비율 정량.

---

## Results

- Bulk RNA-seq는 절단 후 세 시기를 보임: 초기 대사 유전자 상향, 강한 세포주기 유전자 상향, 이어서 신경계 발생 유전자 하향. IPA는 3 dpa에서 Foxm1을 최상위 상위 조절자로 규명; Foxm1과 표적 유전자는 3 dpa에 whole tail이 아닌 척수에서 특이적으로 상향.
- foxm1은 0/1 dpa에는 미발현이나 3 dpa에 재생 척수에 국한(3 dpa 정점, 7 dpa에 기저 복귀). 유도는 ROS 필요(DPI가 foxm1을 약 69% 감소)하나 FGF, Shh 신호와는 독립적.
- foxm1−/− 올챙이는 정상 발생하나 척수 재생이 손상: 7 dpa 꼬리 재성장이 약 35% 감소; 이형접합체는 중간(약 17%) 감소로 용량 의존적 효과.
- Foxm1은 증식률이나 세포주기 길이를 조절하지 **않음**: EdU+ 비율과 절대 Tc(~50시간)가 wt와 foxm1−/−에서 동일; 1차 신경발생 증식도 영향 없음.
- scRNA-seq는 예상되는 척수 세포 유형과 3-dpa 특이적 두 클러스터를 확인: foxm1+ 전구세포 클러스터(sox2+, 다수가 S기, ccna2/pcna/cdk2 등 세포주기 유전자 농축)와 leptin+ 신경세포 클러스터. 세포주기 추론과 PCNA 염색은 3 dpa에 S기 세포의 일시적 증가(5 dpa에 기저 복귀)를 보임.
- foxm1−/− 재생체에서 Sox3+ 전구세포 비율 증가(62% → 69%)와 무질서한 다층 배열, 자가재생 분열 증가(65% → 75%), Myt1+ 신경세포 급감(30% → 14%)이 관찰됨 — 증식률과 세포자멸사 변화 없음. 따라서 Foxm1은 분열 중인 전구세포의 운명을 자가재생이 아닌 신경세포 분화 쪽으로 이동시킴.

---

## Perspective

본 연구는 척수 특이적 손상 반응을 규명하고 Foxm1에 세포주기 비의존적 재생 역할을 부여한다: 증식을 유도하기보다 Foxm1은 분열 중인 신경전구세포의 운명을 조절하여 성공적 척수 재생에 필요한 신경세포 분화를 촉진한다. 이는 *X. laevis* 1차 신경발생과 마우스 종뇌에서 보고된 Foxm1의 세포주기 의존적 역할과 대비되며, 정통 세포주기 조절자의 맥락 특이적 기능을 시사한다. 또한 신경세포 분화 자체가 재생 과정에 필요함을 강조하고, ROS를 foxm1의 상위 유도인자로 규명한다.

언급된 한계: 시퀀싱 depth/세포 수가 전구세포·신경세포 아형의 명확한 배정을 허용하지 않음; 새로 확인된 leptin+ 신경세포 집단의 재생 중 역할이 불명확; Foxm1이 (세포주기 길이와 무관하게) 운명을 편향시키는 하류 기전이 완전히 규명되지 않음. 이 비교 양서류 모델은 포유류 척수 재생이 실패하는 이유에 관한 통찰을 제공한다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
