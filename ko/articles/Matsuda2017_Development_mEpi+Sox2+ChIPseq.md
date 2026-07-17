---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p06.txt
---

# ChIP-seq analysis of genomic binding regions of five major transcription factors highlights a central role for ZIC2 in the mouse epiblast stem cell gene regulatory network

## Citation (NLM)
Matsuda K, Mikami T, Oki S, Iida H, Andrabi M, Boss JM, Yamaguchi K, Shigenobu S, Kondoh H. ChIP-seq analysis of genomic binding regions of five major transcription factors highlights a central role for ZIC2 in the mouse epiblast stem cell gene regulatory network. Development. 2017;144(11):1948-1958. doi:10.1242/dev.143479

**DOI:** [https://doi.org/10.1242/dev.143479](https://doi.org/10.1242/dev.143479)

---

## Background
포유류 체세포는 착상 후 배아의 상배엽(epiblast)에서 유래한다. 알집 원기(egg-cylinder) 단계 마우스 배아에서 수립된 상배엽 줄기세포(EpiSC)는 상배엽의 유전자 조절 네트워크 연구와 특정 체세포 계통 유도를 위한 모델을 제공하며, activin/Nodal 신호를 제거하면 전측 신경판(anterior neural plate, ANP) 세포로 발생한다. 저자들은 선행 연구에서 ZIC2, OTX2, SOX2, POU5F1, POU3F1을 EpiSC 및 EpiSC→ANP 전환의 주요 조절자로 규명하였다. 이 전사인자(TF)들은 E6.5 이후 상배엽에서 전후축 국재를 변화시키며, 이들의 조작은 다양한 체세포 계통 유도를 좌우하는 하위 TF에 큰 영향을 미친다.

SOX2–POU5F1 쌍은 배아 줄기세포(ESC)의 핵심 조절 모듈로 잘 확립되어 있으나, 발생적으로 더 진행된(primed) EpiSC 상태에서 이들 및 다른 TF의 유전체 결합이 어떻게 조직되고 ESC→EpiSC 전환 중 어떻게 재분배되는지는 불명확하였다. 본 연구는 ChIP-seq으로 EpiSC에서 다섯 TF의 유전체 전반 결합을 지도화하여, 초기 배발생 및 신경 계통 priming과 관련된 TF 의존적 조절을 규명한다.

---

## Key Experiment Methods
1. **In vivo 비오틴화 ChIP-seq:** TF의 C-말단에 biotin ligase recognition peptide(BLRP)를 융합하고 E. coli biotin ligase(BirA)를 함께 발현하는 단일 pCAGGS-BLRP-IRES-BirA 벡터를 사용하여, 항체 의존적 효율 변동을 회피하는 간소화된 ChIP-seq 기법 개발.
2. **생리적 수준의 일시적 형질주입:** feeder-free EpiSC 세포주에 10-cm 접시당 5 µg 벡터를 고효율(75~95%)로 일시 형질주입하여 외인성 TF를 거의 생리적 수준으로 조정(histone H2로 정규화한 면역형광으로 검증; NANOG/POU5F1 확인으로 EpiSC 상태 유지 확인).
3. **ChIP 및 라이브러리 제작:** formalin 고정, 전세포 용해물 크로마틴 절편화(~150 bp), streptavidin 자기 비드로 비오틴화 TF–DNA 복합체 포획, TruSeq 라이브러리, Illumina HiSeq2500 single-end 100 bp 시퀀싱.
4. **피크 콜링 및 분석:** mm9에 Bowtie2 정렬; MACS1.4 피크 콜링(TF당 60,000~120,000 피크); MEME-ChIP 모티프 농축; 피크 폭·gap 크기·TSS 근접성 분석; IGV/ChIP-Atlas 시각화; GREAT 유전자 연관; BioVenn 중첩 분석.
5. **공개 데이터 통합:** 히스톤 H3 변형 ChIP-seq(H3K4me1/K27ac 활성 인핸서, H3K4me1/K27me3 poised 인핸서), 체세포(ATDC5 연골세포, MEF, 근모세포) 마이크로어레이 발현, ESC/EpiLC/인간 ESC ChIP-seq(UCSC LiftOver로 mm9 좌표 변환)와 중첩 분석.

---

## Results
- **Mb 규모 교번 도메인:** ZIC2 피크가 풍부하고 유전자도 풍부한 메가베이스 규모 도메인과, POU3F1 피크가 풍부하나 유전자는 희박한 도메인이 교번한다. 이는 단거리(ZIC2)와 장거리(POU3F1) 조절 서열의 군집화를 반영한다. OTX2는 ZIC2와, SOX2/POU5F1은 POU3F1과 함께 위치하는 경향.
- **피크 중첩으로 본 두 TF 그룹:** ZIC2–OTX2 피크는 광범위하게 중첩(~16~19%)한 반면 ZIC2–POU3F1 중첩은 미미(~1.2~1.3%). SOX2와 POU 인자들이 두 번째 중첩 그룹을 형성. ZIC2/OTX2 대 SOX2/POU는 대체로 별개 모듈로 작동.
- **TSS 근접성:** ZIC2·OTX2 피크의 ~55%가 TSS로부터 50 kb 이내(유전자 근접)인 반면, SOX2·POU5F1·POU3F1 피크의 >80%는 TSS로부터 50 kb 이상 떨어짐(유전자 원거리).
- **인핸서 시그니처:** ZIC2 결합은 활성(H3K4me1/K27ac) 및 poised(H3K4me1/K27me3) 인핸서 표지 모두와 가장 빈번히 연관. ZIC2–OTX2 공동 결합 피크의 ~33%가 활성 인핸서 표지를 가져 이 쌍이 주로 전사 활성자로 작용함을 시사. 예: Fgf5(EpiSC 활성), Pax6(poised, ANP 유전자).
- **ZIC2–OTX2가 TF 유전자를 조절:** 히스톤 표지된 ZIC2–OTX2 공동 결합 영역 근처 유전자, 특히 TF 유전자(Mycn, Nanog, Otx2, Pou5f1, Sall4, Sox2 등)는 EpiSC 대비 체세포에서 우선적으로 하향조절되어, 이들이 기능적 EpiSC 인핸서임을 확인.
- **줄기세포별 SOX2/POU5F1 결합의 발산:** SOX2–POU5F1 피크는 ESC에서 ~78% 중첩하나 EpiSC에서는 ~8%만 중첩. 종·상태 간 비교로 발생 진행 순서를 마우스 ESC → EpiLC → 인간 ESC → 마우스 EpiSC로 정렬.
- **인핸서 priming/pioneer 인자로서의 ZIC2:** ESC의 ZIC2 결합 영역 중 ~80%가 EpiSC에서도 ZIC2 결합 유지. ESC에서 ZIC2는 bivalent 인핸서의 NuRD 복합체와 상호작용. ZIC2는 ESC에서 유전체 위치를 미리 표지(priming)하여 SOX2/POU5F1이 이탈한 후 OTX2가 결합하는 활성 인핸서로 전환되게 하는 것으로 보임 — 다능성 유전자(Mycn, Nanog, Nodal, Sall4)와 EpiSC 특이적 Fgf5에서 입증.

---

## Perspective
본 연구는 효율적인 in vivo 비오틴화 ChIP-seq 절차를 제시하고 마우스 EpiSC의 다섯 핵심 TF에 대한 새로운 유전체 자원(GEO GSE74636)을 제공한다. 개념적으로는 primed 다능성 네트워크를 재정립한다: 주요 작용 TF 쌍이 SOX2/POU5F1(ESC)에서 ZIC2/OTX2(EpiSC)로 이동하면서도 유사한 유전자 집합을 조절하며, ZIC2는 ESC에서 위치를 미리 표지하여 이후 활성화에 대비시키는 인핸서 priming("pioneer"/"seed-enhancer") 인자로 작용한다. 신경 계통과의 관련성이 주목된다: SOX2, nestin(Nes30) 인핸서, ANP 표지자 Pax6가 두드러지게 등장하여 이 조절 논리를 신경판 특정화 및 신경 줄기/전구세포 priming과 연결한다. 한계로는 (거의 생리적이지만) 일시적 과발현에 의존한 점, anti-ZIC2 항체의 ZIC1/ZIC3 교차반응성, 그리고 대부분 결론이 기능적 교란이 아닌 상관적(ChIP/히스톤/발현) 성격이라는 점이 있다. 제기된 미해결 질문으로는 Mb 규모 교번 도메인 구성이 EpiSC 특이적인지, 그것이 고차 유전체 구조와 어떻게 연관되는지, 그리고 중간 상태인 EpiLC에서의 ZIC2/SOX2 결합 동역학이 포함된다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
