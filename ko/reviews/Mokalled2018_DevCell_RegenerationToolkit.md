---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p06.txt
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
---

# A Regeneration Toolkit

## Citation (NLM)
Mokalled MH, Poss KD. A Regeneration Toolkit. Dev Cell. 2018;47(3):267-280. doi:10.1016/j.devcel.2018.10.015

**DOI:** [https://doi.org/10.1016/j.devcel.2018.10.015](https://doi.org/10.1016/j.devcel.2018.10.015)

---

## Overview

이 논문은 Developmental Cell에 실린 Perspective 형식의 리뷰로, 척추동물 조직 재생을 연구하기 위한 분자유전학적 도구(toolkit)를 개괄한다. 저자들은 재생생물학 전반을 망라하기보다는, 재생 현상을 시각화·특성화·조절하기 위해 사용되는 방법론과 앞으로 필요한 기술에 초점을 맞춘다.

동물마다 재생 능력은 크게 다르다. 플라나리아는 neoblast라는 체성 줄기세포에 기반해 몸 전체를 재생하며, 도롱뇽(newt, axolotl)과 제브라피시는 사지·지느러미·척수·심장·뇌 등 다양한 조직을 재생한다. 반면 포유류와 조류는 조직·나이 의존적으로 재생 능력이 제한되며, 특히 심장과 중추신경계(CNS)의 복구 능력이 낮다. 저자들은 대부분의 종이 재생을 가능하게 하는 유전적 기구는 유지하고 있으나 손상 후 이를 활성화하는 조절 기전을 잃었을 가능성 등을 논의한다.

리뷰는 재생 연구 모델 시스템, 실험적 접근법(세포 절제, 계통 추적, 이미징, 서열 기반 전략), 그리고 재생의 트리거와 브레이크를 찾는 유전자 조작 도구를 차례로 다룬다. 척수 재생은 axolotl 및 제브라피시에서, 그리고 포유류 손상 모델(pericyte 유래 반흔)에서 반복적으로 등장하는 핵심 사례로 제시된다.

---

## Key Topics

- **재생 모델 시스템**: 양서류(newt, axolotl, Xenopus), 경골어류(제브라피시, medaka, killifish, bichir), 마우스(실험용 계통, Acomys 등). 각 모델의 재생 능력, 세대 기간, 유전자 조작 가능성 비교.
- **세포 유형 특이적 손상/절제**: DTA/DTR(디프테리아 독소), 제브라피시의 nitroreductase/metronidazole 시스템을 이용한 특정 세포군 절제. 척수 손상에서 type A pericyte 특이적 Ras 불활성화(Glast-Rasless 마우스)를 통해 pericyte 유래 섬유성 반흔이 축삭 재생을 억제함을 규명한 사례.
- **계통 추적(lineage mapping)**: CreER 기반 tamoxifen/doxycycline 유도 계통 추적, Dre/rox를 이용한 이중 recombinase 정교화, clonal analysis, Brainbow 다색 표지, tissue clearing, 생체 실시간 이미징(light-sheet, two-photon), FUCCI 세포주기 리포터.
- **서열 기반 전략**: transposon mobilization, CRISPR-Cas9 기반 barcode 기록(GESTALT), single-cell RNA-seq, scGESTALT를 통한 전사체와 계통 정보의 통합.
- **재생의 트리거와 브레이크(유전자 조작)**: 유도성 프로모터, CRISPR/Cas9 표적 돌연변이, dCas9 기반 후성유전체 편집, 조건부 knockout, RNA/단백질 편집 도구. Sox2(axolotl 척수 재생), ctgfa(제브라피시 척수 재생), inhbaa(제브라피시 심장 재생) 등 재생 특이적 유전자 사례.
- **재생 유전자 조절**: 재생은 발생·항상성 유전자의 대규모 재활용이며 enhancer 등 조절 요소와 염색질 프로파일링이 핵심임을 강조.

---

## Key Findings

- 재생을 가능하게 하는 유전적 기구는 여러 종에 보존되어 있으나, 손상 후 이를 활성화하는 조절 네트워크의 차이가 재생 능력의 종간 편차를 만들 수 있다.
- 단일 종이 재생 모델의 모든 이상적 조건(높은 재생 능력 + 유전자 조작 용이성 + 짧은 세대 기간)을 갖추지 못하므로, 다양한 종에 걸친 비교 연구가 필수적이다.
- 세포 유형 특이적 절제와 정교한 계통 추적은 재생 시 세포의 기원과 운명을 규명하는 데 결정적이며, pericyte 절제 사례처럼 보조 세포 유형이 재생을 촉진하거나 억제하는지를 검증할 수 있다.
- 시각적 접근(다색 clonal analysis)과 서열 기반 접근(scGESTALT)의 통합이 단일세포 수준에서 재생 궤적을 재구성하는 미래 방향으로 제시된다.
- CRISPR/Cas9의 표적 돌연변이는 sox2, ctgfa, inhbaa가 발생에는 큰 영향 없이 재생에 특이적으로 요구됨을 밝혀, 재생 특이적(또는 우선적) 유전자 기능이 존재함을 시사한다.

---

## Perspective

이 Perspective는 재생생물학을 위한 분자유전학 도구를 체계적으로 정리하여, 척수·심장·CNS 등 포유류에서 제한적인 조직의 재생 기전을 해독하고 궁극적으로 재생의학에 응용하려는 분야의 동기를 잘 요약한다. 특히 척수 손상 맥락에서 pericyte 유래 반흔의 부정적 영향과 axolotl/제브라피시 척수 재생 유전자(Sox2, ctgfa)를 강조하여, 본 지식베이스의 척수·재생 주제와 직접적으로 연결된다.

한계로는, 리뷰 스스로 인정하듯 현재 진행 중인 연구의 일부만을 반영하며 포괄적인 재생생물학 리뷰가 아니라는 점, 그리고 somatic CRISPR/Cas9의 off-target 및 mosaicism 문제, Brainbow/clonal 분석의 기술적 제약 등 각 도구의 caveat가 남아 있다는 점이 있다. 향후 방향으로는 세포 유형 특이적 유도성 절제 계통의 확충, 다중 조직 다중화 표적화, 시각·서열 접근의 통합, 그리고 SNP·재생 능력 조절인자 탐색을 위한 dCas9 기반 후성유전체 편집의 활용이 제안된다.

---

## Key References

- Dias et al. (2018) — 척수 손상 후 type A pericyte의 KRas 불활성화(Glast-Rasless)로 축삭 재생 및 감각운동 기능 개선.
- Poss et al. (2002b) — 제브라피시 심장 재생의 최초 명확한 규명.
- Fei et al. (2014) — axolotl 척수 재생에서 Sox2 요구성.
- Mokalled et al. (2016) — 제브라피시 척수 재생에서 ctgfa(connective tissue growth factor a)의 역할.
- Dogra et al. (2017) — 제브라피시 심장 재생에서 inhbaa(inhibin beta a).
- Nowoshilow et al. (2018); Elewa et al. (2017) — axolotl 및 Iberian ribbed newt(Pleurodeles waltl) 게놈 보고.
- McKenna et al. (2016) — GESTALT (CRISPR-Cas9 barcode 기반 계통 기록).
- Raj et al. (2018) — scGESTALT (single-cell transcriptome + 계통 barcode 통합).
- Livet et al. (2007) — Brainbow 다색 신경세포 표지 시스템.
- Seifert et al. (2012) — African spiny mouse(Acomys)의 피부·귀 재생.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
