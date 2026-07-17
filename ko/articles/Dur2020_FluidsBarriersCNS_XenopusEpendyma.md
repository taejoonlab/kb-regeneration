---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p03.txt
---

# Xenopus에서 상의세포 섬모는 심장 박동성 힘과 무관하게 배아 CSF 순환과 뇌 발달을 주도한다 (In Xenopus ependymal cilia drive embryonic CSF circulation and brain development independently of cardiac pulsatile forces)

## Citation (NLM)
Dur AH, Tang T, Viviano S, Sekuri A, Willsey HR, Tagare HD, Kahle KT, Deniz E. In Xenopus ependymal cilia drive embryonic CSF circulation and brain development independently of cardiac pulsatile forces. Fluids Barriers CNS. 2020;17(1):72. doi:10.1186/s12987-020-00234-z

**DOI:** [https://doi.org/10.1186/s12987-020-00234-z](https://doi.org/10.1186/s12987-020-00234-z)

---

## Background

뇌척수액(CSF)은 중추신경계에 수력학적 보호를 제공하고 영양소를 전달하며 대사산물을 제거한다. CSF로 채워진 뇌실의 병리적 확장은 치명적인 질환인 수두증을 유발한다. 성인에서는 심장(박동성 동맥) 및 호흡 힘이 대량 CSF 흐름을 주도하는 반면, 상의세포 섬모는 벽 근처 흐름을 생성한다. 그러나 맥락총 형성과 능동적 CSF 분비 이전인 배아 뇌에서의 CSF 순환 역학은, 주로 배아 CNS에 in vivo로 접근할 수 있는 모델 시스템과 이미징 기술의 부족으로 인해 잘 이해되지 않고 있다. 새로운 데이터는 CSF가 초기 신경발생(신경전구세포 정체성 유지, 증식, 분화)에 중요함을 보여주며, 기존 제브라피시 연구는 심장 대 섬모의 상대적 기여에 대해 상충되는 견해를 제시했다.

Xenopus 올챙이 뇌는 포유류 뇌의 구획화(2개의 측뇌실, 제3뇌실, 제4뇌실)를 공유하지만 반투명하여 in vivo 이미징에 이상적이다. 본 연구는 Xenopus와 광간섭단층촬영(OCT)을 이용하여 배아 CSF 순환과 신경발달에서 심장 대 섬모 힘의 역할을 규명한다.

---

## Key Experiment Methods

1. **광간섭단층촬영(OCT)** 이미징(Thorlabs Ganymede 900 nm, ~2.2 μm 축방향 해상도)으로 stage 16부터 stage 49까지 Xenopus tropicalis 배아에서 뇌실 형태와 CSF 흐름을 연속적·비파괴적으로 in vivo 시각화.
2. 내인성 입자(ImageJ의 TrackMate)를 이용한 **CSF 흐름 속도 분석 및 입자 추적**과 뇌실 구획별 밀집 속도 추정을 위한 **가우시안 과정 회귀(GPR)** 후처리 파이프라인.
3. 초기(stage 30) 및 후기(stage 47-49) 단계에서 흐름을 추적하기 위한 **뇌실내 미세비드 주입**(0.81 / 4.61 μm 폴리스티렌).
4. stage 40 및 stage 46에서 심장/유출로의 미세절제에 의한 **심장 절제(cardiac ablation)**, 주정맥(cardinal vein) 흐름 소실로 확인; 절제 전후 CSF 흐름과 뇌실 크기 비교.
5. 뇌실내 NiCl2 또는 sodium orthovanadate 주입에 의한 **화학적 섬모 마비**.
6. c21orf59 모르폴리노를 이용한 **유전적 섬모 녹다운**(섬모 dynein arm 조립 차단; 섬모는 형성되지만 박동하지 못함).
7. 섬모에 대한 **면역조직화학**(glutamylated tubulin GT335, phalloidin); 신경전구세포/패터닝 마커 emx1, lhx1, en2에 대한 **in situ hybridization**.

---

## Results

- OCT로 신경관 형성 후(stage 19)부터 뇌실형성(ventriculogenesis)을 연속 추적할 수 있었다. 뇌실 공간은 문미측(rostrocaudal)으로 확장되었다; CSF 순환은 신경관 형성 약 12시간 후(stage 32)에 시작되어 극성화되었고, stage 39까지 4개, stage 46까지 5개의 흐름 장(flow field)을 형성했다.
- CSF 흐름은 미문측(caudo-rostral) 속도 구배를 보였다 — 미측(후방 제4뇌실 33.2 μm/s)이 문측(측뇌실 3.5 μm/s)보다 약 10배 빨랐다.
- stage 32 이전에는 주입된 비드가 정지 상태로 남아, 초기 뇌실 확장 동안 감지 가능한 CSF 이동이 없음을 확인했다.
- 후기 올챙이(stage 49)는 수도관(aqueduct)을 가로지르는 복잡한 양방향 구획 간 CSF 혼합을 보였다. 섬모 박동의 NiCl2 절제는 가장 빠른 제4뇌실 흐름을 정지시켜 섬모가 주도체임을 확인했다; 박동성 맥락총 흐름은 감지되지 않았다.
- **심장 절제**(stage 40/46)는 CSF 흐름 패턴, 속도, 뇌실 크기/모양, 뇌실 간(수도관) 혼합에 변화를 일으키지 않았다 — CSF 순환은 심장 힘과 무관하다. 약한 박동성 흐름만이 후기(stage 49)에 시상하부 근처에서 나타났으나 전체 순환에 기여하지 않았다.
- 다섬모세포(multiciliated cell)는 능형뇌(rhombencephalon) 등쪽 표면(가장 빠른 흐름)에서 발견되었다; 단섬모세포(monociliated cell)는 측면/복측 및 문측 표면에서 우세했다.
- **c21orf59 녹다운**(섬모 마비)은 CSF 순환을 폐지하고 수도관 협착(폐쇄성 수두증)을 유발했다. 문측 뇌실(측뇌실, 제3뇌실)은 미측 뇌실보다 불균형하게 작아, 섬모 주도 흐름이 문측 뇌 발달에 더 중요함을 보여주었다.
- 섬모 주도 흐름의 소실은 신경전구세포 공간 조직을 교란했다: 등쪽 종뇌의 emx1은 잘못 패터닝되었고(간뇌/중뇌로 확장되는 이소성 발현), lhx1(zli/시상)은 종뇌 영역에서 특이적으로 교란되었으며, en2(중뇌-후뇌)는 더 미측 마커로 검토되었다.

---

## Perspective

본 연구는 Xenopus에서 배아 뇌실계가 심장 박동성 힘과 무관하게 작동하는 상의세포 섬모 주도의 극성화된 CSF 흐름 네트워크를 형성하며, 이 섬모 주도 흐름이 문측 뇌 발달과 신경전구세포의 공간 조직을 조절함을 확립한다. 이는 배아 CSF/수두증 연구에서 성인에게만 관련된 심장 힘이 아니라 운동성 섬모로 주의를 전환시킨다. 반투명 Xenopus 배아를 OCT 및 GPR 기반 입자 추적과 결합한 것은 강력한 in vivo 플랫폼을 제공한다. 한계로는 모르폴리노 녹다운에 대한 의존(알려진 주의사항 포함), OCT 해상도 한계, 포유류에 비해 양서류 뇌의 구조적 단순성이 있어 포유류 선천성 수두증으로의 번역에는 검증이 필요하다. 이 발견들은 상의세포 섬모, CSF 역학, 신경전구세포 패터닝의 역할을 고려할 때 척수/CNS 발달과 관련이 있다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
