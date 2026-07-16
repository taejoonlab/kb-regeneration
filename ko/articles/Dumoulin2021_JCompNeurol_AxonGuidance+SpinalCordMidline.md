---
tags: [2026-07]
extract: 2026-07-16
---

# Axon guidance at the spinal cord midline—A live imaging perspective

## Citation (NLM)
Dumoulin A, Zuñiga NR, Stoeckli ET. Axon guidance at the spinal cord midline—A live imaging perspective. J Comp Neurol. 2021;529(10):2517-2538. doi:10.1002/cne.25107

**DOI:** [https://doi.org/10.1002/cne.25107](https://doi.org/10.1002/cne.25107)

---

## Background

신경 회로 형성 과정에서 축삭(axon)은 여러 중간 표적(choice point)을 순차적으로 지나가며, 각 지점에서 성장원뿔(growth cone)은 계속 나아가기 위해 유인에서 반발로 반응성을 전환해야 한다. 발생 중인 척수에서 배측 dI1 교련 사이신경세포(commissural interneuron)는 고전적 모델로, 그 축삭은 복측 정중선(바닥판, floor plate, FP)을 가로질러 빠져나온 뒤 반대편 경계를 따라 문측(rostral)으로 회전한다. 수십 년간 그 기전은 서로 다른 시점에 고정된 조직의 여러 성장원뿔 "스냅샷"이나 "open-book" 표본 배양에서 추론되어 왔다. 그러나 open-book 배양은 인공산물(특히 FP 출구에서의 비정상적 overshooting)을 유발하며, 스냅샷으로는 단일 성장원뿔이 중간 표적에 도착하고 떠나는 동적 거동을 관찰할 수 없다.

이 Toolbox 논문은 병아리 배아에서 온전한(intact) 척수를 배양하여 개별 dI1 축삭이 원래 환경 내에서 정중선을 항행하는 과정을 라이브 이미징할 수 있는 새로운 ex vivo 표본을 제시한다.

---

## Key Experiment Methods

1. **In ovo 전기천공(electroporation)**: HH17-18 병아리 신경관에 Math1::tdTomato-F(dI1 특이 표지)와 β-actin::EGFP-F(주변 환경) 도입, FP 표지용 Hoxa1::EGFP-F 및 Fzd3 knockdown용 miFzd3 구성체 사용.
2. **온전한 척수 절편(intact spinal cord) 해부**: HH22 배아에서 복·배측 정중선과 DRG를 보존한 채 분리, 저융점 아가로스에 복측이 아래로 향하도록 유리바닥 접시에 포매; 기존 **open-book 표본**(HH24)과 비교.
3. **라이브 이미징**: 도립 스피닝디스크 공초점 현미경(37°C, 5% CO2)으로 5~15분 간격 z-stack을 최대 24시간, 20x·40x 배율로 획득.
4. **가상 추적(virtual tracing, MtrackJ/Fiji)**: 단일 Math1 양성 성장원뿔을 추적하여 통과 시간과 국소 성장 속도 추출; **kymograph 및 temporal-color projection** 분석.
5. **면역조직화학/whole-mount 염색**: 패터닝 마커(Lhx2, Islet-1, Nkx2.2, Hnf3β), 유도 신호(Shh, NrCAM), laminin(기저판/수막), cleaved caspase-3(세포자멸사) 염색.
6. **Shh 강도 측정**: 요추 vs. 흉추 수준의 FP에서 gradient 보존 여부 평가.

---

## Results

- 온전한 척수 배양에서 dI1 축삭은 24시간 동안 FP를 가로지르고 문측으로 회전하여 반대편 복측 funiculus를 정상적으로 형성했으며, in vivo 궤적을 충실히 재현했다. Math1 양성 동측(ipsilateral) 아집단도 관찰되었다.
- 1일 ex vivo 후에도 조직 완전성이 유지되었다: 패터닝 마커, FP의 삼각형 형태, 수막/기저판(laminin), 미측→문측 Shh gradient가 모두 보존되었고 세포자멸사는 최소였다.
- 반면 open-book 배양은 심각한 인공산물을 보였다: 축삭의 91 ± 6%가 반대편 FP 경계를 넘어 overshooting(온전한 표본에서는 0%, 98 ± 2%가 문측 회전), Shh gradient 소실, 수막 부재, 기저판 변형·단절, 복측의 대량 세포자멸사.
- 시간 정량화: dI1 축삭은 전체 FP를 가로지르는 데 5.6 ± 1.4시간, 문측 회전에 1.4 ± 1.0시간(총 6.9 ± 1.8시간)이 걸렸다. FP 전반부와 후반부 간 차이는 없었다. 회전 시간(통과 시간은 아님)은 시간이 지날수록 유의하게 감소하여, 먼저 회전한 개척(pioneer) 축삭이 뒤따르는 축삭의 회전을 돕는 것으로 시사되었다.
- 성장원뿔은 가속-감속 pulse가 요동치는 성장 패턴을 보였다. FP 출구에서 성장원뿔 면적이 일시적으로 확대되었다(FP 내부 ~45 μm² 대비 ~105 μm²)로 in vivo 값과 일치.
- 100%의 성장원뿔이 회전 직전 문측·미측으로 긴 사상위족(filopodia)을 뻗었고, 16 ± 8%는 회전 직전 일시적으로 분할되었다. 고배율 3D 이미징에서 FP 통과 중 배복측(dorso-ventral) 방향의 동적 돌기(최대 13 μm)가 관찰되었다.

---

## Perspective

이 방법은 개별 교련 성장원뿔을 원래의 3D 환경 내에서 척수 정중선 choice point를 통과하는 동안 추적할 수 있는 안정적이고 인공산물이 없는 ex vivo 플랫폼을 제공한다. 성장 속도, 형태 변화, 비정상 거동(정체, 잘못된 회전 등)을 측정할 수 있어 정적 스냅샷과 open-book 배양이 포착하지 못하는 정보를 얻을 수 있다. 또한 중간 표적인 FP의 능동적 참여와 회전 중 축삭-축삭 협력 가능성을 밝혔다. 저자들이 지적한 한계는 특히 저배율 3D에서의 해상도 제약으로, 통과 중 성장원뿔의 미세한 형태 변화를 놓칠 수 있다는 점이다. 이 접근법은 수용체 전환(Fzd3, Slit, Shh, Wnt 반응성 등)의 정밀한 타이밍과 choice point에서의 축삭 간 상호작용 연구에 새로운 길을 열며, 더 성숙한 배아(최소 HH24-25)에도 적용 가능하다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
