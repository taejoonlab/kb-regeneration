---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p08.txt
---

# Stem cell differentiation trajectories in Hydra resolved at single-cell resolution

## Citation (NLM)
Siebert S, Farrell JA, Cazet JF, Abeykoon Y, Primack AS, Schnitzler CE, Juliano CE. Stem cell differentiation trajectories in Hydra resolved at single-cell resolution. Science. 2019;365(6451):eaav9314. doi:10.1126/science.aav9314

**DOI:** [https://doi.org/10.1126/science.aav9314](https://doi.org/10.1126/science.aav9314)

---

## Background

담수 자포동물 폴립인 히드라(Hydra)는 모든 세포를 지속적으로 자가재생하며 작은 조직 조각으로부터 전신을 재생할 수 있어, 재생·줄기세포 생물학·신경계 기능 연구의 고전적 모델이다. 세 개의 줄기세포 계통(내배엽 상피, 외배엽 상피, 간질(interstitial)), 형태학적 세포 유형, 계통 관계는 잘 규명되어 있으나 세포 상태의 분자적 정의는 여전히 불명확했다.

저자들은 단일세포 RNA 시퀀싱을 적용하여 히드라 세포 상태의 완전한 분자적 다양성을 포착하고, 각 계통의 분화 궤적을 재구성하며, 세포 상태 특이화의 후보 조절자를 규명하고, 신경계의 공간적 분자 지도를 구축하고자 했다. 좌우대칭동물의 자매군이며 유전자 패밀리 구성이 대체로 보존된 히드라는 조상형 발생·신경생성 기전에 대한 진화적 기준점을 제공한다.

---

## Key Experiment Methods

1. 성체 *Hydra vulgaris* 폴립을 해리한 전체 조직의 Drop-seq 단일세포 RNA-seq(13개 라이브러리)와 형질전환 히드라의 FACS로 농축한 GFP+ 뉴런 라이브러리 2개; 약 25,000개 전사체(24,985개 분석, 세포당 중앙값 1,936 유전자/5,672 UMI).
2. de novo 전사체 및 유전체 참조에 리드 매핑, 그래프 기반 클러스터링, tSNE 시각화, 기존 표지자로 클러스터 주석; RNA in situ hybridization과 이중 형광 in situ hybridization(FISH)으로 검증.
3. 비음수 행렬 분해(NMF)로 공발현 유전자 모듈/메타유전자 규명 및 생물학적·기술적 doublet과 식세포작용 이벤트 탐지.
4. URD 소프트웨어로 분화 궤적 재구성(간질 및 수컷 생식선 계통은 분지형 tree, 상피·샘세포는 선형 oral-aboral 궤적); 모의 무작위 보행과 pseudotime/latent-time 순서화 사용.
5. 전체 히드라 ATAC-seq와 모티프 농축 분석(시작코돈 상류 5 kb 이내 peak) 및 Pfam/JASPAR 추론으로 각 메타유전자의 농축 전사인자 결합 모티프를 후보 조절자와 연결; 분리한 조직층의 TagSeq로 뉴런을 외배엽/내배엽 신경망에 배정; GFP 리포터 형질전환 계통으로 검증.

---

## Results

- 클러스터링은 세포를 계통별로 분리하고 각 계통 내 예상 집단을 회복했으며, 여러 분화 궤적이 tSNE에서 직접 관찰되어 줄기세포 클러스터가 분화된 자손과 연결되었다.
- 상피 궤적은 위치 의존적(oral-aboral) 유전자 발현을 드러냈고, 여기에는 Wnt·BMP·FGF 신호전달의 미규명 유전자가 포함되어 패턴형성 후보 조절자를 시사했다.
- 다능성 간질 줄기세포(ISC)는 대체로 세포 유형 특이 표지자의 부재로 정의되었으며(단일 고유 표지자 발견), 이는 편형동물의 cNeoblast와 유사하다. HvSoxC는 뉴런과 nematoblast로 전이하는 세포를 표지했다.
- URD 재구성 결과, 신경생성과 샘세포 분화는 공유 전구 상태(Myc3 및 Myb로 표지)를 거치며 nematogenesis와는 구별됨을 시사했다. 외배엽에서 생성된 이능성 샘/뉴런 전구세포가 mesoglea를 건너 내배엽 뉴런과 샘세포를 공급한다는 모델을 제안했다.
- 샘세포는 위치 의존적 transdifferentiation(zymogen → granular mucous gland cell)과 oral-aboral 발현 프로그램을 보였고, spumous mucous gland cell에서 oral-organizer 유전자(HyWnt1/3, HyBra1/2)가 확인되었다. 생식선 줄기세포 후보 표지자(HyFem-1/2)도 규명되었다.
- ATAC-seq + 모티프 분석으로 39개 메타유전자의 농축 모티프와 25개의 후보 조절자를 발견했으며, nematogenesis의 Pax-A, 샘세포 특이화의 RFX, 내배엽의 forkhead 모티프(Nematostella/좌우대칭동물과 보존) 등이 포함되었다.
- 신경계 분자 지도는 12개의 뚜렷한 뉴런 아형(내배엽 뉴런의 최초 분자 표지자 포함)을 공간적으로 배치하고 기존 신경 회로(RP1, RP2, CB)에 배정했으며, NDF1 및 Alpha-LTX-Lhe1a-like GFP 리포터 계통으로 검증했다.

---

## Perspective

본 연구는 히드라 세포 상태, 분화 궤적, 후보 유전자 조절 인자, 공간 분해능 신경계 지도를 광범위하게 검증하여 포괄적 분자 아틀라스를 제공하며, 발생·진화·재생 생물학의 강력한 리소스를 확립한다. 재생 동물 전체의 분화 지형을 하나의 생활사 단계에서 비교적 적은 세포로 포착할 수 있음을 보여, 전신 수준의 교란 연구 가능성을 연다. 동적으로 재생하는 신경계 지도의 규명은 진화적 맥락에서 신경 가소성과 재생을 이해하는 데 특히 유의미하다. 저자들이 언급한 한계로는 제안된 공유 샘/뉴런 전구세포(vs. 초기 전사 이벤트를 공유하는 별개 전구세포)를 확증하기 위한 fate-mapping의 필요성, scRNA-seq 해석을 복잡하게 하는 강한 식세포성 상피세포, 그리고 기능적 검증이 필요한 궤적 추론 의존성이 있다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
