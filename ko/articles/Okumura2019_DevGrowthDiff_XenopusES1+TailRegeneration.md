---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p06.txt
---

# Cell type-specific transcriptome analysis unveils secreted signaling molecule genes expressed in apical epithelial cap during appendage regeneration

## Citation (NLM)
Okumura A, Hayashi T, Ebisawa M, Yoshimura M, Sasagawa Y, Nikaido I, Umesono Y, Mochii M. Cell type-specific transcriptome analysis unveils secreted signaling molecule genes expressed in apical epithelial cap during appendage regeneration. Dev Growth Differ. 2019;61(9):447-456. doi:10.1111/dgd.12635

**DOI:** [https://doi.org/10.1111/dgd.12635](https://doi.org/10.1111/dgd.12635)

---

## Background
양서류와 어류는 남아 있는 줄기/전구세포의 증식과 분화를 통해 사지, 꼬리, 지느러미 같은 절단된 부속기관을 재생할 수 있다. 성공적인 부속기관 재생의 첫 번째 결정적 단계는 상처 표피(wound epidermis, WE)의 형성이며, 양서류에서 WE는 원위부에서 두꺼워져 정단 상피모(apical epithelial cap, AEC)라는 특수한 다층 구조를 형성한다. WE/AEC는 분비성 신호전달 분자를 방출하여 하부 세포의 동원, 증식, 분화를 조절함으로써 재생을 유도하고 유지하는 것으로 여겨진다. 기존 연구에서 FGF(특히 FGF8), Wnt, BMP, TGFβ, Notch, ROS 신호전달이 다양한 재생 시스템의 WE/AEC에서 역할을 한다고 밝혀졌으나, WE/AEC 세포의 포괄적 유전자 발현 프로파일은 불명확했다.

저자들은 이전에 올챙이 꼬리 재생 중 AEC 세포에서 풍부하게 발현되는 Xenopus laevis *es1* 유전자를 동정하고, 꼬리 절단 후 WE와 AEC를 표지하는 *es1:egfp* 형질전환 리포터 계통을 제작했다. 본 연구에서는 이 계통을 이용해 WE/AEC 세포를 분리하여 이들이 발현하는 신호전달 분자 유전자 목록을 작성하고, 꼬리와 사지 원기(limb bud)의 AEC를 비교했다.

---

## Key Experiment Methods
1. WE/AEC 세포가 EGFP로 표지되는 *es1:egfp* 형질전환 Xenopus laevis 올챙이(NF stage 49-51) 사용; 뒷다리 원기 실험은 NF stage 52-53 사용.
2. 꼬리를 절단하고 꼬리 절단부 조직을 해리(collagenase/EDTA)한 뒤, 절단 후 1, 2, 3, 4일(dpa)에 형광활성세포분류(FACS)로 EGFP 양성 WE/AEC 세포를 분리. 무절단 대조군은 Alexa488-WGA로 표지한 야생형 올챙이에서 분류.
3. 조건당 100개 분류 세포의 3중 풀에 대해 Quartz-Seq 전사체 증폭과 Illumina HiSeq2500을 이용한 전전사체 RNA 시퀀싱 수행; X. laevis v9.1 유전체에 매핑하고 TPM으로 정량.
4. edgeR로 차등 발현 분석(padj < 0.05); 계층적 클러스터링과 PCA로 시료 유사성 평가.
5. 발현 유전자의 인간 상동유전자를 이용해 DAVID로 유전자 온톨로지(GO) 농축 분석.
6. GeneCards와 UniProt를 참조해 649개 후보 분비성 신호전달 분자 유전자를 수작업 선별(ECM 성분/재구성 효소 제외).
7. Whole-mount 및 절편 in situ 혼성화(DIG 표지 프로브)로 재생 중인 꼬리와 사지 원기에서 후보 유전자의 공간적 발현 검증.

---

## Results
- 검출된 45,099개 전사체 중 조건 간 8,017개 차등 발현 유전자(DEG)를 동정. 3중 반복은 밀접하게 군집화되었고, 가장 큰 차이는 무절단과 절단 시료 사이에 있었으며, 초기(1-2 dpa)와 후기(3-4 dpa) 사이에 뚜렷한 발현 전환이 나타남.
- 꼬리 재생 중 8,000개 이상의 유전자가 동적으로 변화했으며, ROS, FGF, canonical/non-canonical Wnt, TGFβ, Notch 경로 유전자가 포함됨.
- GO 농축: 1 dpa WE에서 상처 치유 관련 용어(과산화수소에 대한 세포 반응, ROS 대사 과정, FGF 수용체 신호전달, Ras 신호전달) 농축; 2 dpa에서 "상피-중간엽 전이" 농축; 3-4 dpa에서 세포 분열 용어 농축(후기 증식).
- 100개 이상의 후보 분비성 신호전달 분자 유전자가 WE/AEC 세포에서 발현되었으며, *bmp*, *wnt*, *tgfβ* 리간드 유전자가 포함됨. 즉 WE/AEC는 소수가 아닌 다수 분자의 칵테일을 방출.
- 꼬리 AEC에서 높게 발현되는 7개 신호전달 분자 유전자를 새롭게 동정: *mdk*, *fstl*, *slit1*, *tgfβ1*, *bmp7.1*, *angptl2*, *egfl6*.
- In situ 혼성화 결과 *mdk*, *fstl1*, *slit1*, *tgfβ1*, *bmp7.1*은 꼬리와 사지 원기 AEC 모두에서 발현("pan-AEC 인자")되었고, *angptl2*와 *egfl6*은 꼬리 AEC에 특이적이었음.
- 특히 *fgf8*은 사지 원기 AEC에서는 발현되지만 꼬리 WE/AEC에서는 발현되지 않았고(낮은 수준의 *fgf20*, *fgf13*만 검출), 따라서 *fgf8*은 사지 특이적 AEC 인자임. 이는 꼬리에서 재생 중인 척삭(notochord)이 주된 FGF/SHH 공급원이라는 점과 일치함.
- Aztekin 등(2019)의 재생 조직화 세포(ROC)와 부분적으로 일치: 둘 다 *fgf8*이 없으나, 다른 FGF 발현과 상재/손상유도 여부, 분리 발생 단계에서 차이가 있음.

---

## Perspective
본 연구는 Xenopus 꼬리 재생 중 WE/AEC 신호전달 분자에 대한 최초의 세포 유형 특이적, 시간 분해 전사체 목록 중 하나를 제공하며, 공유되는 "pan-AEC" 인자와 부속기관 특이적 인자를 구분한다. FGF8이 보편적 AEC 유래 재생 인자라는 가정을 반박하고, FGF 리간드의 공급원이 시스템에 따라 다름(꼬리에서는 척삭, 사지 원기에서는 AEC)을 보여준다. 꼬리 특이적 인자(ANGPTL2, EGFL6)의 동정은 척삭과 혈관 같은 꼬리 특이적 조직에서의 역할을 시사한다. 재생 중인 꼬리는 척수, 척삭, 근육을 포함하므로, 이러한 AEC 유래 신호는 부속기관 내에서 CNS/척수 조직이 어떻게 재생되는지를 이해하는 데 관련이 있다.

한계로는 *es1:egfp* 리포터 의존성(모든 WE/AEC 아집단을 포착하지 못할 수 있음), 저발현 전사체에 대한 절편 in situ 검출 한계, 새로 동정된 유전자의 기능적 역할이 미검증인 점이 있다. 향후 연구에서는 후보 인자(예: 꼬리 재생에서 ANGPTL2/EGFL6)의 기능적 검증과 발생 단계에 걸친 es1 표지 세포와 ROC의 관계 규명이 필요하다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
