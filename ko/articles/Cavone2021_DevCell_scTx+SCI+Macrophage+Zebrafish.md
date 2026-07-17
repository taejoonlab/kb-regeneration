---
tags: [2026-07]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
---

# A unique macrophage subpopulation signals directly to progenitor cells to promote regenerative neurogenesis in the zebrafish spinal cord

## Citation (NLM)
Cavone L, McCann T, Drake LK, Aguzzi EA, Oprișoreanu AM, Pedersen E, Sandi S, Selvarajah J, Tsarouchas TM, Wehner D, Keatinge M, Mysiak KS, Henderson BEP, Dobie R, Henderson NC, Becker T, Becker CG. A unique macrophage subpopulation signals directly to progenitor cells to promote regenerative neurogenesis in the zebrafish spinal cord. Dev Cell. 2021;56(11):1617-1630. doi:10.1016/j.devcel.2021.04.031

**DOI:** [https://doi.org/10.1016/j.devcel.2021.04.031](https://doi.org/10.1016/j.devcel.2021.04.031)

---

## Background

중추신경계 손상 후 무양막류(어류, 양서류)는 척수 전구 세포에서 신경발생을 재개하지만 포유류는 그렇지 못하며, 포유류 척수 전구 세포는 대신 흉터 관련 별아교세포(astrocyte)를 생성한다. 제브라피시에서 선천 면역계의 활성화가 재생성 신경발생을 촉진한다는 것은 알려져 있으나, 면역세포가 발생 신호전달 경로(Wnt, Fgf, Shh, 도파민)를 재유도하여 간접적으로 작용하는지, 아니면 재생 특이적 기전을 통해 전구 세포에 직접 신호를 보내는지는 근본적으로 미해결 과제였다.

손상 부위에서 주로 대식세포가 생성하는 종양괴사인자(Tnf/Tnf-a)는 재생 특이적 신호 후보이다. 저자들은 특정 재생 촉진 대식세포 아형이 Tnf를 통해 뇌실-방사교세포(ependymo-radial glia, ERG) 척수 전구 세포에 직접 신호를 보내어, 손상 후 이들을 희소돌기아교세포생성에서 신경발생으로 전환시키는지 검증한다.

---

## Key Experiment Methods

1. FACS로 분리한 her4.3:GFP ERG 전구 세포의 단일세포 RNA-seq(손상 24시간 후 vs. 비손상 3 dpf 유충; 비손상 2,477개, 손상 1,203개 세포)와 손상 부위 mpeg1:GFP+ 대식세포 계통 세포의 scRNA-seq(비손상 3,767개, 손상 4,579개 세포), 비지도 클러스터링 및 차등발현 분석.
2. Tnf 단백질(항체), 대식세포(mpeg1:GFP), 운동신경 전구 ERG(olig2:DsRed)의 생체 내 삼중 표지로 공간적 근접성 평가.
3. 덱사메타손(면역억제)과 LPS(면역증강)를 이용한 면역 조작, tnfa 및 hdac1의 qRT-PCR, EdU 기반 증식 olig2:GFP+ 전구 세포 및 신생 mnx1:GFP+ 운동신경 계수.
4. Tnf 신호전달 기능 상실: 포말리도마이드(Tnf 방출 억제제), 급성 tnfa gRNA/Cas9, 안정 tnfa 돌연변이 계통, tnfrsf1a gRNA를 운동신경 및 HuC+ 신경발생으로 평가.
5. 정제된 her4.3:GFP+ ERG를 재조합 제브라피시 및 인간 TNF에 노출하는 ex vivo 실험(AP-1 억제제 SR11302 포함), mnx1 및 hdac1 발현 측정.
6. Hdac1 기능 검증: 범-Hdac 억제제 TSA와 Hdac1 선택적 mocetinostat, 그리고 독시사이클린 조건부 세포유형 특이적 Tg(her4.3:TetA;TetRe:YFP-dnhdac1) 우성음성 계통.

---

## Results

- scRNA-seq 결과 손상은 ERG 전구 세포에서 희소돌기아교세포생성에서 신경발생으로의 전환을 유도했다(신경모세포 상대적으로 약 480% 증가; gap43, sox11b, atf3 상향조절; plp1b, mbpa, mag 하향조절).
- Tnf 신호전달 유전자는 손상 후 전구 세포에서 특이적으로 농축·상향조절되었다: AP-1 구성요소 fosl2와 junbb, Tnf 조절 유전자 tnfaip2b, 수용체 tnfrsf1a(tnfrsf1a+ 전구 세포가 18%→45%로 증가). tnfa/b 리간드는 전구 세포에 없어 자가분비 신호를 배제했다. NF-kB1은 거의 검출되지 않았다.
- tnfa는 미세아교세포보다 주로 혈액 유래(포식성) 대식세포에서 발현되었다. 손상 활성화된 fth1a+ tnfa+ 대식세포 아집단이 손상 후 확장(19%→55%)되었고, 높은 카텝신 발현과 M1/M2 표지의 혼합을 보여 재생 촉진 대식세포 아형으로 정의되었다.
- 생체 내에서 대식세포와 과립상 Tnf 단백질이 olig2:DsRed+ ERG로부터 20 um 이내에 집중되어, 전구 세포가 대식세포 유래 Tnf에 노출됨을 확인했다.
- 면역 조작은 Tnf와 함께 신경발생을 조절했다: 덱사메타손은 tnfa, hdac1, 전구 세포 증식, 운동신경을 감소시켰고, LPS는 hdac1(1.7배), 운동신경 전구 세포(+57.5%), 신생 운동신경(+104%)을 증가시켰다. 비손상 유충에서 LPS 단독으로는 항상성 신경발생을 증가시키지 못했다.
- Tnf 신호전달 차단(포말리도마이드, tnfa gRNA, tnfa 돌연변이)은 재생성 신경발생을 약 33~53% 감소시켰다. tnfrsf1a 녹다운은 손상 유도 운동신경을 약 46~51% 감소시켰으나 발생 신경발생에는 영향을 주지 않아, 수용체가 재생에 특이적으로 필요함을 보였다.
- Ex vivo에서 제브라피시와 인간 TNF 모두 분리된 ERG에서 mnx1과 hdac1을 직접 상향조절했고, AP-1 억제제 SR11302는 Tnf 유도 hdac1을 소실시켜 AP-1 의존적 기전을 확립했다.
- Hdac1 기능이 필요했다: TSA와 mocetinostat는 전구 세포 증식과 신생 운동신경을 감소시키고 LPS 효과를 약화시켰다. 전구 세포 특이적 우성음성 hdac1은 손상 후 신생 HuC+ 신경을 약 43% 감소시켰다. In situ 혼성화는 유충 및 성체(2주) 척수 모두에서 손상 유도 hdac1 상향조절을 뇌실 ERG에서 확인했다.

---

## Perspective

본 연구는 손상 활성화된 재생 촉진 대식세포가 Tnf를 분비하고, 이 Tnf가 Tnfrsf1a를 통해 ERG 척수 전구 세포에 작용하여 AP-1을 활성화, hdac1을 상향조절하고 척수 손상 후 운동신경 신경발생을 유도하는 직접적이고 재생 특이적인 신호 축을 확립한다. 특히 tnfrsf1a는 발생 신경발생에는 불필요하나 재생성 신경발생에는 필요하며, 인간 TNF가 분리된 ERG를 신경으로 유도하기에 충분하다는 점은 재생 능력이 결핍된 포유류 척수에 대한 중개연구적 의의를 강조한다. 저자들이 인정한 한계로는 불완전한 억제(약 50%)가 추가적인 대식세포 유래 및 발생 신호의 존재를 시사한다는 점과, ERG 세포 내 신호전달을 완전히 규명하기 위한 추가 scRNA-seq 및 직접 전사인자 결합 분석의 필요성이 있다. 세포외 Tnf를 광범위하게 증강하면 복구의 다른 측면에 해로울 수 있으므로, 규명된 하류 노드(AP-1, Hdac1)가 보다 정밀한 치료 표적으로 제안된다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
