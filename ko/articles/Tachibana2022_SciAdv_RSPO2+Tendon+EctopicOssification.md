---
tags: [2026-07, Tenocyte, RawDataAvailable]
extract: 2026-07-17
extract_file: extract/2026-07-17_p02.txt
raw_data:
  - "GEO: GSE188758, GSE188760, GSE188759"
log:
  - "2026-07-17 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# RSPO2 defines a distinct undifferentiated progenitor in the tendon/ligament and suppresses ectopic ossification

## Citation (NLM)

Tachibana N, Chijimatsu R, Okada H, Oichi T, Taniguchi Y, Maenohara Y, Miyahara J, Ishikura H, Iwanaga Y, Arino Y, Nagata K, Nakamoto H, Kato S, Doi T, Matsubayashi Y, Oshima Y, Terashima A, Omata Y, Yano F, Maeda S, Ikegawa S, Seki M, Suzuki Y, Tanaka S, Saito T. RSPO2 defines a distinct undifferentiated progenitor in the tendon/ligament and suppresses ectopic ossification. Sci Adv. 2022;8(33):eabn2138. doi:10.1126/sciadv.abn2138

**DOI:** [https://doi.org/10.1126/sciadv.abn2138](https://doi.org/10.1126/sciadv.abn2138)

---

## Background

건/인대의 이소성 연골내골화(ectopic endochondral ossification)는 반복적인 기계적 과부하나 염증에 의해 유발되며, 운동선수와 반복적으로 건을 사용하는 노동자, 그리고 후종인대골화증(OPLL) 같은 척추 인대 질환에서 흔히 관찰된다. 이 병태는 염증에서 시작되는 실패한 손상-복구 과정이 연골세포 분화·비대·골아세포 치환으로 이어지는 것으로 여겨진다. 건 줄기/전구세포(TSPC)는 Tppp3와 Pdgfra 공발현으로 정의되며 조직 복구에 기여하고, 그 일부는 lubricin(proteoglycan 4, PRG4)을 발현한다. 이전 GWAS에서 canonical WNT 신호의 분비성 활성인자인 R-spondin 2(RSPO2)가 OPLL 감수성 유전자로 확인되었고, RSPO2는 연골내골화의 초기 단계를 억제하는 것으로 알려져 있다. 그러나 건/인대 내 Prg4+ 세포의 특성과 이소성 골화와의 연관성은 밝혀지지 않았다. 본 연구는 Prg4+ TSPC 집단을 특성화하고, RSPO2가 이소성 골화를 억제하는 별개의 미분화 전구세포를 표지함을 규명한다.

---

## Key Experiment Methods

**1. 마우스 아킬레스건 천공(ATP) 이소성 골화 모델**
- 27-gauge 바늘로 아킬레스건 5곳을 천공하여 최소 침습적으로 이소성 연골내골화 유도
- Micro-CT로 골 부피 정량(ATP 후 8–12주에 골화 검출)
- SOX9, COL2, PRG4, RSPO2 면역조직화학 시간경과 분석(양성세포율)

**2. Prg4+ 세포의 단일세포 RNA-seq(scRNA-seq)**
- Prg4-CreERT2;R26-tdTomato 마우스에 ATP 후 3·4일 tamoxifen 투여, 1주 후 tdTomato+ 세포 프로파일링
- Seurat 클러스터링(10개 클러스터, 중간엽 클러스터 2차 분석 → 7개 클러스터); CytoTRACE로 분화 상태 추정
- 화상/건절단 이소성 골화 공개 데이터(GSE126060)로 검증
- FACS로 tdTomato+/tdTomato− 세포 분리하여 Prg4/Rspo2 발현 확인

**3. 클러스터 특성화 및 궤적 분석**
- 마커 프로파일링(Prg4, Rspo2, Tppp3, Pdgfra, Itga6, Tspan15, Procr, Col15a1, Fst, Runx2, Scx, Mkx, Tnmd, Col2a1, Acan, Sox9)
- GO 농축(clusterProfiler); diffusion-map 및 Monocle2 유사시간(pseudotime); scTensor 세포-세포 상호작용 분석
- SCENIC 전사인자 regulon 분석으로 상류 조절자 규명

**4. Rspo2 기능획득 및 항체 in vivo**
- Cre-의존 CAG-EGFP-Rspo2 형질전환 마우스를 Prg4-CreERT2와 교배하여 건 특이적 과발현; 골 부피와 Sox9/Col2a1 mRNA 평가
- ATP 후 복강 내 anti-RSPO2 항체 대 vehicle 투여

**5. 인간 인대세포 및 임상 검체 분석**
- 인간 일차 인대세포의 연골분화 중 RNA-seq/qRT-PCR; 공개된 인간 MSC 연골분화 데이터와 비교
- 재조합 인간 RSPO2와 LiCl(WNT 활성인자) 처리 in vitro; Alcian blue, COL2A1/ACAN, AXIN2, TOPflash 리포터
- OPLL 대 경추 척수증(CSM) 환자 척추 인대에서 RSPO2 mRNA·단백질 비교

**6. 인간 인대세포에서의 상류 신호전달**
- IL-1β 자극 ± IKK 억제제 Bay11-7085; 주기적 인장 응력 부하 ± Bay11-7085 또는 Rac1 억제제(EHT1864, NSC23766); Western blot로 IκB 인산화 확인

---

## Results

**ATP 모델의 이소성 연골내골화와 초기 연골 마커**
아킬레스건 천공 8–12주 후 Micro-CT로 이소성 골화가 검출되었다. SOX9와 COL2 발현은 1주째부터 증가하였고 COL2+ 세포율은 전 기간 sham 대비 높게 유지되어, 이소성 연골분화가 손상 후 첫 1주 내에 시작됨을 나타냈다.

**Rspo2는 별개의 Prg4+ 전구세포 클러스터를 표지**
Prg4-CreERT2;R26-tdTomato ATP 건의 scRNA-seq에서 두 개의 Prg4+ 클러스터가 확인되었다. Rspo2는 클러스터 6에서 특이적으로 발현되었고, 다른 Prg4+ 클러스터(클러스터 7)는 Rspo2가 없는 대신 연골/골화 마커(Col2a1, Acan, Sox9)를 발현하여 연골 전구세포로 규정되었다. Rspo2+ 클러스터는 day 0에는 거의 없었고 침습 후 출현하였다. FACS 분리된 tdTomato+ ATP 세포는 Rspo2, Pdgfra, Tppp3, Procr를 강하게 발현한 반면 sham 세포는 그렇지 않았다.

**Rspo2+ 클러스터는 미분화 전구세포**
클러스터 6은 줄기세포 마커(Pdgfra, Tppp3, Itga6, Tspan15, Procr)를 발현했으나 특정 분화 경향의 GO term은 없었으며, "ossification"은 연골 클러스터 7에서만 농축되었다. Diffusion-map과 Monocle2 유사시간 분석에서 Rspo2+ 클러스터는 가장 미분화된 위치에 있어, Tppp3+Pdgfra+Rspo2− 및 tenogenic/chondro-osteogenic 궤적의 상류에 위치했다.

**RSPO2는 연골분화 억제를 통해 이소성 골화를 저해**
세포-세포 상호작용 분석에서 Rspo2+ 클러스터로부터 연골 전구세포로의 Rspo2–Lgr6 쌍이 높은 순위로 예측되었다. Prg4+ 세포에서 Rspo2 과발현(CAG-EGFP-Rspo2)은 이소성 골 부피를 유의하게 감소시키고 Sox9·Col2a1 mRNA를 낮추었으며 COL2 단백질을 억제하였다. 반대로 anti-RSPO2 항체는 골량과 Sox9/Col2a1 발현을 증가시켜, RSPO2 단백질이 연골분화를 억제함으로써 이소성 연골내골화를 저해함을 확인하였다.

**RSPO2는 인간 인대세포의 연골분화를 억제하고 OPLL에서 감소**
인간 인대세포의 연골분화 과정에서 RSPO2는 AXIN2(canonical WNT 지표)와 MSC 마커 ENG/NT5E와 함께 하향조절되었다. 재조합 인간 RSPO2와 LiCl은 모두 Alcian blue 염색과 COL2A1/ACAN을 감소시키고 AXIN2와 TOPflash 활성을 증가시켜 WNT 매개 항연골분화 작용과 일치하였다. 환자에서 RSPO2 mRNA와 RSPO2+ 세포율은 OPLL 인대가 CSM 인대보다 유의하게 낮았고, RSPO2+ 세포는 COL2+ 영역과 변성 영역의 경계부에 위치했으나 골화 병변 내부에는 없었다.

**RSPO2는 염증과 기계적 부하에 의해 NF-κB를 통해 유도**
SCENIC은 Rspo2+ 클러스터의 조절자 중 Rela(NF-κB)를 확인하였다. IL-1β는 인간 인대세포에서 RSPO2를 현저히 유도했고 이는 IKK 억제제 Bay11-7085로 차단되었다. 주기적 인장 응력도 RSPO2를 유도(IκB 인산화 증가 동반)했으며, 이 유도는 Bay11-7085와 두 종류의 Rac1 억제제로 소실되어, 연골세포에서의 gremlin-1 유도와 유사한 Rac1–NF-κB 경로를 시사하였다.

---

## Perspective

본 연구는 RSPO2를 건/인대 내 별개의 미분화 Tppp3+Pdgfra+Prg4+ 전구세포 아집단을 규정하는 마커로 동정하고, RSPO2 단백질이 canonical WNT 매개 연골분화 억제를 통해 이소성 연골내골화를 저해함을 입증하였다.

첫째, Prg4+ TSPC의 이질성을 기능적으로 대립되는 두 집단 — Rspo2+ 미분화 전구세포와 Rspo2− 연골 전구세포 — 으로 분해하고, Rspo2+ 클러스터를 분화 궤적의 상류에 위치시켜 병리적 골화가 아닌 적절한 건/인대 복구에 관여함을 뒷받침한다.

둘째, 마우스(과발현·항체), 인간 인대세포, 임상 OPLL 데이터의 수렴은 RSPO2 감소와 척추 인대 질환인 OPLL의 이소성 골화를 기계론적으로 연결하여, 건/인대 전구세포 생물학을 임상적으로 중요한 병태와 잇는다.

셋째, 염증(IL-1β)과 기계적 부하가 Rac1–NF-κB를 통해 RSPO2를 유도함을 보임으로써, RSPO2를 이소성 골화를 유발하는 손상/기계적 과부하 신호 안에 위치시킨다. RSPO2가 연골분화를 지배하는 동일한 초기 연골 프로그램(Sox9, Col2a1)을 억제하므로, 이 발견은 연골 재생 및 결합조직 전구세포의 연골성/비연골성 운명 균형과도 직접 관련된다.

한계로는 인간 인대에 대한 scRNA-seq 부재(수술 검체가 드묾), 세포 수 부족으로 인한 마우스 인대 프로파일링 불가, RSPO2+ 집단의 기원과 최종 운명 미규명이 있으며, 기여 인자로서의 노화도 검토되지 않았다. 그럼에도 본 연구는 건/인대 항상성 이해를 진전시키고 RSPO2/WNT 신호를 이소성 골화의 치료 축으로 제안한다.


## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- GEO: GSE188758, GSE188760, GSE188759

**본문에 인용된 기타 accession (외부·재사용 데이터):**
- GEO: GSE126060


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-17*
