---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
---

# Secreted inhibitors drive the loss of regeneration competence in Xenopus limbs

## Citation (NLM)
Aztekin C, Hiscock TW, Gurdon J, Jullien J, Marioni J, Simons BD. Secreted inhibitors drive the loss of regeneration competence in Xenopus limbs. Development. 2021;148(13):dev199158. doi:10.1242/dev.199158

**DOI:** [https://doi.org/10.1242/dev.199158](https://doi.org/10.1242/dev.199158)

---

## Background
양서류 사지 재생은 도롱뇽에서 주로 규명된 특수화된 상처 표피(정단상피모자, AEC)에 의존한다. 이 조직의 부재 또는 미성숙이 포유류를 포함한 고등 척추동물의 재생을 제한한다는 가설이 있으나, 재생 불가능 동물에서 그 형성을 막는 요인은 잘 이해되지 않았다. AEC는 발생기 사지싹의 정단외배엽능선(AER)과 유사하다고 제안되었으나(둘 다 Fgf8 발현), 상충되는 데이터로 인해 AEC 세포가 새로운 전사 프로그램을 사용하는지 발생기 AER 프로그램을 재배치하는지 불분명했다.

*Xenopus laevis*는 양막류처럼 사지를 발생시키고 검출 가능한 AER를 지니며 사지 재생을 보이는 유일한 흔한 모델 생물로, 발생 과정에서 재생 능력을 점진적으로 상실한다(가능 NF ~52-54; 제한 NF ~55-57; 불가능 NF ~58 이상). 재생 능력은 절단 위치에도 의존한다(뼈나 근위/연골형성 부위 절단 시 감소). 저자들은 scRNA-seq과 생체외(ex vivo) 재생 사지 배양으로 상처 표피 형성의 세포 프레임워크와 그 실패를 규명했다.

---

## Key Experiment Methods
1. **scRNA-seq 아틀라스**(42,348 세포, 조건당 2회 이상 반복, 세포주기 보정): 발생 중 온전한 뒷다리(NF ~52, ~54, ~56)와 재생 가능(NF ~52-53), 제한(NF ~55-56), 불가능(NF ~58-60) 단계의 5 dpa 절단 사지 + 반대측 대조; 약 60개 클러스터 주석. 인터랙티브 플랫폼 제공.
2. **전사체 비교:** AER(발생기 Fgf8+ 표피 세포) vs. AEC(5 dpa Fgf8+ 표피 세포), 그리고 꼬리 ROC와의 비교.
3. **생체외 재생 사지 배양** 프로토콜: 생체 내에서 불가능한 약물 스크리닝, 공동배양, 조건배지 실험 수행.
4. **소분자 경로 억제제 스크리닝**(SU5402/FGF, LDN193189/BMP, ICRT3/WNT, SB431542/TGFβ, DAPT/NOTCH)을 외식편(explant)에 적용, HCR in situ로 Fgf8.L 판독.
5. **EdU 도입**으로 AER 세포가 세포분열로 생기는지 검증; Lgr5.S → Fgf8.L 궤적의 인자 분석.
6. **공동배양 및 조건배지** 실험(가능 + 불가능 외식편)과 anti-NOGGIN / anti-IgG 항체 구제.
7. **생체 내 비드 이식:** anti-NOGGIN, FGF10, FGF10+NOGGIN을 절단면에 이식; 연골형성 제한을 위한 tip 외식편 배양; Alcian Blue 조직학.

---

## Results
- **AEC = 재배치된 AER, 새로운 상태 아님:** AEC(5 dpa)와 발생기 AER의 Fgf8+ 표피 세포는 전사체적으로 매우 유사하고 단일 클러스터로 응집되며, 둘 다 대부분 극성화된 입방형 기저세포 단층으로 나타남; 주된 차이는 신호 중심 잠재력이다. 사지 AER 세포와 꼬리 ROC는 유사하나 동일하지 않다(부속지 재생은 맥락 의존적).
- **AER 세포 존재비가 재생 결과와 상관:** 5 dpa에 가능 올챙이는 AER 세포가 풍부, 제한 올챙이는 제한적, 불가능 올챙이는 거의 부재. AER 세포만이 여러 리간드(FGF, BMP, WNT, DELTA, TGFβ)를 고수준으로 공동 발현; Fgf8 단독으로는 잠재력을 구분하지 못함.
- **손상 유도 중간엽 가소성:** 절단 시 섬유아세포 아집단이 탈분화/배아싹 및 원위 전구세포/연골형성 유전자(Sall4, Kazald1, Grem1, Shh, Msx1, Fgf10, Sox9)를 상향 조절; 그 정도는 AER 세포 존재비와 상관.
- **AER 세포 형성은 여러 경로 필요**(FGF, BMP, WNT 및 TGFβ, NOTCH)를 외식편 억제제 스크리닝으로 입증; AER 세포는 대체로 **세포분열 없이**(~40% EdU+) 단계적 Lgr5+ → Fgf8+ 기저 표피 궤적을 통해 형성 가능.
- **분비 억제인자가 AER 형성 차단:** 재생 불가능 외식편과의 공동배양 또는 그 조건배지가 가능 외식편의 AER 세포 형성을 차단 — 촉진인자 결핍이 아닌 지배적 억제 효과. (후기 단계에 농축되는) 연골형성 중간엽 세포가 BMP/WNT 길항제, 특히 **Noggin**을 발현. anti-NOGGIN 항체는 공동배양/조건배지에서 AER 형성을 구제하고 생체 내 재생을 경미하게 개선.
- **FGF10은 Noggin의 상류에서 작용:** FGF10은 근위 연골형성을 감소(FGFR 차단은 연장); FGF10 + anti-NOGGIN은 이소성 근위 Fgf8 발현 유도; FGF10 유도 AER 형성은 BMP 억제제/NOGGIN으로 취소; 생체 내에서 FGF10 + NOGGIN 공동 적재 비드는 FGF10 단독의 재생 촉진 효과를 소거.

---

## Perspective
조직 수준 기술을 넘어, 본 연구는 특수화된 상처 표피(AEC)가 재생 특이적 신규 현상이 아니라 발생기 AER 프로그램의 재배치임을 보인다 — 이는 포유류가 전사 프로그램을 보유하나 손상 후 재배치에 실패함을 시사한다. 재생의 핵심 장벽은 활성화 인자의 단순 결핍이 아니라 **연골형성 계통에서 분비되는 억제 인자(예: Noggin)의 농축**이다. FGF10은 부분적으로 연골형성과 그에 따른 Noggin을 억제하여 재생 능력을 회복시킨다.

의의: 세포외 환경 조작(분비 억제인자 제거) 또는 연골형성 제한이 고등 척추동물의 재생 잠재력을 회복하는 전략이 될 수 있다. 한계·향후 방향: anti-NOGGIN 단독은 생체 내 효과가 경미하여 추가 연골형성 억제인자(예: Chrdl1, Frzb)도 중화해야 함을 시사(또는 전달 한계 반영); 근위에서 유도된 AER 세포가 근위 배아싹을 지지할 수 있는지, 그리고 "원위 변환 규칙(rule of distal transformation)"과의 관계는 미해결 과제로 남는다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
