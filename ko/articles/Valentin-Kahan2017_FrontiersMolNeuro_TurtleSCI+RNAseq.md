---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p08.txt
raw_data:
  - "SRA: SRP082501"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Gene Expression Profiling in the Injured Spinal Cord of Trachemys scripta elegans: An Amniote with Self-Repair Capabilities

## Citation (NLM)
Valentin-Kahan A, García-Tejedor GB, Robello C, Trujillo-Cenóz O, Russo RE, Alvarez-Valin F. Gene Expression Profiling in the Injured Spinal Cord of Trachemys scripta elegans: An Amniote with Self-Repair Capabilities. Front Mol Neurosci. 2017;10:17. doi:10.3389/fnmol.2017.00017

**DOI:** [https://doi.org/10.3389/fnmol.2017.00017](https://doi.org/10.3389/fnmol.2017.00017)

---

## Background

척수손상(SCI)은 포유류에서 손상 부위 이하의 신경 기능을 영구적으로 상실시키며, 현재 가능한 치료법(중간엽/신경 줄기세포, BDNF 등 신경영양인자 유전자치료)은 유의한 기능 회복을 거의 이루지 못한다. 척수 재생 불능은 포유류, 조류, 대부분의 파충류가 공유하는 특징인 반면, 도롱뇽 같은 비양막류 척추동물과 (제한적이지만) 제브라피시는 재생이 가능하다.

슬라이더 거북(slider turtle)은 척수 자가복구를 통해 상당한(비록 불완전하지만) 기능 회복을 이루는 유일하게 알려진 양막류로, 손상 후 축삭 성장에 우호적인 세포 다리(cellular bridge)를 형성하고 결국 다시 걷는 능력을 회복한다. 거북은 이 능력을 가진, 포유류와 가장 가까운 근연군(악어·조류의 자매군)이므로, 왜 어떤 척추동물 계통은 척수를 재생하고 다른 계통은 못하는지를 묻는 데 전략적인 모델이다. 기존 분자 연구는 제한된 후보 유전자 집합만을 다루었고, 거북 SCI 반응의 유전체 규모 프로파일링이나 척추동물 간 폭넓은 비교 분석은 없었다. 본 연구는 Trachemys scripta elegans에서 SCI에 대한 유전체 전반의 유전자 발현 반응을 프로파일링하였다.

---

## Key Experiment Methods

1. 담수 거북(T. scripta elegans, 등딱지 ~6 cm, n=12)의 척수 절단; 수술 효과를 상쇄하기 위한 "sham 손상" 수술 대조군.
2. 수술 4일 후 병변 중심 4 mm 척수 절편을 채취(RNAlater), RIN>7.
3. RNA-seq: polyA 선택 라이브러리(ScriptSeq); Illumina GAIIX(2×100 PE) 및 MiSeq(2×75 PE) 시퀀싱; 데이터는 SRA SRP082501에 등록.
4. 매핑 레퍼런스: 근연종 Chrysemys picta 유전체(cpic v3.0.1)와 T. scripta의 de novo 전사체 어셈블리(Trinity)를 결합; TopHat/Cufflinks/Cuffmerge로 어셈블; 분기(divergent)/미매핑 리드는 별도 분석.
5. DESeq2로 차등발현 분석(DE 기준: FDR<0.1, 2배 이상 변화, 리드 ≥50).
6. 기능 분석: GO 농축분석(Blast2GO, Fisher 정확검정, FDR<0.05), 대사경로 농축(PANTHER), 단백질-단백질 상호작용 네트워크(STRING, 신뢰도 >0.7; Pajek Louvain 클러스터링; Gephi 시각화).
7. 인간, 마우스, 주머니쥐, 닭, 녹색 아놀도마뱀, Xenopus tropicalis, 제브라피시, 자라 등에 걸친 진화/직교유전자(ortholog) 분석(fastortho + 웹 DB).
8. 마우스(비재생) 및 Xenopus(재생성 올챙이 vs 비재생성 변태 후) 공개 RNA-seq를 이용한 종간 발현 비교.

---

## Results

- 손상 4일차에 1057개 유전자가 차등발현(덜 엄격한 기준에서는 1300개): 800개 상향, 257개 하향.
- 하향 유전자는 콜레스테롤 생합성(SQLE, HMGCS1, FDFT1, LSS), 글루탐산 시냅스 전달, 기타 소분자 생합성에 농축; 카드헤린·Wnt 신호전달도 포함.
- 상향 유전자는 크게 네 그룹: (1) 허혈/저산소 손상 및 활성산소종 반응; (2) 세포외기질(ECM) 재편(90여 개: MMP, TIMP, ADAM/ADAMTS, cathepsin, 인테그린 신호, 응고); (3) 세포 증식·사멸(220여 개: 유사분열, 세포주기 조절, 분화, 신경교형성, 신경관 발생, 혈관신생); (4) 면역반응·염증(180여 개: 케모카인, 보체, 백혈구/대식세포 이동, 항원제시).
- PPI 네트워크 클러스터링에서는 농축분석으로는 검출되지 않은 소규모 기능 그룹(탄수화물 이화, 소포 수송, 수초화)도 드러났다.
- 진화적 분포: 거의 모든 DE 유전자가 척추동물 전반에 존재하며, 재생 분류군에만 특이적인 유전자(거북과 제브라피시가 공유하는 "재생 유전자")는 발견되지 않았다. 유전자 부재는 대부분 불완전한 어셈블리나 계통 특이적 소실로 설명된다.
- 종간 발현 비교: 거북의 SCI 반응은 재생성(올챙이) Xenopus보다 마우스 및 비재생성(변태 후) Xenopus와 더 유사했으며, 재생성 Xenopus는 근본적으로 다른 패턴을 보였다(유전자의 약 60~70%가 상이한 거동).
- 거북 회복의 잠재적 후보 유전자: 무산소/탄수화물 대사 유전자(BPGM/BPGG, LDHB), 거북에서만 상향된 축삭유도/재성장 유전자(SEMA3A, SEMA4A, PAK1, MAP3K12), 거북에서 하향되지만 마우스에서 상향되는 KDR(VEGFR) 등.
- 이전에 주석되지 않은 전사 영역 8389개를 확인했으나 대부분 단백질 코딩 특성이 없었다.

---

## Perspective

본 연구는 자가복구가 가능한 양막류에서 SCI 반응을 유전체 규모로 처음 규명하고 이를 비교진화적 틀 안에 위치시켰다. 핵심적이면서 다소 의외인 결론은, 거북의 재생 능력이 보존된 조상 척추동물 형질의 잔존이 아니라 계통 특이적 혁신이라는 점이다. 즉 모든 양막류가 공유하는 유전자들의 발현을 본질적으로 비재생성인 유전적 배경 위에서 재조직하여 획득한 것으로 보인다(거북의 반응은 재생성 올챙이 Xenopus보다 비재생성 포유류·변태 후 Xenopus와 더 유사). 현대 파충류 계통(거북이 조룡류의 자매군)에 비추어, 거북의 복구를 조상 형질로 보려면 세 차례의 독립적 소실이 필요하므로 혁신 해석이 더 타당하다.

저자들은 무산소 내성, ECM 재편, 축삭 재성장 경로를 기능 회복의 유력 후보로 지목한다. 한계로는 단일 급성 시점(4일), 소수의 풀링 생물학적 반복, ~8% 분기 서열을 갖는 근연종 유전체(C. picta) 의존, 종간 비교에서 손상 시점·진행 속도의 차이 등이 있다. 거북과 제브라피시가 배타적 "재생 유전자"를 공유하지 않는다는 발견은 재생 계통들 간에 척수 복구의 분자 전략이 서로 다름을 시사하며, 단일 보존 재생 프로그램 가정에 주의를 요하고, 보다 시간분해적이며 기능 검증된 후속 연구의 필요성을 부각한다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- SRA: SRP082501


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
