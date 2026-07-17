---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p04.txt
---

# CRISPR gRNA phenotypic screening in zebrafish reveals pro-regenerative genes in spinal cord injury

## Citation (NLM)
Keatinge M, Tsarouchas TM, Munir T, Porter NJ, Larraz J, Gianni D, Tsai HH, Becker CG, Lyons DA, Becker T. CRISPR gRNA phenotypic screening in zebrafish reveals pro-regenerative genes in spinal cord injury. PLoS Genet. 2021;17(4):e1009515. doi:10.1371/journal.pgen.1009515

**DOI:** [https://doi.org/10.1371/journal.pgen.1009515](https://doi.org/10.1371/journal.pgen.1009515)

---

## Background
포유류와 달리 제브라피시(zebrafish)는 척수손상 후 손상부를 가로지르는 축삭 연결을 기능적으로 재생한다. 포유류에서 지속적 염증은 회복에 해롭지만, 제브라피시에서는 전염증성 사이토카인이 빠르게 하향 조절되고 면역반응이 재생을 촉진한다. 선행 연구는 혈액 유래 대식세포가 축삭 재연결과 마비 회복에 필수적이며, 항재생성 호중구를 줄이고 il1b 등 전염증성 사이토카인을 완화하여 손상 환경을 조절함을 보였다. 그러나 대식세포가 재생 중 호중구와 il1b 발현을 억제하는 기전은 대부분 알려지지 않았다.

CRISPR/Cas9 접근은 급성 주입된 모자이크 돌연변이 배아에서 표현형 관찰이 가능하여 제브라피시 유전자 기능의 확장적 평가를 가능하게 한다. 합성 RNA Oligo CRISPR guide RNA(sCrRNA)는 효율적 표적화를 제공하나 활성이 가변적이고 예측 불가하다. 저자들은 guide를 생체 내에서 고활성으로 사전 선별하면 off-target 효과를 최소화하면서 강력한 표현형 스크리닝이 가능하리라 판단했다.

---

## Key Experiment Methods
1. 350개 이상의 sCrRNA를 RFLP(제한효소절편길이다형성) 분석으로 생체 내 활성 사전 선별; Cas9 절단부가 제한효소 인식부와 겹치도록 설계, 고활성 sCrRNA(haCR)를 효율 >90%로 정의.
2. haCR 효과를 직접 allele 시퀀싱(frameshift율)과 hexb 효소 활성 분석으로 검증.
3. 대식세포 관련 후보 30개 유전자에 대한 표현형 스크리닝: Xla.Tubb:DsRed transgenic 접합자에 haCR(유전자당 최대 2개) 주입; 3 dpf에 15번째 근절 부위 척수 자상/절개 손상.
4. 판독: 24, 48 hpl에 손상부를 가로지르는 축삭 "bridging" 비율을 맹검 채점.
5. 5개 hit 유전자(tgfb1a, tgfb3, tnfa, sparc, cst7)에 대해 안정 돌연변이 라인(F3 이형접합 incross) 생성하여 급성 표현형 검증.
6. tgfb1a/tgfb3 기전 분석: 대식세포(mpeg1:GFP), 호중구(anti-Mpx), il1b(qRT-PCR) 정량; Tgf-β 수용체 약물 억제(SB431542); Il-1β 억제 구제(caspase-1 억제제 YVAD); glial bridging(GFAP); 촉각유발 수영.

---

## Results
- 검사한 350개 sCrRNA 중 44%가 haCR(>90% 활성)이었고, 기존 in silico 설계 규칙은 관찰된 생체 내 활성과 약한 상관(R² ≈ 0.028–0.044)만 보여 생체 내 사전 선별의 가치를 강조.
- 두 haCR 병용 시 ~87% frameshift율; hexb 표적 단일 haCR로 효소 활성을 최대 80% 감소시켜 강력한 유전자 파괴 확인.
- 표적 30개 유전자 중 10개가 48 hpl에 축삭 bridging을 유의하게 감소시킨 hit(cst7, sparc, tgfb1a, tgfb3, tnfa, ifngr1, hspd1, tbrg1, serpinb1, mertk 포함); tnfa는 양성 대조군.
- 안정 돌연변이가 검사한 5개 중 4개(tgfb1a, tgfb3, tnfa, sparc)의 재생 손상을 확인, cst7은 확인 안 됨(위양성); 약물 Tgf-β 억제도 bridging을 감소시켜 Tgf-β 신호가 필수임을 확인.
- tgfb1a haCR/돌연변이 개체는 염증 해소에 실패: 48 hpl에 호중구 ~63-66% 증가, il1b 발현 ~120% 증가로 대식세포 소실을 표현형 모사, 반면 대식세포 수는 불변. tgfb3는 유의하지 않은 경향만.
- Il-1β 억제(YVAD)가 tgfb1a 돌연변이의 축삭 bridging 결함을 구제하여, tgfb1a가 적어도 부분적으로 호중구 수와 il1b 발현 조절을 통해 재생을 촉진함을 확립. tgfb3만(tgfb1a/sparc/tnfa 아님) glial bridging 손상을 보여 glial과 축삭 기전이 구분됨을 시사.

---

## Perspective
이 연구는 빠르고 확장 가능한 sCrRNA 표현형 스크리닝 패러다임을 확립했다. 핵심 혁신은 생체 내 RFLP 사전 선별로 고활성 guide를 식별하여, 유전자당 최소 2개 guide 접근으로 off-target과 위음성을 제한한 것이다. 척수 재생에 적용하여 기능적 친재생 유전자를 식별하고, 면역반응이 어떻게 회복을 촉진하는지에 대한 기전적 통찰을 제공했다: tgfb1a가 손상 후 염증(호중구, Il-1β)을 조절함으로써 대식세포 매개 재생의 이해를 확장했다. 한계로는 위양성(cst7), 일부 돌연변이가 급성 주입보다 약한 표현형을 보인 점(off-target 과장 가능성), 필수 발생 기능 유전자 스크리닝 불가(dmt3는 과도한 치사 유발), hit 유전자의 다른 면역 기능을 배제하지 못하는 고도로 표적화된 판독 등이 있다. 저자들은 transgenic 표지와 강력한 판독이 있는 어떤 생물학적 맥락에도 이 접근을 적용할 수 있으며, 향후 단일세포 RNA-Seq로 hit 유전자의 직접적 뉴런 작용과 환경적 작용을 구분할 수 있음을 언급한다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
