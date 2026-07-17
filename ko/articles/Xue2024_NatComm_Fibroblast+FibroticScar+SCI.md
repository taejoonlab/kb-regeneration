---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p09.txt
---

# Heterogeneous fibroblasts contribute to fibrotic scar formation after spinal cord injury in mice and monkeys

## Citation (NLM)
Xue X, Wu X, Fan Y, Han S, Zhang H, Sun Y, Yin Y, Yin M, Chen B, Sun Z, Zhao S, Zhang Q, Liu W, Zhang J, Li J, Shi Y, Xiao Z, Dai J, Zhao Y. Heterogeneous fibroblasts contribute to fibrotic scar formation after spinal cord injury in mice and monkeys. Nat Commun. 2024;15:6321. doi:10.1038/s41467-024-50564-x

**DOI:** [https://doi.org/10.1038/s41467-024-50564-x](https://doi.org/10.1038/s41467-024-50564-x)

---

## Background

척수손상(SCI)은 병변 부위에 두 종류의 반흔을 형성한다: 증식하는 GFAP+ 성상교세포로 이루어진 성상교세포 반흔과 세포외기질(ECM)을 생산하는 근섬유아세포(myofibroblast)로 채워진 섬유성 반흔(fibrotic scar)이다. 섬유성 반흔은 축삭 재생의 장벽으로 여겨지지만, 완전 제거는 해로운 공동(cavity)을 남기는 반면 부분 감소는 회복을 향상시켜, 섬유성 반흔 조직의 기능적 이질성을 시사한다. 반흔을 형성하는 근섬유아세포의 세포 기원은 수막 섬유아세포(MF), 혈관주위 섬유아세포(PF), 또는 A형 주위세포(type A pericyte) 등으로 다양하게 주장되며 구분 표지자 유전자의 부재로 논란이 있어왔다.

본 연구는 계통 추적(lineage tracing)과 단일세포 RNA 시퀀싱(scRNA-seq)을 사용하여 마우스와 암컷 붉은털원숭이(rhesus monkey)에서 SCI 후 섬유성 반흔 내 섬유아세포의 분포·기원·기능을 규명하였다.

---

## Key Experiment Methods

1. 다수의 CreER::R26-TdTomato 마우스 계통을 이용한 계통 추적: PDGFRβ-CreER(혈관주위+수막 세포), Col1a2-CreER(섬유아세포), Myh11-CreER 및 NG2-CreER(주위세포/vSMC), CRISPR/Cas9로 제작한 Crabp2-CreER(수막 섬유아세포).
2. 두 가지 SCI 모델: 절단(transection, 관통성) 및 압착(crush, 비관통성)을 5 dpi, 14 dpi, 손상 후 1개월에 분석.
3. 면역염색: TdT와 CD31/Pdx(혈관), GFAP, CD68, Ki67/BrdU(증식), Acta2/Tagln(근섬유아세포), Desmin, Lama1/Lama2, Crabp2/Emb, Col1/Col6a1의 공동 국소화.
4. FACS로 분리한 PDGFRβ-TdT+ 세포의 scRNA-seq(0, 5, 14 dpi에서 44,386개 세포); 군집화, DEG 분석, 공개된 압착 SCI 데이터와 비교.
5. 신호경로 분석: GO/KEGG 강화 분석 및 CellPhoneDB 리간드-수용체 상호작용 점수(TGF-β, Wnt, PDGF).
6. 원숭이(Macaca mulatta) 절단 SCI, 병변 가장자리와 중심부의 10x Genomics 시퀀싱; 종간 DEG 비교 및 면역염색(CRABP2, LAMA1).
7. 시험관 실험: 분리한 CE-F(경막/거미막)와 LA-F(연막)의 콜레스테롤 합성/수송 유전자, Bodipy 지질방울, 수초 식균, transwell 공배양 혈관신생 검증.

---

## Results

- PDGFRβ+ 세포(혈관주위 및 수막)는 절단·압착 SCI 모두에서 병변 중심부로 이동하여 Acta2+ 근섬유아세포로 전환되며, 모집은 압착보다 절단 손상에서 더 높다.
- 주위세포/vSMC가 아니라 섬유아세포가 섬유성 반흔의 주 기원이다: TdT+ 세포의 8% 미만만 Desmin과 공동 국소화하였고, Myh11+ 및 NG2+ 주위세포/vSMC의 기여는 미미한 반면 Col1a2-CreER로 추적한 섬유아세포가 Col1+/Col6a1+ 병변을 채웠다.
- 두 섬유아세포 집단이 구분되었다: 반흔 중심부에 위치하는 수막 유래 Crabp2+/Emb+ 섬유아세포(CE-F)와 주변부에 위치하는 혈관주위/연막 Lama1+/Lama2+ 섬유아세포(LA-F).
- CE-F는 콜레스테롤 합성(Hmgcr, Pmvk, Hmgcs1)이 강화되어 있고 I형 콜라겐과 피브로넥틴을 분비하며, LA-F는 라미닌과 IV형 콜라겐을 발현하고 콜레스테롤 수송(Apod, Apoe, Abca1, Lrp1) 및 혈관신생 기능을 담당한다.
- 신호전달: TGF-β 및 Wnt 경로가 주로 섬유아세포에서 활성화되어 섬유화를 유도하는 반면, PDGFB/PDGFD 신호는 주위세포/vSMC(혈관신생)에서 더 활성화된다. 미세아교세포/대식세포는 TGFB 리간드를 분비하여 섬유아세포의 TGF-β 신호를 활성화한다.
- LA-F는 시험관 및 생체 내에서 수초를 우선적으로 식균하여 지질방울을 형성하였고, 공배양에서 CE-F보다 혈관 형성을 더 촉진하였다.
- 섬유아세포 이질성(중심부 CE-F, 주변부 LA-F)은 마우스와 원숭이 사이에 보존되었으며, 더 큰 원숭이 병변 중심부에는 더 많은 CE-F가 모집되었다.

---

## Perspective

본 연구는 엄격한 다계통 계통 추적과 종간 scRNA-seq를 결합하여, 척수 섬유성 반흔이 관통성·비관통성 손상 모두에서 주위세포/vSMC가 아니라 PDGFRβ+ 수막 및 혈관주위 섬유아세포에서 주로 유래함을 보여 오랜 논란을 해소하였다. 또한 공간적·기능적으로 뚜렷이 구분되는 두 반흔 섬유아세포 아형(콜레스테롤 합성/콜라겐 침착의 CE-F, 지질 수송/혈관신생의 LA-F)을 규정하여, 섬유성 반흔을 완전히 제거하기보다 선택적으로 재구성함으로써 축삭 재생과 기능 회복을 향상시키는 틀을 제시한다.

한계로는 Myh11+/NG2+ 계통이 모든 주위세포를 표지하지 못하므로 소수의 주위세포-근섬유아세포 기여를 완전히 배제할 수 없다는 점과, CNS 주위세포 이질성이 아직 충분히 규명되지 않았다는 점을 저자들이 인정한다. 향후에는 CE-F와 LA-F의 아형 특이적 제거 또는 조절을 통해 손상 미세환경과 회복에 대한 차별적 영향을 규명해야 한다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
