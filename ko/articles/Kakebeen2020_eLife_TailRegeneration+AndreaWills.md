---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p04.txt
raw_data:
  - "GEO: GSE146837"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Chromatin accessibility dynamics and single cell RNA-Seq reveal new regulators of regeneration in neural progenitors

## Citation (NLM)
Kakebeen AD, Chitsazan AD, Williams MC, Saunders LM, Wills AE. Chromatin accessibility dynamics and single cell RNA-Seq reveal new regulators of regeneration in neural progenitors. eLife. 2020;9:e52648. doi:10.7554/eLife.52648

**DOI:** [https://doi.org/10.7554/eLife.52648](https://doi.org/10.7554/eLife.52648)

---

## Background
포유류와 달리 Xenopus 올챙이는 사지, 척수, 꼬리를 흉터 없이 완전히 재생하지만 이 능력은 변태 시 감소하고 성체에서는 소실된다. 이 때문에 Xenopus는 재생을 지배하는 세포 내재적·외재적 특성을 연구하는 유용한 모델이다. 손상은 발생 신호(Wnt, FGF, BMP, TGF-β, Notch, Shh)를 부분적으로 재현하는 빠른 전사체 재구성을 유발한다. 그러나 기존의 유전체 전반 연구는 재생 조직 전체(bulk)를 대상으로 하여, 어떤 세포 유형이 특정 발현 변화를 주도하는지, 어떤 전사인자가 손상 신호를 해석하는지 규명하기 어려웠다.

신경전구세포(NPC)는 척수 재생의 핵심 세포이자 운동기능 회복을 위한 재생의학의 주요 표적이다. 발생 과정에서 신경줄기세포는 계통이 제한된 전구세포 영역을 형성하며, 세포주기 이탈과 분화 결정은 Notch 억제 같은 외재적 신호에 의해 조절된다. 저자들은 재생 중 NPC 운명 결정을 지배하는 유전자 조절 동역학을 규명하기 위해, 재생 중인 Xenopus tropicalis 꼬리에서 pax6 발현 NPC의 염색질 접근성과 전사를 특이적으로 프로파일링했다.

---

## Key Experiment Methods
1. Xtr.Tg(pax6:GFP) transgenic 라인으로 NPC를 표지; GFP가 Sox2 및 중심관 주변 pax6 영역과 공존하고 분화 뉴런 마커(Dcx, neurofilament)와 구분됨을 확인.
2. pax6:GFP+ 세포를 FACS로 분리하여 0, 6, 24, 72 hpa 및 미손상 조직에서 정렬 NPC("pax6")와 전체 조직("all-tissue") ATAC-Seq 라이브러리 제작; ENCODE 기준으로 QC.
3. 시점별 차등 접근성 분석 및 GO:BP 분석(gProfileR2, ReviGO); MDS 클러스터링; peak-TSS annotation.
4. 미손상(2617 세포)과 24hpa(1090 세포) 꼬리 신경세포의 scRNA-Seq; Seurat 통합, UMAP 클러스터링, 세포주기 예측; 8개 신경 하위 클러스터 규명.
5. ATAC-Seq(HOMER 모티프 분석), bulk RNA-Seq, scRNA-Seq 차등발현을 통합한 유전자 조절 네트워크 예측.
6. Meis1, Pbx3 기능 검증: 번역 차단 morpholino, 두 번째 독립 morpholino, CRISPR/Cas9 guide, stage 35에 주입한 조직투과 vivo-morpholino; neurofilament 염색, 재생 꼬리/척수 길이, 척수 면적, PH3+ 유사분열 세포 평가; in situ hybridization으로 마커 검증.

---

## Results
- 정렬 NPC의 ATAC-Seq는 bulk 분석으로 검출 불가능한 신경 특이 접근성 영역(bulk보다 접근성 높은 3604개 영역, "Neurogenesis", "Nervous system development" 강화)을 밝혀냈다.
- 시간에 따른 접근성 우선순위 변화: 6hpa에 세뇨관/ependymal 형태형성, 24hpa에 뉴런 분화, 72hpa에 신경전구세포 증식.
- scRNA-Seq로 8개 신경 하위 클러스터(척수 전구세포, floor plate 전구세포, 분화 중 뉴런, interneuron, 운동뉴런, vulnerable 운동뉴런, leptin+ 운동뉴런, 도파민성 뉴런)를 새 후보 마커와 함께 분해; axolotl 사지 결합조직과 달리 Xenopus 신경세포는 손상 후에도 이질적 정체성 유지.
- 24hpa에 NSC 38%→25%, 분화 중 뉴런 20%→10%로 감소하고 분화 뉴런은 42%→65%로 증가, 세포주기는 G1로 이동 — 증식보다 분화(특히 운동뉴런·interneuron)의 조기 우선화를 뒷받침.
- 유전자 조절 네트워크 예측으로 Meis1과 Pbx3(homeodomain 전사인자)를 후보 조절자로 규명; 둘 다 신경세포에서 발현되고 24hpa에 운동/inter/도파민성 뉴런에서 증가하며 표적 영역이 중첩(Meis1 표적은 24hpa, Pbx3는 72hpa에 정점).
- Meis1 또는 Pbx3 knockdown(morpholino, vivo-MO, CRISPR)은 재생 꼬리·척수 단축, 척수 면적 감소, neurofilament 염색의 무질서/감소를 초래하여 두 유전자가 성공적 꼬리·척수 재생에 필수적임을 확립.

---

## Perspective
이 연구는 세포 유형 특이적 ATAC-Seq(FACS)와 scRNA-Seq를 결합하여 NPC의 유전자 조절 지형을 규명함으로써 척추동물 재생생물학을 진전시켰다. Bulk 분석으로는 보이지 않던 조절 peak를 드러냈고, 낮은 발현·계통 제한적 조절자(pbx3, meis1)를 후보 상위로 끌어올렸다. 핵심 통찰은 분화와 증식의 시간적 분리(temporal uncoupling)이다. pax6+ 전구세포는 증식보다 뉴런 분화를 먼저 우선하는데, 이는 전구세포가 증식 후 신경발생하는 배아 발생과 대조된다. 저자들이 인정한 한계로는 NPC의 불완전 포획(일부 Sox2+/pax6- 세포, 최배측 전구세포 배제), 최근 분화하여 GFP를 유지한 pax6+/Sox2- 세포의 포함 가능성, 초기 재생 단계에서 마커 공존 미검증 등이 있다. 향후 추가·영역 특이 리포터, birthdating, 단일세포 접근으로 hit 유전자의 직접적 뉴런 작용과 환경적 작용을 구분하고 전구세포 아형별 우선순위를 완전히 규명할 수 있을 것이다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- GEO: GSE146837


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
