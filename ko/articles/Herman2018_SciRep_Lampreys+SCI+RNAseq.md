---
tags: [2026-07]
extract: 2026-07-16
---

# Highly conserved molecular pathways, including Wnt signaling, promote functional recovery from spinal cord injury in lampreys

## Citation (NLM)
Herman PE, Papatheodorou A, Bryant SA, Waterbury CKM, Herdy JR, Arcese AA, Buxbaum JD, Smith JJ, Morgan JR, Bloom O. Highly conserved molecular pathways, including Wnt signaling, promote functional recovery from spinal cord injury in lampreys. Sci Rep. 2018;8:742. doi:10.1038/s41598-017-18757-1

**DOI:** [https://doi.org/10.1038/s41598-017-18757-1](https://doi.org/10.1038/s41598-017-18757-1)

---

## Background
포유류에서 척수 손상(SCI)은 신경세포와 시냅스 연결의 극적인 손실 및 영구적 기능 결손을 초래한다. 포유류와 달리 칠성장어(lamprey)는 약 5억 5천만 년 전 인간의 공통 조상에서 분기한 고대 척추동물 계통으로, 완전 척수 절단 후 자발적으로 재생하고 기능을 회복하여 약 12주 내에 수영 능력을 되찾는다. 칠성장어 CNS는 유악류 척추동물과 매우 유사하며, 게놈 서열 분석으로 축삭 유도, 시냅스 전달, 신경 패터닝의 보존된 경로가 밝혀졌다. 저자들은 재생하는 하행 축삭의 상당수가 뇌의 망상척수(RS) 신경세포에서 기원하므로, SCI 후 척수와 뇌 모두의 전체 전사 반응을 규명하여 심층 보존된 친재생(pro-regenerative) 경로를 찾고자 하였다.

---

## Key Experiment Methods
1. 후기 유생 바다칠성장어(Petromyzon marinus)의 완전 척수 절단 및 12주에 걸친 수영 회복의 정량적 행동 점수화(0-4 척도).
2. 미손상 대조군과 10개 손상 후 시점(6시간~12주, 시점당 n=6 pooling)의 척수(병변 주변 1 cm)와 뇌(후각엽 제외 전뇌) cDNA 라이브러리 RNA-Seq.
3. 공개된 칠성장어 게놈(Ensembl Pmarinus_7.0)에 read 매핑, RSEM으로 발현 정량, EBSeq로 차등발현(PPDE >=0.95) 분석, 계층적 클러스터링.
4. Enrichr(GO, KEGG)와 TRANSFAC/JASPAR 전사인자 네트워크 분석으로 인간/생쥐 오솔로지를 활용한 기능/경로 추론.
5. 주요 재생/증식/세포사멸 유전자의 상동성 BLAST 검증.
6. 약리학적 Wnt 차단: PORCN 억제제 Wnt-C59(10 uM) 또는 vehicle을 Gelfoam으로 절단 부위에 단회 투여, 12주 행동 점수화 및 3 dpi RNA-Seq 후속 분석.
7. JUN과 ATF3 시간별 발현의 qPCR 검증.

---

## Results
- SCI는 척수와 뇌 모두에서 강력하고 동적인 전사 반응을 유발; 미손상 프로파일은 별도로 클러스터되었고, 새로운 차등발현 전사체가 회복 후기(12 wpi)까지 계속 나타나 회복이 미손상 상태로의 단순 복귀가 아님을 보임.
- 풍부화된 기능 범주에는 면역 기능, ECM 리모델링, 발생, 신경세포 기능, 증식, 세포사멸, 세포골격, 이온 채널이 포함되어 재생 능력이 있는 제브라피시/액솔로틀 및 포유류 PNS 반응과 유사.
- TF 네트워크 분석은 FOXC1, NFKB1, 그리고 표준(canonical) Wnt 구성원 LEF1을 시사; 포유류 PNS에서 알려진 재생 관련 유전자(RAG) 17개가 풍부화, 그중 CEBPB, GATA2, JUN, LEF1은 두 조직 모두에서 10개 시점 전체에 차등발현.
- ATF3는 척수와 뇌 모두에서 가장 강하게 유도된 RAG였으며, JUN, SOX11, SMAD, REL 상동체가 높게 상향 조절되어 포유류 PNS 손상 핵심 네트워크와 일치.
- 성장 촉진 전사체(SNAP25, ACVR1)는 상향, 성장 억제 전사체(RHOB, SLIT2/3, ROBO2/3)는 하향 조절; 신경섬유(neurofilament), synapsin, semaphorin, ECM 유전자(콜라겐, 라미닌), 면역 유전자(IL8, CXCR4)가 차등발현.
- 차등발현 전사체의 약 3%가 Wnt 경로에 매핑(척수 121개, 뇌 101개)되었고 손상 후 첫 주에 정점.
- 약리학적 Wnt 억제(C59)는 기능 회복을 차단: C59 처리군은 12 wpi에 운동 점수 약 1.6에 그친 반면 vehicle군은 약 3.33; 3 dpi RNA-Seq에서 직접 Wnt 표적(CDH2, Cldn19, CCNB2, FN1, 케라틴류; 뇌: Axin1, JAG2, JUN, MMP9, Tbr1/TBX20)의 발현 변화 확인.

---

## Perspective
본 연구는 기저 척추동물인 바다칠성장어의 자연적 SCI 회복 과정에서 척수와 뇌를 대상으로 한 최초의 RNA-Seq 분석이다. 고도로 보존된 포유류 PNS 관련 친재생 프로그램(ATF3/JUN 네트워크)과, 특히 Wnt 신호전달이 기능 회복에 관여하고 필수적임을 입증하여 칠성장어 모델의 중개연구적 타당성을 뒷받침한다. 예상외로 강력한 뇌(supraspinal) 반응은 회복에 손상된 하행 신경세포의 세포체가 관여함을 강조하며, 이는 만성기 인간 SCI 회복 촉진과 관련된다. 저자들이 인정한 한계로는 불완전한 칠성장어 참조 전사체, 제한적인 기능유전학 도구(morpholino/CRISPR/약리학은 사용 가능), 세포 유형별 프로그램을 가리는 벌크 조직 프로파일링, 그리고 필요한 Wnt 구성요소를 특정할 수 없는 범-Wnt 분비 억제제 사용이 있다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
