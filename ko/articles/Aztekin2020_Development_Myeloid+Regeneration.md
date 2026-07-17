---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
---

# The myeloid lineage is required for the emergence of a regeneration-permissive environment following Xenopus tail amputation

## Citation (NLM)
Aztekin C, Hiscock TW, Butler R, De Jesús Andino F, Robert J, Gurdon JB, Jullien J. The myeloid lineage is required for the emergence of a regeneration-permissive environment following Xenopus tail amputation. Development. 2020;147(3):dev185496. doi:10.1242/dev.185496

**DOI:** [https://doi.org/10.1242/dev.185496](https://doi.org/10.1242/dev.185496)

---

## Background
재생 가능한 척추동물은 비재생 동물보다 염증을 더 빠르게 억제하는 것으로 여겨진다. 면역계, 특히 골수계(myeloid lineage)는 도롱뇽·제브라피시·마우스에서 부속지 및 심장 조직 재생을 주로 ECM 리모델링, 조직융해(histolysis), 혈관신생, 세포자멸사 제거를 통해 긍정적으로 촉진할 수 있다. 그러나 재생 능력이 높은 동물에서 염증 상태가 조절하는 세포 사건은 잘 정의되지 않았다.

*Xenopus laevis* 올챙이는 꼬리를 재생하지만 특정 발생 단계에서 일시적으로 이 능력을 잃는다. 저자들은 이전에 이 상실이 상처 표피를 형성하고 성장인자를 분비하는 재생 조직화 세포(ROC)의 이동 실패 때문임을 밝혔다. 본 연구는 자연 발생하는 재생 가능·불가능 올챙이 단계를 이용하여 골수계가 재생 허용 환경(regeneration-permissive environment) 조성에 어떻게 기여하는지 규명한다.

---

## Key Experiment Methods
1. **골수계 제거(상보적 3가지 방법):** 클로드로네이트 함유 리포솜(Clodrosome vs. Encapsome 대조) 복부 정맥 주입; slurp1l:NTR + metronidazole(MTZ) 유전적 제거; spib의 CRISPR/Cas9 모자이크 녹아웃.
2. **재생 분석:** 꼬리 약 30-50% 절단, 7 dpa에 재생 지수로 채점; Fiji로 재생 꼬리/몸통 길이 비율 측정.
3. **RT-qPCR**(ef1α/gapdh 정규화)로 제거 확인.
4. **조직 리모델링**을 "리모델링 지수"(절단면 길이 / 후방 체절 조직 길이)로 정량.
5. **세포자멸사 분석:** LysoSensor(세포질 산성도) 사용, caspase-3 IHC로 검증; 세포자멸사 억제제 NS3694와 히알루론산(HA) 합성 억제제 4-MU로 상위성(epistasis) 분석.
6. **ROC 이동 분석:** pbin7Lef:GFP 리포터 및 anti-EGFP 염색.
7. **scRNA-seq 재분석:** Aztekin 등(2019) 꼬리 세포 아틀라스로 골수 아집단과 차등 존재비 특성화.
8. **면역억제 약물 구제:** 재생 불가능 올챙이에 FK506, Celastrol 처리.
9. **성체 개구리 실험:** FV3 바이러스 또는 열처리 사멸 *E. coli* 자극 후 복강 백혈구를 유세포 분석으로 선별.

---

## Results
- **골수계는 재생에 필수적:** 세 가지 제거 전략(클로드로네이트, slurp1l:NTR/MTZ, spib CRISPR) 모두 재생 가능 올챙이의 꼬리 재생을 감소시켰다. (단, slurp1l 프로모터는 절단 시 ROC를 포함한 비골수 세포에서도 활성화되어 후기 단계 사용에 주의 필요.)
- **골수계는 세포 사건의 계층을 조절:** 제거 시 조직/ECM 리모델링 감소, 절단 유도 세포자멸사 증가, 절단면으로의 ROC 이동 손상.
- **상위성 분석:** HA 합성 차단(4-MU)은 리모델링을 감소시켰으나 세포자멸사에는 영향 없음; 세포자멸사 차단(NS3694)은 리모델링을 감소. 이는 골수계 활성이 상류에 위치하여 세포자멸사 → HA 매개 ECM 리모델링 → ROC 재배치를 조절함을 나타냄.
- **염증성 vs. 회복성 골수 균형:** 꼬리 아틀라스는 두 골수 클러스터를 포함 — 염증성(예: tnf 농축)과 회복성(예: arg1, mmp1/9 농축). 온전한 꼬리에서는 재생 능력과 무관하게 비율이 유사했으나, 1 dpa에서 재생 가능 올챙이는 회복성 골수 활성이, 불가능 올챙이는 염증성 활성이 우세.
- **면역 억제가 재생 능력 회복:** 재생 불가능 올챙이에 FK506 또는 Celastrol 처리 시 염증성 골수 유전자 발현 감소, 세포자멸사 저하, 리모델링 가능, (약간 지연된) ROC 이동을 허용하여 일부 올챙이에서 재생 구제. 4-MU 또는 NS3694 병용은 이 구제를 무효화.

---

## Perspective
본 연구는 재생 가능한 척추동물에서 골수계가 꼬리 재생에 필수적임을 입증하고, 골수계가 조절하는 세포 사건의 순서(세포자멸사 조절, HA 의존 ECM 리모델링, ROC 재배치)를 정의한다. 이들이 함께 재생 허용 환경을 조성한다. 재생 불가능성은 염증성에서 회복성 골수 활성으로의 전환 실패로 특징지어지며, 약리학적 면역 억제가 재생 능력을 부분적으로 회복시킬 수 있다.

의의: 염증성 골수 세포 억제가 마우스 손상 모델(척수 손상부터 모발 재생, 흉터 감소까지)에서 회복을 지지하므로, *Xenopus*는 회복성 골수 활성을 촉진하는 약물/유전자 스크리닝에 적합한 시스템을 제공한다. 한계: 제안된 계층은 일방향적·상관적이며 직접 인과관계와 상호 crosstalk는 미검증; 염증성 골수 세포가 재생을 직접 차단하는지 불확실; 호중구 클러스터 미포착; LysoSensor가 일부 비자멸사(고pH) 세포를 표지할 가능성. 특수화된 상처 표피 형성에서 골수계의 보존된 역할(아홀로틀 사지, 마우스 손가락 끝, 제브라피시 지느러미)이 제안되나 종간 검증이 필요하다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
