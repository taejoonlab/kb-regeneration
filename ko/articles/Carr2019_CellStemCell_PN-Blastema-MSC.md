---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
raw_data:
  - "GEO: GSE120678"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Mesenchymal Precursor Cells in Adult Nerves Contribute to Mammalian Tissue Repair and Regeneration

## Citation (NLM)
Carr MJ, Toma JS, Johnston APW, Steadman PE, Yuzwa SA, Mahmud N, Frankland PW, Kaplan DR, Miller FD. Mesenchymal Precursor Cells in Adult Nerves Contribute to Mammalian Tissue Repair and Regeneration. Cell Stem Cell. 2019;24(2):240-256. doi:10.1016/j.stem.2018.10.024

**DOI:** [https://doi.org/10.1016/j.stem.2018.10.024](https://doi.org/10.1016/j.stem.2018.10.024)

---

## Background

말초 신경 지배는 여러 종에서 조직 복구와 재생에 필수적이다. 양서류에서는 사지 재생에 신경이 필요하고, 재생 능력이 없는 포유류에서도 심장, 뼈, 손발가락 끝(digit tip) 복구를 신경이 돕는다. 이러한 재생 촉진 효과는 주로 축삭이 분비하는 리간드와 탈분화된 슈반세포(Schwann cell)가 방출하는 인자를 통해 일어난다고 여겨져 왔다. 그러나 말초 신경에는 상신경초(epineurium), 신경다발막(perineurium), 신경내막(endoneurium)에 존재하는 중간엽 세포도 포함되어 있으며, 이들이 복구에 기여하는지는 규명되지 않았다.

본 연구는 손상된 말초 신경이 중간엽 전구 유사 세포(mesenchymal precursor-like cell)의 저장고로 작용하여, 이 세포들이 인접한 손상 조직으로 이동해 직접 복구에 기여한다는 가설을 검증한다. 이를 통해 포유류 재생의 신경 의존성을 세포 수준에서 설명하고자 한다.

---

## Key Experiment Methods

1. PdgfraEGFP/+ 마우스 좌골신경(비손상 vs. 축삭절단 9일 후)에 대한 면역염색(PDGFRa, CD34, Thy1, S100b 등)과 EdU 표지를 통한 손상 유도 증식 분석.
2. 손상 9일차 원위 좌골신경 약 4,300개 세포와 비손상 대조군 약 2,000개 세포에 대한 고처리량 droplet 기반 단일세포 RNA 시퀀싱(Drop-seq), t-SNE 클러스터링, 차등발현 분석, 계층적 클러스터링, Cyclone 세포주기 예측, 랜덤포레스트 클러스터 검증.
3. 대조군과 손상군의 Pdgfra 양성 전사체 통합 재분석(mutual nearest neighbors 배치 보정 포함)으로 중간엽 집단 비교.
4. 출생 후 및 성체 신경 세포의 시험관 내 분화 분석(골형성, 지방형성, 연골형성), PdgfraCreERT;R26-LSL-TdT 계통 표지 세포 분류 포함.
5. 유전적으로 표지된 신경 절편을 NOD-SCID 마우스의 대퇴골 골막 스크래치 손상 부위 옆에 이식.
6. Wnt1Cre, Wnt1CreERT2, DhhCre로 R26-LSL-TdT를 구동하는 신경능선(neural crest) 계통 추적을 성체 손발가락 끝 절단 및 피부 상처 모델에 적용, CLARITY 3차원 영상 및 탈신경 실험 병행.

---

## Results

- Pdgfra-EGFP 양성 중간엽 세포는 모든 신경 구획에 존재하며, 축삭절단 후 신경내막 밀도가 약 3배 증가하고 증식(EdU+)한다. 비손상 반대측 신경에는 증식하는 Pdgfra+ 세포가 없었다.
- 손상 신경의 scRNA-seq은 전사체가 뚜렷이 구분되는 4개의 Pdgfra 양성 중간엽 집단을 확인했다: 전구 유사 신경내막 세포(클러스터 2/5, Sox5/6/8, Sox9, Etv1, Alpl, Col2a1 및 MSC/골연골 유전자 발현), 분화 중인 신경 절단부 세포(클러스터 1/3/6, Dlk1, Runx2, Tnc), 상신경초 세포(클러스터 4/7, Gsn, Ly6c1, Dpt), 신경다발막 세포(클러스터 8, Glut1/Slc2a1, Itgb4).
- 대조군과 손상 신경 비교 시 신경다발막·상신경초 세포는 손상 여부와 무관하게 함께 클러스터링된 반면, 신경내막 세포는 손상에 의해 전사체가 변화(Aldh1a2, C3, Ccl2, Wif1 등 상향조절)하며 더 전구 유사 상태가 되었다. 별개의 신경 절단부 클러스터는 손상 후에만 나타났다.
- 신경 중간엽 세포는 배양에서 골형성·지방형성·연골형성 계통으로 분화했고, PdgfraCreERT-TdT 계통 표지로 확인되었다. 이식된 표지 신경은 대퇴골 복구 가골(callus)에 TdT+/ALPL+/osteocalcin+ 세포를 생체 내에서 기여했다.
- 신경내막 중간엽 세포는 신경능선 유래(Wnt1Cre-TdT+, Sox9+ 세포의 약 65%)였다. 손발가락 끝 재생 중 Pdgfra-EGFP+ 배아모체(blastema) 세포의 약 21%가 Wnt1Cre-TdT+였고, 절단 28일차(DPA)에는 신경능선 유래 세포가 재생된 뼈 소강(lacunae)의 약 32%를 차지했다.
- DhhCre 계통 추적이 신경능선 기여를 뒷받침했다. 대조 실험(EdU, Wnt1 qRT-PCR/FISH, 유도성 Wnt1CreERT2)은 상주 골세포의 증식이나 신생 Wnt1 유도 가능성을 배제했으며, 탈신경은 재생 조직에서 신경능선 유래 세포 밀도를 크게 감소시켰다.

---

## Perspective

본 연구는 말초 신경이 신경능선 유래 중간엽 전구 세포를 공급하며, 이 세포들이 손상 조직으로 이동해 뼈(손발가락 끝 재생, 대퇴골 복구)와 진피 복구에 직접 기여함을 확립하여, 오래 관찰되어 온 포유류 조직 재생의 신경 의존성에 대한 세포 수준의 설명을 제시한다. 신경이 거의 모든 조직을 지배하므로, 이 저장고는 재생의학에 폭넓은 함의를 가질 수 있다. 한계로는 계통 추적 마우스 모델 의존성과 초기 scRNA-seq의 상대적으로 얕은 깊이가 있으며, 손발가락 끝/뼈 맥락이므로 중추신경/척수 재생과의 직접적 관련성은 간접적이다. 향후 방향으로는 이 전구 세포를 동원·유도하는 신호의 규명과, 신경 유래 중간엽 세포를 재생이 저조한 조직의 복구 향상에 활용할 수 있는지 검증이 포함된다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- GEO: GSE120678


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
