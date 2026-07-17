---
tags: [2026-06, Chondrocyte]
extract: 2026-06-07
---

# Pre-hypertrophic chondrogenic enhancer landscape of limb and axial skeleton development

## Citation (NLM)

Darbellay F, Ramisch A, Lopez-Delisle L, Kosicki M, Rauseo A, Jouini Z, Visel A, Andrey G. Pre-hypertrophic chondrogenic enhancer landscape of limb and axial skeleton development. _Nat Commun._ 2024 Jun 7;15(1):4820. doi: [10.1038/s41467-024-49203-2](https://doi.org/10.1038/s41467-024-49203-2). PMID: 38849444.

---

## Background

연골세포(chondrocyte) 분화는 골격 발달과 신장(stature)을 결정하는 핵심 과정이다. 중배엽 세포가 연골세포로 분화한 후, 연골 응집체 중심부의 세포는 비대로(mineral deposition 유도), 말단부의 세포는 성장판(growth plate)을 형성하여 골 연장을 지속한다. SOX9, COL10A1, COL2A1, FGFR3 등 연골세포 분화 관련 유전자의 돌연변이는 신장 이상과 다양한 골격 질환을 유발한다. 원거리 작용 인핸서(distant-acting enhancer)는 유전자의 시공간적·세포 특이적 전사를 조절하는 핵심 요소이나, **태아기 연골세포에서 활성 인핸서의 전장 유전체 지도**는 아직 정의되지 않았다. 본 연구는 Col2a1 형광 보고자 마우스를 이용해 태아 사지(limb)와 체간(trunk)의 전비대(pre-hypertrophic) 연골세포를 분리하고, 전사체·크로마틴 프로파일링을 결합하여 연골세포 특이적 인핸서의 종합적 지도를 작성하였다.

---

## Key Experiment Methods

**1. Col2a1 형광 보고자 마우스 라인 개발**

- Col2a1 전사 시작 부위 1.2 kb 상류에 minimal ß-globin promoter + EGFP 코딩 서열 삽입( regulatory sensor cassette)
- Tetraploid aggregation으로 Col2a1EGFP ESC에서 태아 유도
- E14.5 태아에서 사지(stylo/zeugo/autopod)와 체간(경부~미부, 내장 제거) 미세해부

**2. 단일세포 RNA-seq 및 세포 분류**

- E14.5 Col2a1EGFP 사지 mesenchyme scRNA-seq: 8개 클러스터 동정(MCT, dermis, PM, tendon, pre-osteoblast, perichondrium, interdigit mesenchyme, chondrocyte)
- Col2a1과 EGFP가 연골세포 클러스터에서 공동발현(correlation = 0.74)
- FACS로 EGFP+(~10%) 및 EGFP-(~90%) 세포 분리

**3. RNA-seq, ATAC-seq, H3K27ac ChIP-seq**

- EGFP+/EGFP- × 사지/체간(4개 조건)의 RNA-seq, ATAC-seq, H3K27ac ChIP-seq 수행
- DESeq2로 차등발현 분석(abs(log2FC)>1.5, FDR < 0.05)
- ATAC-seq peak 112,095개 중 H3K27ac 신호가 있는 30,953개(27.6%)를 활성 조절 영역으로 분류

**4. 연골세포 인핸서 정의 및 TAD 분석**

- EGFP+ vs EGFP- 간 H3K27ac ≥4배 차이를 보이는 promoter 제외 영역 → **2,704개 연골세포 인핸서** 동정
- E14.5 마우스 전지 연골 Hi-C 기반 TAD(3,109개)에 인핸서 할당
- chondroTADs(연골세포 유전자 + 인핸서 포함 TAD, n=357) vs chondroEnhTADs(인핸서만 포함, n=661) 비교

**5. SOX9 및 TF 결합 분석**

- E13.5 마우스 사지 SOX9 ChIP-seq 데이터와 인핸서 오버랩 분석
- 356개 TF 결합 motif enrichment 분석

**6. 인간 신장 GWAS와의 연관 분석**

- 5.4M 인간 대상 GWAS의 7,209개 신장 분산 설명 locus와 인핸서 오버랩
- Longshanks 마우스 경골 길이 연관 8개 locus 분석
- mHVEL(mouse-conserved height variance-explaining loci) 중 non-coding 1,771개와 인핸서 오버랩 비교

**7. 인핸서 기능 검증**

- LacZ 보고자 벡터에 인간 인핸서 서열 클로닝(site-directed integration)
- Col2a1EGFP 배경에서 Col2a1, Fgfr3, Hhip, Nkx3-2 locus 인핸서 homozygous deletion
- E14.5 태아 사지/체간 bulk RNA-seq로 표적 유전자 발현 변화 분석

---

## Results

**Col2a1 보고자가 전비대 연골세포 특이적 표지** scRNA-seq에서 EGFP 발현이 연골세포 클러스터에 국한되었고, perichondrium에서는 약한 신호만 관찰되었다. EGFP+ 세포는 Col2a1, Sox9, Foxa2/3, Matn, Fgfr3 등 연골세포 마커가 고발현되었고, perichondrium 마커(Foxp1/2, Sox11)는 풍부하지 않아 균질한 연골세포 집단이 분리됨이 확인되었다.

**780개 연골세포 특이적 유전자 동정** EGFP+에서 과발현된 780개 유전자 중 655개(84%)가 사지·체간 공통, 67개(9%)가 사지 특이적(Gdf5 등), 58개(7%)가 체간 특이적(Pax1 등)이었다.

**2,704개 연골세포 인핸서 지도** 2,704개 인핸서 중 2,003개(74%)가 **pan-chondrogenic**(사지·체간 공통), 483개(18%)가 **사지 특이적**, 218개(8%)가 **체간 특이적**이었다. 연골세포 인핸서는 대부분 E9.75~E11.5 사이 크로마틴 접근성이 열렸으며, 이 시기에 Sox9, Foxc1/2 발현이 시작됨을 시사한다.

**TF 결합 분석** 연골세포 인핸서에서 SOX9, MEF2C/D, FOX factor motif가 풍부하였고, CTCF, MAZ, MYOD1/MYOG/MYF6 motif는 고갈되었다. E13.5 사지 SOX9 ChIP-seq peak와 967개(39%) 인핸서가 오버랩되었고, 비활성 영역에서는 3.5%만 오버랩되어 SOX9 의존적·비의존적 인핸서를 모두 포착함을 보였다.

**TAD 기반 인핸서-유전자 연결** chondroTADs(n=357)은 평균 3.8개 인핸서/TAD를 포함(chondroEnhTADs는 2개/TAD, p=4.68e-23). chondroTADs 유전자는 골·연골 발달 GO term에 풍부하였고, chondroEnhTADs 유전자는 일반 발달 과정(Shox2, Hoxd, Tbx4 등)에 풍부하였다. 사지/체간 특이적 유전자는 대응하는 조직 풍부 인핸서를 가진 TAD에 위치하는 경향이 있었다.

**인간 신장 변이와 인핸서 연관** Longshanks 마우스 경골 길이 연관 8개 locus에서 73개 연골세포 인핸서(전체의 2.7%)가 확인되었고, Nkx3-2 locus의 N1 인핸서는 SNP를 포함하였다. 인간 GWAS non-coding mHVEL 1,771개 중 169개(9.5%)가 연골세포 인핸서와 오버랩되어 전체 신장 분산의 18.4%를 설명하였다. **연골세포 인핸서가 비연골세포 인핸서보다 신장 분산을 더 잘 설명**하였다.

**인핸서 기능 검증** Col2a1 locus에서 hs2697/hs2698 9.1 kb 삭제 시 체간에서 Col2a1 발현 20% 감소. Fgfr3 locus에서 hs2696 5.9 kb 삭제 시 사지·체간에서 Fgfr3 발현 75% 감소. Hhip locus에서 CE2-3 3.5 kb 삭제 시 사지에서 Hhip 발현 15% 감소. Nkx3-2 locus에서 CE1-N1 27.6 kb 삭제 시 사지 25%, 체간 37% Nkx3-2 발현 감소와 Sox9, Col2a1, Ihh 등 하류 연골세포 유전자 전반적 감소가 확인되었다.

---

## Perspective

본 연구는 태아기 전비대 연골세포의 전장 유전체 인핸서 지도를 최초로 제시한 획기적인 연구로, 다음과 같은 의의를 갖는다.

첫째, 2,704개 연골세포 인핸서 중 74%가 pan-chondrogenic이며, 나머지가 사지 또는 체간 특이적임을 보여, 골격 부위별 연골세포 분화 조절의 인핸서 기반 메커니즘을 규명하였다. SOX9가 39% 인핸서에 결합하지만, 나머지 61%는 SOX9 비의존적 인핸서로, 단일 TF 기반 인핸서 탐색의 한계를 넘어선 포괄적 접근의 중요성을 입증하였다.

둘째, 연골세포 인핸서가 인간 신장 GWAS 변이를 설명하는 기계적 프레임워크로 작용함을 보였다. 특히 chondroEnhTADs 인핸서가 chondroTADs 인핸서보다 신장 분산을 더 잘 설명하여, **연골세포 유전자가 아닌 일반 발달 유전자의 인핸서 변이도 골격 형질에 중대한 영향**을 미칠 수 있음을 시사한다.

셋째, 4개 locus(Col2a1, Fgfr3, Hhip, Nkx3-2)의 인핸서 삭제로 표적 유전자 발현 감소를 in vivo에서 직접 검증하여, 인핸서 변이가 골격 질환(예: Fgfr3 인핸서 변이 → CATSHL 증후군, Nkx3-2 인핸서 변이 → 단신증)의 원인이 될 수 있음을 입증하였다.

향후 과제로는 인핸서-프로모터 3D 상호작용(Hi-C/HiChIP)을 통한 표적 유전자 매핑 정확도 향상, 연골세포 아집단(조기/성숙/비대)별 인핸서 동적 변화 규명, 그리고 인간 연골세포에서의 인핸서 기능 검증이 필요하다.

---

*Processed by **DeepSeek V4 Flash** (OpenCode Go) on 2026-06-07*
