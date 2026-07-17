---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p05.txt
raw_data:
  - "GEO: GSE67833"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Single-Cell Transcriptomics Reveals a Population of Dormant Neural Stem Cells that Become Activated upon Brain Injury

## Citation (NLM)
Llorens-Bobadilla E, Zhao S, Baser A, Saiz-Castro G, Zwadlo K, Martin-Villalba A. Single-Cell Transcriptomics Reveals a Population of Dormant Neural Stem Cells that Become Activated upon Brain Injury. Cell Stem Cell. 2015;17(3):329-340. doi:10.1016/j.stem.2015.07.002

**DOI:** [https://doi.org/10.1016/j.stem.2015.07.002](https://doi.org/10.1016/j.stem.2015.07.002)

---

## Background

성체 뇌의 뇌실하영역(SVZ)에 존재하는 신경줄기세포(NSC, type B 세포)는 지속적으로 신경모세포(neuroblast)를 생성하여 후각망울로 이동시키며, 손상 후에는 뇌 회복에 기여하도록 동원될 수 있다. NSC가 기능적으로 이질적이며 서로 다른 활성 상태와 신경/교세포 계통을 생성하는 능력을 가진 세포들이 공존한다는 증거가 축적되어 왔다. 그러나 기존 연구들은 소수의 마커만을 조사하거나 혼합된 세포 집단을 다루었기 때문에, NSC 활성화와 계통 결정의 분자적 조절 기전, 그리고 서로 다른 NSC 풀이 손상에 어떻게 반응하는지는 명확하지 않았다.

저자들은 편향 없이 급속 분리한 성체 SVZ NSC를 단일세포 RNA 시퀀싱으로 분석하여 이질성을 규명하고, 정지(quiescence)에서 활성화로의 전환을 지도화하며, 손상 유도성 NSC 활성화의 분자적 방아쇠를 규명하고자 하였다.

---

## Key Experiment Methods

1. 유전자변형 리포터 없이, SVZ NSC를 CD45−/O4−/GLAST+/Prominin1(CD133)+ 세포로, 신경모세포를 PSA-NCAM+ 세포로 FACS 분리.
2. GLAST+/Prom1+ 세포 104개와 PSA-NCAM+ 세포 26개에 대한 단일세포 RNA-seq(Smart-seq2), 1,000세포 집단 대조군 및 기술적 잡음 보정을 위한 RNA spike-in 포함.
3. 주성분분석(PCA), 비지도 계층적 군집화, 세포 간 상관분석으로 세포 유형 및 아집단 정의.
4. Monocle를 이용한 유사시간(pseudotime) 순서화로 휴면-활성화 연속체 재구성.
5. O-propargyl-puromycin(OP-Puro) 도입을 통한 단백질 합성 속도의 기능적 검증, 그리고 γ-secretase 억제제(DAPT)를 이용한 Notch의 정지 유지 역할 검증.
6. 실질 성상세포(n=21) 및 전이증폭전구세포(TAP, n=27)의 비교 scRNA-seq로 NSC 특이 마커(CD9) 규명.
7. 전사인자만을 이용한 PCA 및 상관분석으로 계통/공간적 프라이밍 재구성, Ascl1 ChIP-seq와 비교.
8. 일과성 양측 총경동맥 폐색(허혈성 손상) 후 손상된 NSC 45개의 scRNA-seq, Ingenuity 상류 조절인자 분석, Ifngr1−/− 마우스에서의 검증.

---

## Results

- 단일세포 전사체는 신경모세포(PSA-NCAM+), NSC(GLAST+/Prom1+), 소규모 희소돌기교세포 클러스터의 세 유형으로 명확히 분리되었다.
- NSC는 정지(qNSC, Egfr−)와 활성(aNSC, Egfr+, 세포주기 유전자) 상태로 나뉘었고, 각각 다시 세분화(qNSC1/2, aNSC1/2)되어 연속체를 형성하였다. 유사시간 분석은 휴면 상태(qNSC1) → 프라임 정지(qNSC2) → aNSC1 → aNSC2 순서를 제시하였다.
- 휴면 상태는 높은 해당작용·지질(지방산) 대사와 낮은 단백질 합성을 특징으로 하며, 활성화는 단백질 합성(검증: aNSC가 qNSC보다 OP-Puro 도입 7.9배 증가), 세포주기, 계통 특이 전사인자의 상향조절을 동반하였다.
- CD9은 SVZ NSC를 실질 성상세포와 구별하였으며, TAP와 성상세포는 활성화 연속체의 양 끝에 위치하였다.
- 정지는 전사인자 Sox9, Id2, Id3 및 Notch(Notch2, Lfng)·BMP(Bmpr1b, Id2) 신호와, 활성화는 Egr1, Fos, SoxC(Sox4/11), Ascl1과 연관되었다. DAPT(Notch 억제)는 qNSC를 활성화 방향으로 유도하였다.
- NSC는 계통/공간적으로 프라임되어 있었으며, 상관된 전사인자 모듈(배측 Emx1/Nr2f1, 복측 Nkx2-1, 외측 Gsx2/Dlx2, Olig2 희소돌기교세포 클러스터 등)이 정지·활성 세포 모두에서 운명이 정해진 아집단을 반영하였다.
- 허혈성 손상은 NSC를 휴면에서 프라임 정지 및 활성 상태로 이동시켰다. 손상반응 유전자는 인터페론감마(IFN-γ) 표적으로 농축되었고, Ifngr1−/− 마우스에서는 IFN-γ 반응과 휴면→프라임 정지 전환이 대부분 소실되어 IFN-γ가 분자적 방아쇠임을 확인하였다.

---

## Perspective

본 연구는 성체 SVZ NSC 상태에 대한 최초의 고해상도·비편향 단일세포 지도를 제공하여, 휴면과 프라임 정지를 근육 위성세포의 G0→Galert 전환을 연상시키는 별개의 단계로 확립하고, 번역 조절이 휴면 탈출의 초기 사건임을 규명하였다. NSC 특이 마커(CD9)를 정의하고 개별 NSC에 사전 계통 프라이밍이 존재함을 입증하였다. 기능적으로는 IFN-γ를 휴면 NSC를 동원하는 손상 유래 신호로 규명하여, 내인성 줄기세포를 동원하는 재생 전략의 가능성을 열었다. 한계로는 분석된 단일세포 수가 제한적이고, 표면 마커 기반 분류에 의존하며, 상태 전환이 상관관계/유사시간 추론에 기반하므로 직접적인 계통추적 검증이 필요하다는 점이 있다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- GEO: GSE67833


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
