---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p05.txt
---

# A latent lineage potential in resident neural stem cells enables spinal cord repair

## Citation (NLM)
Llorens-Bobadilla E, Chell JM, Le Merre P, Wu Y, Zamboni M, Bergenstråhle J, Stenudd M, Sopova E, Lundeberg J, Shupliakov O, Carlén M, Frisén J. A latent lineage potential in resident neural stem cells enables spinal cord repair. Science. 2020;370(6512):eabb8795. doi:10.1126/science.abb8795

**DOI:** [https://doi.org/10.1126/science.abb8795](https://doi.org/10.1126/science.abb8795)

---

## Background

중추신경계(CNS) 손상은 효율적으로 회복되지 않으며 기능 장애가 대개 영구적으로 지속된다. 뇌와 척수에는 상주 신경줄기세포가 존재하지만, 손상 후에는 재생에 필요한 다계통 세포 대체 대신 주로 흉터 형성 성상세포를 생성한다. 척수에서 이러한 줄기세포 잠재력은 중심관을 둘러싼 잘 특성화된 상의세포(ependymal cell) 집단에 있으며, 이들은 평소 정지 상태이나 손상 시 거의 전적으로 성상세포를 생성한다. 한편 신경줄기세포 이식은 척수손상 후 회복에 유익한데, 이는 부분적으로 탈수초화된 축삭을 재수초화하는 희소돌기교세포를 공급하기 때문이다.

상의세포는 척수 희소돌기교세포와 발생학적 기원을 공유하므로, 저자들은 상주 상의세포에 희소돌기교세포 생성을 확장할 수 있는 잠재적(latent) 능력이 존재하며 이를 활성화하여 내인성 회복을 촉진할 수 있으리라 가정하였다.

---

## Key Experiment Methods

1. 상의세포를 농축한 척수 비신경 세포(~1100개)의 단일세포 ATAC-seq(scATAC-seq)를 동일 조직의 참조 scRNA-seq와 통합하여 클러스터 주석화.
2. 세포 클러스터 전반에 걸친 OLIG2/SOX10 결합부위 접근성(보존된 SOX10 인핸서 포함) 및 모티프 농축 분석.
3. Rosa-CAG-LSL-Olig2-IRES-tdTomato 마우스를 Foxj1-creER와 교배(Foxj1-Olig2-tdT), Foxj1-tdT 대조군과 함께 상의세포 특이적 조건부 OLIG2 발현 및 운명 지도화.
4. 배측 섬유단(dorsal funiculus) 절개 후 분리한 상의세포(비손상, 손상 후 1일 및 5일)에 대한 ATAC-seq 및 RNA-seq.
5. 운명추적된 tdTomato+ 상의세포 후손(비손상, 손상 후 2주 및 4주)의 droplet 기반 3′ scRNA-seq(~3000개), diffusion map 및 유사시간 분석.
6. 면역조직화학, RNAscope, 확장현미경(expansion microscopy), 전자현미경으로 희소돌기교세포 정체성 및 재수초화 평가.
7. 중등도 흉부 좌상(contusion) 모델과 생체 내 광유전학/전기생리학(피질척수로에 AAV9-CAG-ChR2-EGFP)으로 광유발 복합활동전위(optoCAP) 및 CST 전도속도 측정.

---

## Results

- scATAC-seq는 OLIG2와 SOX10가 발현되지 않음에도 이들의 결합 모티프(보존된 SOX10 인핸서 포함)가 상의세포에서 높게 접근 가능함을 보여, 희소돌기교세포 생성에 대한 잠재적(허용성) 염색질 상태를 시사하였다.
- 비손상 Foxj1-Olig2-tdT 마우스에서 강제 OLIG2 발현은 상의세포 정체성과 양립하였고 잠재 프로그램을 열지 않았다. 손상 후에는 OLIG2 발현 상의세포가 OPC 농축 OLIG2 결합부위에서 급속히 접근성을 획득(1일차 1.5배, 5일차 1.9배)하고 SOX10를 발현하였다.
- 손상은 다수의 상의세포 유래 희소돌기교세포 계통 세포(epOL)를 유도하였다: 4주차에 상의세포 후손의 약 30%가 SOX10+였고 12주차에는 약 11,000개(대조군 대비 40배 이상 증가). 이는 성상세포 흉터 형성을 희생하지 않고 병행되었으며 상의세포를 고갈시키지 않았다.
- 실질 성상세포에 강제 OLIG2를 발현시켜도 효율적인 희소돌기교세포 생성이 일어나지 않아, 상의세포가 특이적으로 허용성임을 보였다.
- scRNA-seq는 6개 클러스터를 규명하였다: 상의세포(EP) 클러스터, 3개의 성상상의(AE) 클러스터(성상세포 흉터 운명), 2개의 Sox10+ epOL 클러스터. Diffusion-map 유사시간 분석은 OLIG2가 초기 운명을 성상상의 대 희소돌기교세포 분기로 편향시킴을 보였고, epOL은 자가증폭 OPC 유사 상태를 포함한 단계적 발생 성숙 프로그램을 재현하며 MOL5/6(Ptgds+, Klk6−) 정체성으로 성숙하였다.
- epOL은 축삭을 재수초화하였다: tdTomato 막이 MBP 및 paranodal 마커 CASPR와 공존하였고, 확장현미경·전자현미경으로 조밀 수초 감쌈을 확인하였다.
- 좌상 모델에서 epOL은 훨씬 더 많았고(12주차 약 32,000개 SOX10+ 세포), 피질척수로 전도속도를 부분적으로 회복시켰다(비손상 대비 대조군 19.0% vs Foxj1-Olig2-tdT 27.9%). 전도속도는 CST 수초초 비율과 상관되었다.

---

## Perspective

본 연구는 성체 상주 신경줄기세포가 평소 발현되는 것보다 훨씬 큰 재생 잠재력, 즉 단일 전사인자(OLIG2)와 손상 신호에 의해 열릴 수 있는 잠재적·염색질 기반 희소돌기교세포 생성 프로그램을 보유함을 입증한다. 내인성 상의세포를 동원하여 세포이식(~30,000개)에 필적하는 수의 재수초화 희소돌기교세포를 생성하고 축삭 전도를 개선함으로써, CNS 손상 후 외인성 세포치료의 대안을 제시한다. 기전적으로 잠재 인핸서는 발생기 OLIG2 발현에서 유래했을 수 있으며 그 전개에는 손상 의존성 보조인자(예: Brg1)가 필요할 수 있다. 한계로는 유전적 OLIG2 유도가 필요하다는 점(아직 임상 적용 가능한 전달 전략 아님), 전도속도의 완전하지 않은 부분적 회복, 손상이 허용 조건으로 요구된다는 점이 있으며, OPC 유래 희소돌기교세포 생성과의 가산 효과는 향후 치료에서 시너지 접근 가능성을 시사한다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
