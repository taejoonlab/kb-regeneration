---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p04.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# SOX2 regulates common and specific stem cell features in the CNS and endoderm derived organs

## Citation (NLM)
Hagey DW, Klum S, Kurtsdotter I, Zaouter C, Topcic D, Andersson O, Bergsland M, Muhr J. SOX2 regulates common and specific stem cell features in the CNS and endoderm derived organs. PLoS Genet. 2018;14(2):e1007224. doi:10.1371/journal.pgen.1007224

**DOI:** [https://doi.org/10.1371/journal.pgen.1007224](https://doi.org/10.1371/journal.pgen.1007224)

---

## Background

줄기세포는 자기재생 능력과 여러 분화 계통을 생성하는 능력을 공유하지만, 서로 다른 장기의 줄기세포는 각기 다른 유전자 발현 프로파일을 가진다. 전사인자 SOX2는 만능세포부터 성체 장기 특이적 줄기세포에 이르기까지 다양한 줄기세포 집단에서 발현되며 유지, 증식, 세포 운명을 조절한다. 그러나 SOX2가 서로 다른 줄기세포 집단에서 유사한 기전으로 이러한 기능을 수행하는지는 알려져 있지 않았다.

이를 규명하기 위해 저자들은 중추신경계(대뇌피질, 척수)와 내배엽 유래 장기(위, 폐/식도)에서 SOX2의 게놈 결합과 유전자 발현을 비교하여, SOX2가 공통(핵심) 및 세포유형 특이적 줄기세포 프로그램을 어떻게 조절하는지 검증하였다.

---

## Key Experiment Methods

1. E11.5 마우스 폐/식도 및 위 조직에 대한 SOX2 ChIP-seq, 기존 공개된 E11.5 대뇌피질·척수 SOX2 ChIP-seq와 비교; SISSRS로 peak calling, MACS14로 검증.
2. E11.5 대뇌피질, 척수, 위, 폐/식도에서 FACS 분리한 SOX2-GFP+ 세포의 RNA-seq(Smart-seq2).
3. SOX2 협력 인자 후보 규명을 위한 모티프 농축(HOMER, CentriMo) 및 모티프 간격 분석.
4. SOX2와 OTX1, FOXA1, ZEB1의 물리적 상호작용을 검증하는 공동면역침전(DNase I 처리 유무).
5. P19 세포에서 cis-조절 모듈(CRM) luciferase 리포터 트랜스활성화 분석.
6. SOX2 결합 CRM의 조직 특이적 인핸서 활성을 검증하는 형질전환 제브라피시 Tol2-e1b-GFP 리포터 분석.
7. 병아리 척수 in ovo 전기천공 및 마우스 위 explant 전기천공을 통한 SOX2 수준 조작(과발현 또는 우성음성 dnSoxB1/shRNA)과 BrdU 증식 분석; Wnt/β-catenin 이펙터(LEF1GBM, dnTcf7L2)와의 상위성(epistasis) 분석.

---

## Results

- SOX2는 네 조직 모두에서 유사한 핵심 모티프에 결합하지만, 표적 영역은 주로 세포유형 특이적이었다(폐/식도 503, 위 962, 대뇌피질 6357, 척수 2313 peaks). 두 배엽 모두에서 공유된 peak은 232개, 네 조직 모두에서 공유된 peak은 32개에 불과했다.
- SOX2 결합은 같은 배엽 내에서 더 유사했으며, 배아 내배엽 결합은 성체 위와, 대뇌피질/척수 결합은 ESC 유래 NPC와 유사했다.
- 세포유형 특이적 SOX2 peak은 각기 다른 협력 인자 모티프가 농축되었다: OTX1(대뇌피질), PAX2(척수), GATA4/HNF1A(위), FOXA1/TEAD4(폐/식도); 공유 peak은 ZEB1과 ZBTB33 모티프가 농축되었다.
- SOX2는 OTX1(DNA 의존적, HMG+B 도메인 경유), FOXA1, ZEB1(C-말단 경유)과 물리적으로 상호작용한다. 기능적으로 OTX1은 CNS CRM을 상가적으로 활성화, FOXA1은 위 CRM을 약하게 활성화, ZEB1은 공유 CRM을 억제하였다.
- 세포유형 특이적 SOX2 결합은 해당 조직에서 특이적으로 발현되는 유전자(예: "cell differentiation in spinal cord") 주변에 농축된 반면, 공유 결합 유전자는 일반적 줄기세포 GO 용어("regulation of stem cell proliferation/differentiation")에 농축되었다.
- SOX2 결합 CRM은 제브라피시에서 조직 특이적 인핸서로 기능하였다(공유 CRM 12개 중 11개가 두 조직에서 활성, CNS 특이 7개 중 5개가 CNS에서, 내배엽 특이 7개 중 4개가 내배엽에서 활성).
- 높은 SOX2 수준은 척수와 위에서 증식을 감소(BrdU+ 세포 감소)시키고, SOX2 활성 감소는 증식을 증가시켜 대뇌피질과 동일한 양상을 보였다. Ccnd1(Cyclin D1) 프로모터는 네 조직 모두에서 SOX2에 결합되며, SOX2는 Wnt/β-catenin 신호를 (GRO/TLE 공억제 경유) 상쇄함으로써 작용하는데 이는 대뇌피질·척수·위에서 보존된 기전이다.

---

## Perspective

본 연구는 단일 전사인자 SOX2가 (각 조직에서 발현되는 조합적 협력 인자를 통해) 세포유형 특이적 유전자 프로그램과, Ccnd1/Wnt-β-catenin 축을 통한 증식 억제를 중심으로 하는 보존된 핵심 줄기세포 프로그램을 동시에 구동함을 보여준다. CNS/척수 생물학 측면에서, SOX2가 비신경 줄기세포와 공유되는 기전을 통해 신경 전구세포를 느린 증식 상태로 유지하는 방식을 명확히 한다. 한계로는 FACS 분리 집단의 비표적 세포 오염 가능성, 과발현 단백질을 이용한 체외 공동면역침전(교량 인자 개입 여지), 종간(제브라피시) 리포터 검증 의존이 있다. 향후 조직 특이적 SOX2 활성을 규정하는 조합적 협력 인자 코드의 완전한 규명이 필요하다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
