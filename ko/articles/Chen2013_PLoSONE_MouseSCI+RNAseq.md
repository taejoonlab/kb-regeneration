---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
---

# RNA-Seq Characterization of Spinal Cord Injury Transcriptome in Acute/Subacute Phases: A Resource for Understanding the Pathology at the Systems Level

## Citation (NLM)
Chen K, Deng S, Lu H, Zheng Y, Yang G, Kim D, Cao Q, Wu JQ. RNA-Seq Characterization of Spinal Cord Injury Transcriptome in Acute/Subacute Phases: A Resource for Understanding the Pathology at the Systems Level. PLoS One. 2013;8(8):e72567. doi:10.1371/journal.pone.0072567

**DOI:** [https://doi.org/10.1371/journal.pone.0072567](https://doi.org/10.1371/journal.pone.0072567)

---

## Background

척수 손상(SCI)은 효과적인 치료법이 없는 심각한 신경학적 질환으로, 미국에서 약 30만 명이 SCI를 안고 살아가며 연간 약 1만 1천 건의 신규 사례가 발생한다. 일차 기계적 외상 후 이차 손상 연쇄반응이 추가적인 조직 손실과 기능 장애를 유발한다. 기존의 분자 연구는 대개 소수의 유전자만 조사하거나 해상도, 동적 범위, 정확도가 제한적인 마이크로어레이를 사용해, SCI 병리에 대한 포괄적 시스템 수준의 관점을 제공하지 못했다.

저자들은 RNA-Seq을 적용하여 마우스 타박상 SCI 후 급성기(2일)와 아급성기(7일)의 시간적 전사체 변화를 규명하고, 핵심 경로·유전자·스플라이싱 이형체를 식별하며, SCI 연구 공동체를 위한 시스템 기반 분석 틀과 참조 자원을 구축하고자 한다.

---

## Key Experiment Methods

1. Infinite Horizons impactor(60 kdyn)를 이용한 암컷 C57BL/6J 마우스의 중등도 T9 타박상 SCI. 가짜 대조군은 척추후궁절제술만 시행. 손상 중증도는 eriochrome cyanine 조직학과 Basso Mouse Score 운동 검사로 확인.
2. 대조군(가짜), 2일(2D), 7일(7D)의 손상 진앙 조직에서 polyA 선택 RNA의 RNA-Seq(paired-end, Illumina HiSeq); 리드를 Tophat/Bowtie로 마우스 mm9에 매핑하고 Cufflinks로 조립·정량(FPKM).
3. 위양성/위음성 비율 곡선을 통한 FPKM 신뢰도 임계값 결정(임계값 0.1 FPKM); 2배 이상 변화 및 t-검정 p < 0.05로 차등발현 판정.
4. 시간적 발현의 c-means(mfuzz) 클러스터링과 반복 샘플의 비지도 계층적 클러스터링; 선행 타박상 SCI 마이크로어레이 데이터셋(GEO GSE5296)과 비교.
5. Ingenuity Pathway Analysis(IPA)와 Gene Set Enrichment Analysis(GSEA, MSigDB)를 이용한 기능/경로 분석; 관련성 지수(RI = |log(fold change)| x 연결 수)로 후보 유전자를 우선순위화하는 시스템 기반 네트워크 구축, 약물유전체(약물) 정보 통합.
6. 대체 스플라이싱/이형체 발현 분석 및 선정 유전자(C3AR1, CCL7, CD22, CD36, CLEC6A, FCER1G, FCGR2B, Il7r, LPL, MSR1, PTX3)의 qRT-PCR 검증.

---

## Results

- RNA-Seq은 2D에서 2,832개, 7D에서 4,207개의 차등발현 유전자를 검출했다(1,802개 공유). 7D에는 하향조절 유전자가 더 많았고(2,579개 vs. 1,187개), 이는 신경세포 사멸 증가에 기인한다. 상향조절 유전자는 "염증 반응", 하향조절 유전자는 "신경계 발생"에 농축되었다.
- 두 시점 모두에서 상위 농축 기능 범주는 염증 반응, 신경학적 질환, 세포 사멸과 생존, 신경계 발생이었으며, 상위 표준 경로는 LXR/RXR 활성화, 죽상경화증 신호전달, TREM1 신호전달을 포함했다. 글루타메이트 수용체 신호전달(대부분 하향조절)은 7D에서만 특이적으로 나타났다.
- RNA-Seq은 비교 마이크로어레이 데이터셋보다 높은 민감도와 넓은 동적 범위를 보여 더 많은 차등발현 유전자를 검출했다.
- 대체 스플라이싱은 광범위했고(유전자당 최대 12개 이형체; 약 99%가 1~5개), 10,327개 이형체가 2배 이상 변화했다. 예: Spp1(osteopontin)은 전체적으로 증가했으며 이형체 NM_009263이 주도했다. Morf4l2는 "이형체 전환"을 보여 손상 후 NM_001168230이 우세해졌다.
- 시스템 틀은 알려진 SCI 유전자(Il6, Tnf, Il1b, Ccl2)를 상위에 순위화하여 접근법을 검증했고, 약물 정보가 있는 덜 연구된 후보(Cd36, Lpl, C3ar1, Msr1)를 부각하여 qRT-PCR로 확인했다.
- 세포유형 마커 분석은 대식세포 동역학을 보였다(M1 마커 Cd86는 7D에 증가, M2 마커 Arg1은 2D에 증가; M1 유전자 집합은 7D에서 더욱 농축). 이는 아급성기에 M1/M2 비율 상승을 시사한다. 반응성 별아교세포 마커 Gfap, Lcn2, Serpina3n이 상향조절되었다(Lcn2/Serpina3n은 2D에 더 높음). OPC(Cspg4/Ng2), 신경줄기세포(Nestin), 내피세포(Pecam-1/Cd31), 조혈줄기세포(Cd34) 마커도 프로파일링되었다.

---

## Perspective

본 연구는 급성기 및 아급성기 마우스 타박상 SCI의 게놈 전반, 시스템 수준 참조 전사체를 제공하며, RNA-Seq이 마이크로어레이를 능가하고 약물 특이성에 유용한 이형체 수준 해상도를 추가함을 입증한다. 차등발현, 네트워크 연결성, 세포 위치, 약물유전체를 결합한 시스템 기반 우선순위화 틀은 알려진 SCI 유전자를 성공적으로 회복하고 새로운 후보(예: Cd36, Lpl, C3ar1, Msr1)와 경로(LXR/RXR, 죽상경화증 신호전달)를 기능 검증 대상으로 제안한다. 한계로는 혼합 세포유형의 전조직 프로파일링(세포유형 귀속 제한), 손상 후 단 두 시점, 풀링된 생물학적 반복, 알려진 전사체로의 분석 제한이 있다. 데이터셋과 틀은 가설 생성 자원으로 제공되며, 저자들은 이차 손상 감소 및 재생 촉진을 위한 새로운 기전과 치료 표적을 규명하기 위해 우선순위 유전자를 동물 모델에서 검증할 계획을 언급한다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
