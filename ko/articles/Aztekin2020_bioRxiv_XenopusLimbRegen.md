---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
raw_data:
  - "ArrayExpress: E-MTAB-9104"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Secreted inhibitors drive the loss of regeneration competence in Xenopus limbs

## Citation (NLM)
Aztekin C, Hiscock TW, Gurdon JB, Jullien J, Marioni JC, Simons BD. Secreted inhibitors drive the loss of regeneration competence in Xenopus limbs. bioRxiv. 2020 Jun 2. doi:10.1101/2020.06.01.127654

**DOI:** [https://doi.org/10.1101/2020.06.01.127654](https://doi.org/10.1101/2020.06.01.127654)

---

## Background
양서류 사지 재생은 특화된 상처 표피(apical-epithelial-cap, AEC)에 의존하며, 이 조직의 부재가 포유류를 포함한 고등 척추동물의 재생을 막는 원인으로 가설화되어 왔다. AEC는 사지 발생 시 나타나는 apical-ectodermal-ridge(AER)와 유사하다고 여겨지는데, 두 조직 모두 원위부 끝에서 Fgf8을 발현하고 근위-원위 축 성장을 지지하며 하부 중배엽의 증식을 유도해 재생 아체(blastema)를 형성한다.

Xenopus laevis 올챙이는 발생 과정에서 점진적으로 사지 재생 능력을 잃으며, 이는 특화된 상처 표피 형성 능력 상실과 일치한다. NF ~52-54기에는 완전 재생(competent), NF ~55-57기에는 부분 재생(restricted, 손가락 결손), NF ~58기 이후에는 단순 상처 치유 또는 무패턴 spike만 형성(incompetent)된다. 재생 능력은 성숙한 연골/골형성 세포가 많은 근위부 절단에서 더 감소한다. 본 연구는 상처 표피 형성의 세포·분자적 결정 요인과 그 실패 원인을 규명하고자 하였다.

---

## Key Experiment Methods
1. 발생 중 온전한 뒷다리(NF ~52, ~54, ~56)와, 절단 후 5일(5 dpa)의 competent/restricted/incompetent 단계 사지 및 대측 대조군에 대한 단일세포 RNA-seq(10X Genomics v3). 총 42,348개 세포, 세포주기 보정, 약 60개 클러스터(대화형 아틀라스 제공).
2. AER 세포(Fgf8+ 표피세포) 주석화 및 재생 조건별 AER 세포 존재량 비교; 꼬리 재생의 regeneration-organising cell(ROC)과의 비교.
3. Ex vivo 재생 사지 explant 배양으로 원위부 vs 근위부 AER(Fgf8) 형성 관찰 및 소분자 억제제(FGF/SU5402, BMP/LDN193189, WNT/ICRT3, NOTCH/DAPT)와 TGF-β를 통한 신호전달 요구성 검증.
4. EdU 도입 실험으로 AER 세포가 세포분열을 통해 형성되는지 검증; 기저 표피의 Lgr5.S / Fgf8.L 궤적에 대한 HCR in situ hybridization.
5. Competent와 incompetent explant 간 공배양 및 조건화 배지 실험, anti-NOGGIN 항체 차단; NOGGIN 및 BMP4 첨가 실험.
6. FGF10 bead / 재조합 FGF10 처리 및 FGFR 억제를 통한 연골형성과 AER 형성 효과 검증(FGF10 + anti-NOGGIN 병용 포함).

---

## Results
- AER 세포(Fgf8+ 표피세포)는 발생과 절단 후 재생에서 전사체·형태학적으로 유사한 특징을 공유하며, 절단면에서의 존재량이 재생 결과와 강하게 상관한다(competent에서 풍부, restricted에서 제한적, incompetent에서 거의 부재).
- 손상 유도 중배엽 가소성(Grem1, Shh, Msx1, Fgf10 등 원위 전구세포 유전자 및 연골형성 Sox9를 상향조절하는 섬유아세포 아집단)은 AER 세포 존재량과 함께 변화한다.
- AER 세포 형성은 FGF, BMP, WNT, TGF-β, NOTCH 신호전달의 활성화를 요구하며, 이들 중 하나라도 억제하면 explant에서 Fgf8 형성이 차단된다.
- 새로 형성된 AER 세포의 약 40%만 EdU 양성으로, 대부분 세포분열 없이 형성됨을 시사한다. Lgr5.S 이후 Fgf8.L의 단계적 궤적을 통해 기저 표피세포가 AER 세포로 직접 전환될 수 있다.
- Incompetent explant에서 분비된 인자가 competent explant의 AER 형성을 차단하며(공배양 및 조건화 배지), 이 억제는 anti-NOGGIN 항체로 회복된다. Incompetent 단계에서 증가하는 연골형성 계열 세포는 높은 NOGGIN과 기타 BMP/WNT 길항제를 발현한다.
- FGF10은 연골형성을 억제하고 NOGGIN 상류에서 작용한다. FGF10 단독으로는 근위부 AER 유도에 불충분하지만 anti-NOGGIN과 병용 시 근위부 근처에 이소성 Fgf8을 유도한다. BMP4는 연골형성을 촉진하고 AER 형성을 차단한다.

---

## Perspective
본 연구는 단일세포 프레임워크로 사지 재생 분야의 상충된 결과들을 통합하며, 연골형성 진행이 FGF10 하류에서 상처 표피(AER) 형성을 길항하는 분비 억제 인자(특히 NOGGIN)를 축적시켜 재생 능력 상실을 유도한다는 모델을 제안한다. 이는 세포외 환경 또는 연골형성 조작이 비재생성 고등 척추동물의 재생 잠재력 회복에 기여할 수 있음을 시사한다. 저자들은 포유류 재생의 추가 장벽(반흔, 복잡한 면역반응)과, 재생 능력이 있는 도롱뇽이 이러한 억제 신호를 어떻게 회피하는지(예: AER 신호의 중배엽 vs 표피 강화)에 대한 미해결 질문을 한계로 언급한다. 프리프린트로서 동료심사를 거치지 않았다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- ArrayExpress: E-MTAB-9104


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
