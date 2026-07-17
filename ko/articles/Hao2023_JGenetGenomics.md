---
tags: [2026-06, Chondrocyte]
extract: 2026-06-06
---

# Single-cell transcriptomic analysis identifies a highly replicating Cd168+ skeletal stem/progenitor cell population in mouse long bones

## Citation (NLM)

Hao RC, Li ZL, Wang FY, et al. Single-cell transcriptomic analysis identifies a highly replicating Cd168+ skeletal stem/progenitor cell population in mouse long bones. _J Genet Genomics._ 2023;50(8):597-607. doi: [10.1016/j.jgg.2023.04.004](https://doi.org/10.1016/j.jgg.2023.04.004).

---

## Background

골격 줄기/전구세포(SSPC)는 골격계 내에서 골형성과 연골형성 능력을 가진 조직 특이적 줄기세포로, 골 발생, 항상성 유지 및 재생에 중요한 역할을 한다. 그러나 SSPC 집단은 시공간적 분포와 재생 능력에 있어 높은 이질성을 보이며, 이에 대한 통합적 이해는 아직 부족하다. 최근 단일세포 RNA 시퀀싱(scRNA-seq) 기술의 발전으로 다양한 SSPC 집단의 특성이 밝혀지고 있으나, 발생 전 과정(배아 사지싹에서 성체 장골까지)을 아우르는 통합 분석은 수행된 바 없었다. Cd168(hyaluronic acid-mediated motility receptor, RHAMM/HMMR로도 알려짐)은 세포 증식, 형질전환, 이동을 촉진하는 것으로 알려져 있으며, 최근 연구에서 중간엽 줄기세포(MSC) 표면에서 발현되어 연골형성에 기여하는 것으로 보고되었다. 본 연구는 scRNA-seq 통합 분석을 통해 마우스 장골에서 높은 증식능을 가진 새로운 Cd168+ SSPC 집단을 발굴하고, 이들의 발생학적 분포와 골 재생에서의 역할을 규명하고자 하였다.

---

## Key Experiment Methods

**1. scRNA-seq 데이터 통합 분석**
- 공개 데이터셋(GSE154247 등) 활용: 마우스 사지싹(E11.5, E13.5, E15.5, E18.5) 및 생후 장골 간질세포(3주, 12주령)
- Harmony 알고리즘으로 배치 효과 보정; 총 14,116개 단일세포 선별
- Seurat unsupervised clustering으로 10개 세포 클러스터 식별
- Monocle3로 분화 궤적 재구성; SCENIC으로 전사인자 활성 분석
- CellCycleScoring 함수로 세포주기 단계(G1/G2M/S) 및 증식 점수 산출

**2. 세포 아집단 특성화**
- 12개 골연골 계통 세포(OCLC) 하위클러스터 분석
- LBM(사지싹 중간엽), 연골세포(chondrocyte, 5개 클러스터: 배아 연골세포, 증식성 OCP, Prg4+ 관절연골세포, Prkg2+ 성장판 연골세포, Col10a1+ 전비대 연골세포), Lepr+ MSCs, 조골세포 계통(2개 클러스터)으로 주석
- Cd168+ 증식성 골연골 전구세포 집단 발굴

**3. 유세포 분석(Flow cytometry)**
- 12주령 성체 마우스 장골에서 기계적/효소적 소화 후 세포 분리
- Cd45⁻Ter119⁻Cd31⁻Cd168⁺ 세포 비율 측정

**4. 면역형광염색 및 조직학**
- Safranin O/Fast Green 염색으로 연골 형태 관찰
- anti-HMMR, anti-SOX9, anti-RUNX2, anti-Collagen type 2 항체를 사용한 다중 면역형광염색
- 배아(E11.5, E13.5, E15.5, E18.5) 및 생후(3주, 12주) 시점의 시공간적 단백질 발현 분석
- 골절 치유 모델: PFD(post-fracture day) 7, 14, 21일째 가골(callus) 내 Cd168+ 세포 분포 확인

**5. 골절 치유 모델**
- 10주령 암컷 마우스 좌측 대퇴골에 횡방향 완전 골절 유도
- 골수강 내 K-강선 고정 후 미세가위로 골절 생성
- PFD14에서 비조혈 간질세포(Cd45⁻Ter119⁻) 분리 및 scRNA-seq 분석
- Partition-based graph abstraction(PAGA) 분석으로 클러스터 간 연결성 평가

---

## Results

**마우스 장골 발생의 단일세포 지도 구축** 14,116개 세포의 통합 분석을 통해 10개 세포 클러스터가 식별되었다: 사지싹 중간엽세포(LBM, Prrx1/Osr2), 연골세포(Acan/Sox9), 골연골 전구세포(OCP, Runx2/Sp7/Alpl), 내피세포, 혈관주위세포, MSC(Lepr/Pdgfra), 정단외배엽능선(AER, Fgf8), 골격근세포, 면역세포, 상피세포.

**OCLC 이질성 및 발생 궤적** 연골 계통 세포(OCLC)를 중심으로 한 재분석에서 12개 클러스터가 확인되었다. 발생 시점별 클러스터 분포 변화를 추적한 결과, 조기 사지싹 단계(E11.5)에서는 중간엽세포가 우세했으나, 연골 응축(precartilaginous condensation)이 진행되면서 연골세포로 분화하고, 성장판 비대 연골세포를 거쳐 장골 종적 성장에 기여했다. Lepr+ MSC는 E11.5부터 출현하여 출생 후 크게 확장되며 성체 골수 주요 SSPC 집단이 되었다. Monocle3 궤적 분석은 골형성(osteogenesis)과 연골형성(chondrogenesis)의 두 가지 운명 분기점을 재현했다.

**Cd168+ 증식성 SSPC 집단 발굴** 세포주기 분석 결과, 초기 사지싹 세포와 골연골 줄기/전구세포에서 증식 점수가 높았으며, 특히 다른 골연골 전구세포보다도 더 높은 증식 점수를 가진 활발히 증식하는 세포 집단이 확인되었다. 해당 집단의 마커 유전자로서 Cd168이 발굴되었다. GO 분석 결과 이 집단은 골격계 발생, 중간엽, 연골, 골 발생 순차적 과정에 관여하는 유전자들이 농축되어 있었다.

**Cd168+ 세포의 시공간적 분포** 유세포 분석에서 Cd45⁻Ter119⁻Cd31⁻Cd168⁺ 세포는 장골 전체 방출 세포의 0.16–0.18%를 차지했다. 면역형광염색 결과, Cd168+ 세포는 E11.5 사지싹 중간엽 응축부, E13.5 연골 응축부, E15.5 1차 골화중심, E18.5 관절면과 골간단(diaphysis)에 분포했다. 출생 후에는 관절 연골 표층과 성장판에서 발견되었으며, 골막이나 내골막(endosteum)에서는 관찰되지 않았다. Cd168은 Sox9 및 Runx2와 공동발현되어 골연골형성 능력을 시사했다.

**골절 치유에서 Cd168+ 세포의 역할** 골절 데이터셋 분석 결과, PFD14에서 연골세포, 섬유아세포, OCP가 유의하게 증가한 반면 Lepr+ MSC는 감소했다. OCP1 클러스터는 발생 데이터셋의 증식성 골연골 집단과 특이적으로 상관관계를 보였다. 골절 치유 과정에서 Cd168 발현이 증가했으며, Cd168은 Sox9 및 Runx2와 공동발현되었다. PAGA 및 분화 궤적 분석(RNA velocity, CytoTRACE)은 Cd168+ 골연골 전구세포가 재생된 연골세포 집단으로 분화함을 시사했다. 면역형광염색에서 PFD7과 PFD14의 골절 가골 중심부에서 Cd168+ 세포가 Sox9/Runx2와 함께 검출되어 골절 치유 과정에 직접 관여함을 확인했다.

---

## Perspective

본 연구는 배아 사지싹에서 성체 장골까지 마우스 장골 발생 전 과정을 아우르는 최초의 통합 scRNA-seq 분석을 수행하여, 골연골 계통 세포의 시공간적 이질성과 발생 궤적을 단일세포 수준에서 규명했다. 특히 세포주기 분석 기반 전략을 통해 **Cd168**을 고증식성 골연골 전구세포의 새로운 표면 마커로 발굴하고, 이 집단이 배아 및 생후 장골 발생뿐만 아니라 골절 치유 과정에서 연골세포로 분화하여 기여함을 증명했다.

Cd168+ SSPC의 발견은 기존에 알려진 골수(Lepr+), 성장판 하방(Grem1+/PTHrP+), 골막(aSMA+/Ctsk+) SSPC 집단과는 구별되는 새로운 SSPC 집단을 제시하며, 연골 관절 표층과 성장판(proliferative zone)에 위치한 특성상 관절 연골 항상성 및 장골 성장 조절에 중요한 역할을 할 가능성이 있다.

향후 과제로는 (1) Cd168-CreERT2 계통추적 마우스 모델을 통한 세포 운명 매핑 및 자가재생 능력 검증, (2) FACS 분리 Cd168+ 세포의 이식 및 분화 기능 분석, (3) 다양한 병리 모델(골관절염, 골다공증)에서 Cd168+ SSPC의 역할 규명, (4) 사지싹 중간엽 LBM2 집단의 특성 규명이 필요하다. 본 연구는 골격계 질환 치료를 위한 새로운 세포 치료 표적으로 Cd168+ SSPC의 가능성을 제시했다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-06*
