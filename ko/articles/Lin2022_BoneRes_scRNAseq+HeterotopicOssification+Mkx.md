---
tags: [2026-06, Chondrocyte, RawDataAvailable]
extract: 2026-06-07
extract_file: extract/2026-06-07_p01.txt
raw_data:
  - "GEO: GSE102931"
log:
  - "2026-06-07 · create · DeepSeek V4 Flash (OpenCode Go)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Single cell analysis reveals inhibition of angiogenesis attenuates the progression of heterotopic ossification in Mkx−/− mice

## Citation (NLM)

Lin J, Yang Y, Zhou W, Dai C, Chen X, Xie Y, Han S, Liu H, Hu Y, Tang C, Bunpetch V, Zhang D, Chen Y, Zou X, Chen D, Liu W, Ouyang H. Single cell analysis reveals inhibition of angiogenesis attenuates the progression of heterotopic ossification in Mkx−/− mice. _Bone Res._ 2022 Jan 3;10(1):4. doi: [10.1038/s41413-021-00175-9](https://doi.org/10.1038/s41413-021-00175-9).

---

## Background

건 이소성 골화(tendon heterotopic ossification, HO)는 건 조직 내에서 뼈가 형성되는 질환으로, 일상생활에 심각한 지장을 초래한다. 현재 HO의 임상 치료는 물리치료, 비스테로이드성 소염제, 이소성 뼈의 수술적 제거에 국한되어 있으며, 빈번한 합병증과 높은 재발률을 보인다. Mohawk(MKX)는 건 특이적 전사인자로, Mkx 결손 마우스와 랫드에서 자발적 건 HO가 발생함이 보고되었다. 그러나 HO 발병의 세포 및 분자기전, 특히 다양한 건 resident 세포 아집단의 기여도와 혈관신생(angiogenesis)의 역할은 충분히 규명되지 않았다. 본 연구는 Mkx−/− 마우스를 건 HO 모델로 활용하여 단일세포 수준에서 HO의 병리기전을 규명하고, 혈관신생 억제가 HO 진행을 attenuate할 수 있는지 검증하고자 하였다.

---

## Key Experiment Methods

**1. 인간 HO 검체 분석**

- 정상인 및 HO 환자의 건에서 H&E 염색, OCN 및 MKX 면역형광으로 MKX 발현 평가

**2. Mkx−/− 마우스 HO 모델 특성화**

- WT 및 Mkx−/− 마우스의 Achilles, patellar, tail tendon을 micro-CT 및 SOFG 염색으로 HO 표현형 확인
- 4주령 tail tendon에서 bulk RNA-seq(DESeq2, FDR<0.05, |log2FC|>1), GO 및 KEGG 분석

**3. 단일세포 RNA 시퀀싱(scRNA-seq)**

- 4주령 WT 및 Mkx−/− tail tendon에서 Fluidigm C1 system(HT IFCs)으로 486개 세포 캡처, 466개 세포 QC 통과
- Seurat alignment workflow(SAW)로 통합 분석, t-SNE 시각화, unsupervised graph-based clustering
- Monocle 2로 pseudotime trajectory 분석

**4. 유전자 세트 점수 분석**

- Seurat AddModuleScore function으로 조골세포 발달, 골화, 골광화 관련 유전자 세트 점수 계산

**5. 혈관 분석**

- CD31 면역형광으로 혈관 밀도 정량
- SOFG 염색으로 혈관 확인

**6. BIBF1120 혈관신생 억제 실험(Mkx−/− 변성 HO 모델)**

- 생후 14일부터 3주간 Mkx−/− 마우스 Achilles tendon에 BIBF1120(4 µg) 또는 vehicle를 주 3회 피하 주입
- 8주령 및 12주령에 micro-CT, SOFG 염색, CD31/OCN 면역형광으로 골화 및 혈관 평가

**7. BIBF1120 외상 유도 HO 모델(랫드)**

- 8주령 수컷 랫드 Achilles tendon에 27G needle로 25회 천자(ATP)
- 손상 3일 후 BIBF1120(40 µg) 또는 vehicle를 주 3회 피하 주입, 3주간
- 9주 및 12주 후 micro-CT, 조직학, 면역형광 분석

**8. BIBF1120 부작용 평가**

- BrdU assay로 세포 증식 평가
- RNA-seq로 전사체 프로파일 비교
- TSPC marker(Mcam, Thy1, Nes) 및 건 marker(Scx, Mkx, Egr1, Tnmd, Tnc, Col1a1) 발현 분석

---

## Results

**인간 HO에서 MKX 억제** 정상인 건에서 MKX 단백질이 검출되었으나, HO 환자 건에서는 MKX 발현이 현저히 감소하였다. OCN+ 조골세포가 HO 부위 및 접합부에 존재함을 확인하였다.

**Mkx 결손으로 건 HO 발생** Mkx−/− 마우스의 Achilles, patellar, tail tendon 모두에서 이소성 뼈 형성이 명확히 관찰되었다. SOFG 염색에서 Mkx−/− 건은 proteoglycan 축적(적색 염색)과 원형 핵을 가진 연골세포가 풍부하여 연골 병변 및 연골내 골화를 확인하였다.

**Bulk RNA-seq: 혈관신생 및 골연골형성 유전자 상승** Mkx−/− 건에서 393개 유전자 상승, 283개 유전자 하조절되었다. 상승 유전자는 cell adhesion, angiogenesis, bone regeneration, ossification에, 하조절 유전자는 collagen fibril organization, ECM organization, tendon formation에 풍부하였다. KEGG 분석에서 Wnt, PI3K-Akt, Rap1 pathway가 상조되었으며, Ctgf, Mmp2, Pecam1, Vegfa 등 혈관신생 관련 유전자와 Sox9, Runx2, Spp1, Postn 등 골연골형성 유전자가 모두 상승하였다.

**단일세포 분석: 3개 세포 유형 동정** WT 및 Mkx−/− 건에서 TPC(tendon progenitor cells, Cd44+/Thy1+/Ly6a+/Fstl1+), TB(tenoblasts, Itm2a+), TC(tenocytes, Col11a2+/Col1a1+/Sparc+/Tnmd+/Fmod+)의 3개 세포 클러스터가 동정되었다. 세포 구성 비율은 WT와 Mkx−/− 간 차이가 없어, 세포 집단 이동이 HO 기전이 아님을 확인하였다.

**Pseudotime 분석: Mkx−/− 세포에서 골연골형성 유전자 조기 활성화** TPC→TB→TC 분화 궤적에서 tenogenesis marker(Ly6a, Tppp3→Itm2a, Lgals3→Tnmd, Col1a1) 발현 패턴은 WT와 Mkx−/−가 유사하였다. 그러나 Spp1, Ogn, Mgp, Comp 등 골연골형성 marker가 Mkx−/− 세포에서 WT보다 더 일찍, 더 높게 발현되었다. 조골세포 발달 관련 유전자 점수가 Mkx−/− TPC에서 유의하게 증가하여, HO가 TPC 단계부터 골연골형성 프로그램의 과도한 활성화와 관련됨을 보였다.

**Mkx−/− 건에서 혈관신생 유전자 및 혈관 증가** TPC, TB, TC 모든 세포 유형에서 angiogenesis 관련 GO term이 풍부하였다. Hif1a는 Mkx−/− TC에서, Thbs1은 Mkx−/− TPC 및 TC에서 높게 발현되었다. SOFG 염색 및 CD31 면역형광에서 Mkx−/− 건의 혈관이 증가함을 확인하였다.

**BIBF1120이 Mkx−/− HO attenuate** BIBF1120 처리 군에서 8주 및 12주 모두 이소성 골 부피가 유의하게 감소하였다. SOFG 염색에서 vehicle 군은 큰 cancellous bone과 골수를 보였으나 BIBF1120 군에서는 감소하였다. CD31+ 혈관 및 Ocn+ 조골세포 수가 BIBF1120 군에서 유의하게 감소하였다.

**BIBF1120이 외상 유도 HO 모델에서도 효과** 랫드 ATP 모델에서 BIBF1120 처리는 9주 및 12주 후 HO 형성 및 골 부피를 유의하게 감소시켰다. CD31+ 혈관 및 Ocn+ 조골세포도 감소하였다.

**BIBF1120의 건 항상성에 대한 영향 최소화** BrdU 양성 세포 비율, 증식 marker(Mki67, Pcna, Mcm2) 발현, 전사체 프로파일이 BIBF1120과 vehicle 군 간 유사하였다. TSPC marker 및 건 canonical marker 발현도 차이가 없어, BIBF1120이 건 세포 증식 및 분화에 미치는 부작용이 최소화됨을 확인하였다.

---

## Perspective

본 연구는 Mkx−/− 마우스 건 HO 모델에서 단일세포 분석을 통해 HO 진행이 TPC 단계부터의 골연골형성 유전자 과도한 활성화와 모든 세포 유형에서의 혈관신생 프로그램 활성화와 밀접하게 연관됨을 규명하였다. 특히 혈관신생 억제제 BIBF1120이 변성 HO(Mkx−/−) 및 외상 유도 HO(랫드 ATP) 모델 모두에서 이소성 골형성과 혈관형성을 유의하게 억제하면서도 건 항상성에는 영향을 최소화함을 보여, HO 치료제로서의 임상 적용 가능성을 제시하였다.

BIBF1120은 Vegfr, Pdgfr, Fgfr를 표적으로 하는 triple vascular kinase 억제제로, 혈관 내피세포, 주위세포, 평활근세포의 전혈관신생 신호전달을 억제한다. 건 생물학에서 Fgf/Fgfr 및 Pdgf/Pdgfr 신호는 건 성장과 항상성에 중요하므로, BIBF1120의 pan-inhibition이 주변 건 세포에 부작용을 줄 우려가 있었으나, 본 연구에서는 증식 및 주요 marker 발현에 영향이 없어 비교적 특이적인 HO 억제 기능을 보였다.

향후 연구로는 TPC의 정확한 운명 추적(lineage tracing), 고처리량 단일세포 방법을 통한 내피세포/주위세포/평활근세포 등 혈관 관련 세포군 포괄적 분석, 그리고 BIBF1120 외 더 특이적인 혈관신생 표적 치료제 개발이 필요하다. 본 연구는 건 HO의 병리기전 이해와 새로운 치료 접근법 개발에 중요한 기초를 제공한다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- GEO: GSE102931


---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*