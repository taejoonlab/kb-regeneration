---
tags: [2026-07]
extract: 2026-07-16
---

# Specialized signaling centers direct cell fate and spatial organization in a mesodermal organoid model

## Citation (NLM)
Skoufa E, Zhong J, Hu K, Kahre O, Tsissios G, Carrau L, Herrera A, Dominguez Mantes A, Leleu M, Castilla-Ibeas A, Jang H, Weigert M, La Manno G, Lutolf M, Ros M, Aztekin C. Specialized signaling centers direct cell fate and spatial organization in a mesodermal organoid model. Sci Adv. 2025;11(48):eady7682. doi:10.1126/sciadv.ady7682

**DOI:** [https://doi.org/10.1126/sciadv.ady7682](https://doi.org/10.1126/sciadv.ady7682)

---

## Background

특화된 신호 중심(specialized signaling center)은 모르포겐(morphogen) 분비 능력으로 정의되는 독특한 세포집단으로, 발생과 재생 과정에서 일시적으로 형성되어 형태형성(morphogenesis)을 조율한다. 척추동물의 사지에서 표면 외배엽 세포는 신호 중심인 정단외배엽융기(apical-ectodermal ridge, AER)로 분화하며, AER는 FGF, BMP, WNT, TGFB, DELTA 등 여러 모르포겐 구배를 동시에 형성하여 그 아래에 있는 다능성 사지싹 중배엽(limb bud mesoderm)의 성장과 분화를 조절한다. AER 구배 영역을 벗어난 중배엽 세포는 연골세포(chondrocyte)와 섬유아세포(fibroblast)로 분화하는 반면, 비-AER 표면 외배엽 신호는 연골세포 분화를 억제하는 것으로 제안되어 왔다.

그러나 이러한 정교한 세포-세포 상호작용을 생체 내에서 연구하는 것은 조직·유전자 수준 관찰로 제한되며, 기존의 단순화된 사지 모델은 거의 전적으로 중배엽에만 초점을 맞추어 AER를 포함한 외배엽을 다룰 적절한 모델이 없었다. 이를 극복하기 위해 저자들은 마우스 배아줄기세포(mESC) 기반의 고효율 3D 오가노이드 모델—"budoid"—를 개발하였다. 이 모델은 AER, 표면 외배엽, 중배엽 특성을 지닌 세포들로 구성되어, 사지 형태형성 및 재생 과정에서 신호 중심-중배엽 상호작용을 대규모·정량적으로 분석할 수 있게 한다.

---

## Key Experiment Methods

1. **mESC 유도 분화**: 기존 프로토콜(SB431542 + BMP4)로 표면 외배엽 유사 전구세포를 유도한 뒤, BMP4 + FGF10 + Wnt 작용제 Chiron("BFC") 처리로 AER 유사 세포를 유도하여 이질적 2D 배양체 생성.
2. **리포터 라인**: Fgf8:tdTomato knock-in, Prrx1 인핸서:mVenus(사지싹 중배엽) 리포터 mESC 라인, 세포 추적용 항상성 발현 CAG:mVenus 라인.
3. **시간경과 scRNA-seq**(0, 3, 5, 7일) 및 클러스터 기반 세포유형 주석; 공개된 생체 내 E9.5–E12.5 마우스 사지 데이터셋과 비교/투영.
4. **3D budoid 생성**: U-바닥 저부착 플레이트에서 해리·응집; FGF8b + WNT3A 단기 처리로 대칭 파괴(symmetry breaking) 및 신장(elongation) 유도.
5. **생체 검증**: E12.5 마우스 앞다리/뒷다리의 원위부·근위부 세포를 동일 프로토콜에 적용.
6. **BMP 경로 조작**: NOGGIN 또는 LDN193189(억제) vs. 재조합 BMP4(활성화)로 연골형성 의존성 검증.
7. **FACS 세포 분리**: EpCAM/CD9로 중배엽(EpCAM-음성), 표면 외배엽 유사(EpCAM-고/CD9-고), AER 유사(EpCAM-고/CD9-저) 집단 분리.
8. **재조합 budoid**: 분리한 중배엽을 AER 유사, 표면 외배엽 유사 또는 중배엽 세포와 1:1 조합.
9. **면역염색/공초점**(TP63, TFAP2C, SOX9, TWIST1, E-cadherin) 및 131개 사지 발생 유전자에 대한 단일세포 해상도 **HybISS** 공간 in situ 시퀀싱.

---

## Results

- BFC 프로토콜은 AER(Sp6/Sp8/Fgf8/Bmp4/Wnt5a/Trp63), 표면 외배엽(Krt8/Wnt3/Wnt6), 초기 측판/사지싹 중배엽(Hand1/Hand2/Prrx1) 정체성을 지닌 세포가 주를 이루는 7일차 이질 배양체를 생성. AER 유사 세포는 생체 E9.5 AER와 가장 유사했으며 대부분 G1기(유사분열 비활성)로, 알려진 AER 특성과 일치.
- 세포들은 2D에서 3D "돔(dome)"으로 자가조직화하였고, TP63+ 세포가 외층을, AER 유사 세포가 끝/외측 바닥을, Prrx1enh+ 중배엽 세포가 중심부를 채웠다.
- 자유부유 응집체는 약 5%만 대칭을 파괴·신장했으나, FGF8b + WNT3A 단기 처리로 대칭 파괴 효율이 약 80%로 상승("budoid"). 일차 E12.5 사지 세포(특히 뒷다리 원위부)도 유사한 형태형성을 보임.
- scRNA-seq 결과 budoid는 다능성 사지싹 표지자(Msx1, Grem1, Fgf10)와 순차적 Hox 클러스터 활성화를 지닌 중배엽 세포가 풍부해졌고, 연골세포(Sox9, Col2a1)와 섬유아세포/힘줄세포/혈관주위세포 집단이 출현. 대칭 파괴 후 극성화된 SOX9+ 영역이 나타남.
- **대칭 파괴는 연골형성 매개이며 BMP 의존적**: NOGGIN/LDN193189는 신장을 억제하고 SOX9+ 세포를 감소시킨 반면, BMP4는 거의 모든 오가노이드를 신장시키고 완전히 SOX9+로 만들었다.
- 중배엽 농축 세포는 단독으로 FGF8b 단기 처리 시 대칭 파괴·신장이 가능했으나, AER 유사 또는 표면 외배엽 유사 세포는 단독으로 불가능했다.
- **재조합 budoid**: 일시적이고 소수인 AER 유사 세포도 한쪽 끝으로 극성화. AER 유사 재조합체는 강한 대칭 파괴·신장을 보인 반면, 표면 외배엽 재조합체는 원형을 유지(외배엽이 연골형성을 상쇄한다는 설과 일치). AER 유사 세포와 SOX9+ 세포는 서로 반대 극에 위치—국소적으로 연골형성을 억제하되 원거리에서는 허용함을 시사.
- **공간 시퀀싱(HybISS)**: 두 극성 영역을 확인—근위부 연골형성 영역(Sox9, Col2a1, Col9a1/2)과 사지싹 중배엽/섬유아세포 표지자(Prrx1, Msx1, Twist1, Lum, Col1a1, Col3a1) 및 높은 신호활성(Bmp4/7, Wnt5a/6, Rspo2/3, Axin2, Fgf7, Spry2/4)이 풍부한 원위부 영역. PCA에서 AER 유사 세포가 영역 간 극성화를 증가시킴을 확인.

---

## Perspective

이 연구는 생체 내에서 연구하기 어려운 상피성 신호 중심-중배엽 상호작용을 해부할 수 있는, 확장 가능하고 매트리젤 봉입이 불필요하며 재현성 높은 플랫폼을 제공한다. 핵심 발견은 AER 유사 신호 중심 세포가 비세포자율적으로 작용한다는 점이다: 즉 인접한 사지싹 중배엽·섬유아세포 정체성을 유지시키면서 국소적으로는 연골형성을 억제하지만, 조직 극성화를 강화하여 공간적으로 떨어진 연골 형성은 오히려 허용·촉진한다. 이는 신호 중심의 영향이 인접 세포뿐 아니라 원거리 집단까지 미쳐 전체 조직 조직화를 형성함을 정량적으로 보여, 기존의 조직·유전자 수준 모델을 확장한다.

신호 중심은 발생과 재생(예: 사지/부속지 재생)을 모두 조율하므로, budoid 시스템은 모르포겐 구배에 의한 세포 운명·패턴 조절을 연구하는 재생생물학의 다루기 쉬운 모델로서 의의가 있다. 실험당 수천 개의 budoid를 생성할 수 있는 처리량은 배아에서는 불가능한 통계적 견고성과 조합적 교란 실험을 가능케 한다.

저자들이 인정한 한계: 외배엽 세포가 3D에서 과소대표되고 유지가 어려워 최적화가 필요하며, budoid 세포유형은 주석 불일치와 단일세포 포획 편향에 부분적으로 기인하는 혼합 발생단계 프로파일을 보이고, Hox 활성화가 3D에서만 나타나는 이유가 불명확하며, budoid는 사지싹과 동등하지 않고 특정 측면(중배엽-연골 분화, AER 매개 신호)만 재현하는 단순화 모델이다. 사지 형태형성 이해에는 생체 연구가 여전히 표준이다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
