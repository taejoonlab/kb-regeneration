---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p08.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# RNA-seq of spinal cord from nerve-injured rats after spinal cord stimulation

## Citation (NLM)
Stephens KE, Chen Z, Sivanesan E, Raja SN, Linderoth B, Taverna SD, Guan Y. RNA-seq of spinal cord from nerve-injured rats after spinal cord stimulation. Mol Pain. 2018;14:1744806918817429. doi:10.1177/1744806918817429

**DOI:** [https://doi.org/10.1177/1744806918817429](https://doi.org/10.1177/1744806918817429)

---

## Background

척수자극술(spinal cord stimulation, SCS)은 약물치료에 반응하지 않는 신경병성 통증에 널리 사용되는 신경자극 치료로, 관문조절이론(gate-control theory)에 기반하며 경막외 리드를 통해 등쪽 기둥(dorsal column)의 저역치 Aβ 섬유를 활성화한다. SCS는 척수 억제 기전 및 신경전달물질 방출 변화와 연관되지만, 그것이 일으키는 억제·흥분 변화의 분자적 조절은 잘 이해되지 않았으며, 기존 근거는 SCS가 광범위하고 지속적인 유전자 발현 변화를 유도함을 시사했다.

본 연구는 신경병성 통증 유지기 동안 반복적 통상 SCS를 받은 쥐의 요추 척수에 대해 최초의 RNA-seq 분석을 수행하여, 차등 발현 유전자와 유전자 네트워크를 규명하고 SCS 효능 향상을 위한 새로운 치료 표적을 제안하고자 했다.

---

## Key Experiment Methods

1. 성체 수컷·암컷 Sprague-Dawley 쥐의 좌측 좌골신경 만성압박손상(CCI); von Frey 발 회피 역치(PWT) 검사로 기계적 과민성 확인.
2. T13-L1 수준에 경막외 이식한 소형 quadripolar 전극을 통한 반복적 통상 SCS(CCI+SCS) 또는 무처치(CCI only)로 무작위 배정; SCS는 50 Hz, 운동역치의 80%, 0.2 ms, 정전류, 세션당 120분으로 연속일에 걸쳐 시행.
3. 마지막 SCS 세션 후 1~2시간 이내에 동측 L4-L6 요추 척수 채취; DNase 처리를 포함한 총 RNA 추출 및 품질 평가.
4. 가닥 특이적 poly(A) RNA-seq 라이브러리 제작 및 Illumina HiSeq4000에서 paired-end 150 bp 시퀀싱(샘플당 약 3,360만 리드).
5. HISAT2로 쥐 유전체(rn6) 정렬, featureCounts 정량, DESeq2 차등발현 분석(FDR < 0.05, 성별 상호작용 항 포함), ToppGene 유전자 온톨로지 농축, IUPHAR/Guide to Pharmacology 데이터베이스로 유전자 클래스 배정.

---

## Results

- 각 SCS 세션은 기계적 PWT를 유의하게 증가시켰고(60~90분에 최대 억제, 중단 후 30분 이내 기저치 복귀), 통증 억제는 운동역치와 양의 상관을 보였다.
- CCI only 대비 CCI+SCS 척수는 1,113개 유전자(7.9%)를 차등 발현했다: 785개 상향, 328개 하향; 343개는 수송체·효소·GPCR·이온채널·촉매수용체·전사인자로 분류 가능했다.
- 상향 유전자는 면역 관련 생물학적 과정에 강하게 농축되었으며, 상위 상향 전사체로 C3, Adgre1, Cd4, Il1b, Cxcl13, Csf1r와 성상세포 표지자(Gfap, Ccl2) 및 활성 미세아교세포 표지자(Cd68, Itgam), toll-like receptor가 포함되어 비신경/면역 활성화 증가를 나타냈다.
- 하향 유전자는 시냅스 전달, 시냅스 조직화, 뉴런 돌기 성장에 농축되었고, 분자기능 농축은 serine/threonine 키나아제 활성과 scaffold 단백질 결합을 강조했다.
- SCS는 NMDAR/AMPAR 국소화를 안정화하는 주요 시냅스후 밀도(PSD) scaffold 유전자(Dlg4/PSD-95, Dlgap1, Dlgap3, Shank1, Shank3, Grip2)를 억제했다. GABA 수송체 유전자 Slc6a11(GAT3)도 하향 조절되어, 시냅스 내 GABA 가용성을 높이고 PSD를 불안정화하여 흥분성 전달을 약화시키는 기전을 시사했다.
- 성별 분석: 수컷은 149개, 암컷은 858개 유전자를 차등 발현(FDR < 0.05)했으나, 두 성별 모두 유사한 GO 과정(면역 상향, 시냅스 하향)을 보였다. 성별 간 유의하게 다른 유전자는 소수여서 데이터를 통합했다.

---

## Perspective

반복적 통상 SCS 후 척수에 대한 이 최초의 RNA-seq 연구는, SCS가 기계적 과민성을 감소시킴에도 역설적으로 면역/교세포 활성화 유전자의 추가 상향과 동시에 PSD scaffold 유전자 억제와 연관됨을 보여준다. 저자들은 시냅스후 밀도의 불안정화(NMDAR/AMPAR 응집 감소)와 시냅스 GABA 가용성 증가가 SCS 매개 통증 억제의 새로운 기전일 수 있으며, SCS 효능 향상을 위한 전사·후성유전 표적 후보를 제공한다고 제안한다. 한계로는 작은 표본 크기(SCS 쥐 5마리, 라이브러리당 n=1), 유전자 수 차이에도 성별 통합 분석, 원위 분절의 등쪽/배쪽 척수 통합 채취, 그리고 유전자 발현 연관성의 상관적(비인과적) 특성이 있으며, 자극 전극에서 원위 분절의 전사 변화를 일으키는 기전은 여전히 불명확하다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
