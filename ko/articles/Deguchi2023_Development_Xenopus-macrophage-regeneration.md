---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p02.txt
---

# Regeneration factors expressed on myeloid expression in macrophage-like cells is required for tail regeneration in Xenopus laevis tadpoles

## Citation (NLM)
Deguchi M, Fukazawa T, Kubo T. Regeneration factors expressed on myeloid expression in macrophage-like cells is required for tail regeneration in Xenopus laevis tadpoles. Development. 2023;150(15):dev200467. doi:10.1242/dev.200467

**DOI:** [https://doi.org/10.1242/dev.200467](https://doi.org/10.1242/dev.200467)

---

## Background
Xenopus laevis 올챙이는 꼬리 절단 후 약 1주 이내에 근육, 척삭(notochord), 척수(spinal cord)를 포함한 꼬리 전체를 재생할 수 있다. 절단 후에는 조직 특이적 줄기세포에서 유래한 계보 제한 전구세포가 분화하여 꼬리를 재건한다. 저자들은 이전 연구에서 interleukin 11(il11)이 절단 후 유도되며 여러 유형의 전구세포 생성에 필요하고 충분하다는 것, 그리고 Il11이 비세포자율적(non-cell-autonomous)으로 작용한다는 것(Il11 수용체가 없는 전구세포도 재생에 기여)을 보였다. 이로부터 Il11이 특정 지지 세포 유형을 통해 전구세포를 유도한다는 가설이 도출되었다.

이 지지 세포를 규명하기 위해 저자들은 Il11 신호 하류에서 작용하는 유전자를 스크리닝하여, 기존에 특성화되지 않은 두 개의 상동 유전자(Xenopus는 이질사배체)—L 및 S 염색체상의 Xetrov90002578m.L와 Xetrov90002579m.S—를 발견하고 이를 regeneration factors expressed on myeloid(rfem.L, rfem.S)로 명명했다. 이 단백질들은 인식 가능한 도메인이 없고(γ-crystallin과 약한 유사성, 신호펩타이드 없음 → 세포내 기능 시사), X. tropicalis에 추정 오솔로그가 있으나 어류·설치류에서는 오솔로그가 확인되지 않았다.

---

## Key Experiment Methods
1. 기존 공개 RNA-seq 데이터 재분석을 통한 후보 유전자 스크리닝: il11 KD 꼬리에서 하향 조절된 유전자를 증식 tailbud 세포와 대조하고 비증식 재생아(regeneration bud) 분획에서 농축된 유전자로 선별.
2. qRT-PCR로 0, 1, 3, 5, 7 dpa 꼬리 절단부의 시간적 발현 분석(rfem.L/rfem.S를 ef1a로 정규화); 두 paralog를 모두 검출하도록 공통 서열에 프라이머 설계.
3. 정상 및 3 dpa 꼬리의 시상 절편에 대한 in situ hybridization으로 rfem 발현 세포 국재화.
4. CRISPR/Cas9 knockdown(KD)을 통한 rfem.L 및 rfem.S 기능 상실(모자이크 "crispant" 올챙이; 각 2개 gRNA), tyrosinase(tyr) KD를 대조군으로 사용; 7 dpa에서 재생 평가(perfect/imperfect; Fiji로 면적·길이 측정); ICE 분석으로 편집 확인(KO score).
5. rfem KD 꼬리 절단부의 bulk RNA-seq로 하류 하향조절 유전자 규명.
6. 정상 꼬리 절단부/끝과 2 dpa 재생아에 대한 단일세포 RNA-seq(scRNA-seq, 10x Genomics)로 rfem 발현 세포 유형 규명(Seurat, UMAP, 50개 클러스터).
7. csf1(colony-stimulating factor 1) CRISPR/Cas9 KD로 대식세포 계보 세포를 고갈시키고 rfem 발현·세포 수 정량.
8. 어류 mpeg1 프로모터 하에서 rfem.L 강제 발현(mpeg1:rfem vs mpeg1:gfp 대조)을 통한 세포유형 특이적 구제(rescue) 실험, I-SceI 매개 형질전환 이용.

---

## Results
- rfem.L과 rfem.S 발현은 꼬리 절단으로 유도되어 1–3 dpa에 유의하게 증가(재생아 형성 시기와 일치)하고, 재생이 완료되는 5–7 dpa에 감소했다.
- In situ hybridization에서 rfem 발현 세포는 3 dpa에 재생아와 인접 부위에 산재했으나 정상 꼬리에서는 드물었으며, 1 dpa에 절단부에서 세포 수가 유의하게 증가하여 rfem 발현 세포의 상처 부위 이동을 시사했다.
- rfem.L 및 rfem.S의 CRISPR/Cas9 KD는 재생률을 낮추고 유의하게 더 작고 짧은 꼬리를 만들었으며 종종 비정상적 방향으로 굽었다; 비정상 형태는 성장 후에도 지속되고 재절단 후 악화되어 rfem.L 및/또는 rfem.S가 정상 꼬리 재생에 필요함을 나타냈다.
- rfem KD 절단부의 bulk RNA-seq에서 유의하게 하향조절된 6개 유전자(헤모글로빈 유전자 3개 포함)가 발견되어 상처 치유/혈관 형성에 대한 영향을 시사했다.
- scRNA-seq에서 rfem.L/rfem.S 발현 세포는 대식세포 유사 프로파일을 가진 백혈구 클러스터에 속했고 c1qc.L, csf1r.S, trem2.S, art5.L, crp.4.L가 농축되었다; c1qc.L과 art5.L 발현은 rfem과 잘 상관되었다.
- rfem 발현 세포에서 il11ra.L(Il11 수용체 소단위)는 검출되지 않아, 이 세포들이 Il11을 직접 수용하기보다 Il11 신호에 의해 간접적으로 조절될 가능성을 시사했다(단, scRNA-seq의 낮은 민감도로 역치 이하 발현을 배제할 수는 없음).
- csf1 KD(대식세포 계보 세포 고갈)는 rfem.L/rfem.S 발현과 세포 수를 유의하게 감소시키고 재생률을 낮춰, rfem 발현 세포가 Csf1 의존적 대식세포 계보와 연결됨을 보였다.
- mpeg1:rfem을 이용한 대식세포 유사 세포 특이적 구제는 rfem KD 올챙이에서 재생 꼬리 면적·길이를 유의하게 회복시켜, 대식세포 유사 세포에서의 rfem 발현이 성공적 꼬리 재생에 필수적임을 입증했다.

---

## Perspective
이 연구는 rfem.L과 rfem.S를 Xenopus 꼬리 재생에 필요한 신규 유전자로 규명하고, 대식세포 유사(수복성 골수계, reparative myeloid) 세포에서의 이들 발현이 재생 촉진 기능에 필수적임을 보였다. 백혈구는 재생을 촉진(수복성)하기도 하고 저해(염증성)하기도 하므로, rfem 발현 대식세포 유사 집단은 기존에 기술된 수복성 골수계 세포의 (하위)집단을 정의하며, 골수계 세포가 재생 능력을 부여하는 방식에 대한 분자적 단서를 제공한다. Xenopus 꼬리는 근육·척삭과 함께 척수를 재생하므로, 이 결과는 CNS/부속지 재생에 대한 면역세포의 기여를 이해하는 데 관련성이 있다. 저자들이 언급한 한계로는 Rfem 단백질의 세포내·미특성화 성질(서열로 기능 예측 불가), 모자이크 CRISPR crispant 사용, paralog 특이적 프라이머 설계의 어려움(두 paralog를 함께 정량), 말초혈액세포에서 KO score와 재생 간 상관을 검출하지 못한 점(rfem 발현 백혈구 비율이 작기 때문으로 추정), 그리고 어류·설치류에 오솔로그가 없어 직접적 번역이 제한될 수 있는 점이 있다. 저자들은 rfem.L/rfem.S가 백혈구에 재생 능력을 부여하는 세포·분자 기전의 단서가 될 것으로 제안한다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
