---
tags: [2026-07, SpinalCord]
extract: 2026-07-16
extract_file: extract/2026-07-16_p01.txt
---

# SOX2는 신경전구세포의 후성유전적 지형을 준비시켜 해마 신경발생 중 적절한 유전자 활성화를 가능하게 한다

## Citation (NLM)

Amador-Arjona A, Cimadamore F, Huang CT, Wright R, Lewis S, Gage FH, Terskikh AV. SOX2 primes the epigenetic landscape in neural precursors enabling proper gene activation during hippocampal neurogenesis. Proc Natl Acad Sci U S A. 2015;112(15):E1936-E1945. doi:10.1073/pnas.1421480112

**DOI:** [https://doi.org/10.1073/pnas.1421480112](https://doi.org/10.1073/pnas.1421480112)

---

## Background

성체 해마 과립하 영역(SGZ)의 신경전구세포(NPC)에서 생성되는 새로운 과립 신경세포는 공간 학습과 패턴 분리에 기여하지만, 이들의 신경발생 프로그램 활성화를 조절하는 분자 기전은 잘 알려져 있지 않다. SOX2는 SOXB1 전사인자이자 신경줄기/전구세포의 표지자로 NPC 자가재생에 필요하며, 인간에서의 돌연변이는 무안구증(anophthalmia), 해마 발달 결함, 경련, 지적 장애를 유발한다. 그러나 신경세포 분화에서 SOX2의 역할은 역설적이었다: SOX2 과발현은 분화를 억제하여 대체로 신경세포 유전자의 억제자로 여겨졌으나, 기능상실 연구는 SOX2가 신경발생에 필요함을 보여준다.

NPC에서 proneural/신경발생 유전자는 이가성(bivalent) 염색질 표지(억제성 H3K27me3와 활성성 H3K4me3 모두)를 지녀 침묵 상태이지만 분화 신호가 도달하면 활성화될 준비가 되어 있다(poised). 본 연구는 새로운 가설을 검증하였다: SOX2가 이가성 표지된 대기 상태 프로모터에 결합하여—polycomb 억제 복합체 2(PRC2) 활성을 제한함으로써—허용적 후성유전 상태를 유지하고, 이로써 해마 신경발생 개시 시 적절한 유전자 활성화를 가능하게 한다는 것이다.

---

## Key Experiment Methods

1. 마우스 ES세포 유래 NPC의 공개 ChIP-seq 데이터(SOX2 결합, H3K27me3, H3K4me3) 전장유전체 분석으로 이가성 표지된 SOX2 결합 부위 확인; Gene Ontology 분류.
2. 성체 해마 NPC(hipNPC)에서 doxycycline 유도성 shRNA(shSox2) 대 대조군(shCTRL)을 이용한 SOX2 기능상실.
3. proneural/신경발생 유전자좌(Ngn2, NeuroD1, Sox21, Bdnf, Gadd45b)에서 SOX2·H3K27me3·H3K4me3·H3K9ac·EZH2·GCN5 ChIP-qPCR; 전체 H3K27me3/EZH2 웨스턴 블롯.
4. Wnt3a로 신경발생 유도 후 표적 유전자 qRT-PCR; HDAC 억제제 valproic acid(VPA)로 회복 시도.
5. 유전자 마우스 모델: Sox2flox::mGFAP-Cre::nestin-CFPnuc(SOX2cKO), 성체 NPC에서 출생 후 결손; NGN2·NEUROD1·PROX1·DCX·GFAP·CFPnuc 면역조직화학.
6. 생체 내 신경발생 정량: PCNA, BrdU(2시간 및 4주 프로토콜), CldU/IdU 세포주기 재진입, NeuN 공동표지; 활성 caspase-3 및 TUNEL로 세포자멸사 측정.
7. 렌티바이러스/레트로바이러스 NeuroD1 전달로 생체 내외 표현형 회복(mCherry 내부 대조를 이용한 양측 DG 레트로바이러스 주입).
8. 새로운 신경세포의 형태·전기생리 분석(수상돌기 길이/분지, 스파인 밀도/형태, sEPSC 전세포 기록).

---

## Results

- NPC의 16,683개 SOX2 결합 부위 중 2,514개(15.1%)가 H3K27me3 농축, 그 중 680개(27%)가 이가성(H3K4me3 동반)이었고, 이는 전체 이가성 프로모터의 25%를 차지했다. SOX2 결합 이가성 유전자는 초기 신경발생 조절자를 암호화하는 반면, SOX2가 없는 나머지 75%의 이가성 프로모터는 후기 신경세포 성숙에 관여한다. H3K27me3 밀도는 SOX2 결합 부위 주변에 "골짜기"를 보였다.
- SOX2는 대기 상태의 proneural(Ngn2, NeuroD1) 및 신경발생(Sox21, Bdnf, Gadd45b) 유전자 조절 영역에 결합했다. Sox2 녹다운은 이 SOX2 부위에서 H3K27me3와 EZH2 결합을 선택적으로 증가시켰고(전체 H3K27me3/EZH2 변화 없이), H3K4me3는 영향을 받지 않아 염색질을 억제 상태로 이동시켰다.
- Wnt3a 유도에 의한 Ngn2, NeuroD1(및 Sox21, Bdnf, Gadd45b) 활성화가 SOX2 결핍 hipNPC에서 현저히 손상되었다. HDAC 억제제 VPA는 발현을 회복시키지 못했으며, 이는 아세틸화에 둔감한 심대한 염색질 변화를 시사한다; GCN5 의존적 H3K9ac 침착도 감소했다.
- 생체 내에서 SOX2cKO 마우스는 NGN2(증폭 전구세포)와 NEUROD1(초기 신경모세포) 발현 감소를 보였고, 정상적인 초기 신경모세포 NEUROD1 정점이 소실되었다. SOX2가 결합하지만 이가성 표지가 없는 PROX1은 영향을 받지 않아 대기 상태 유전자에 대한 특이성을 확인했다.
- SOX2cKO는 NPC, 증폭 전구세포, 신경모세포(DCX+), 성숙한 새 신경세포(BrdU+NeuN+ 약 45.5% 감소)의 연령 진행성 감소를 일으켰고, 방사형 NPC 자가재생은 경미하게만 영향받았다. 주된 결함은 신경모세포의 세포자멸사 증가(AC3+/TUNEL+ DCX+ 세포 증가)였다.
- 레트로바이러스 NeuroD1 전달은 SOX2cKO 마우스의 생체 내외에서 신경모세포 생존/신경발생을 회복시켰으며, 하류 proneural 유전자 복원만으로 충분함을 입증했다.
- 생존한 SOX2 결핍 새 신경세포는 비정상 성숙을 보였다: 수상돌기 길이와 분지 감소, 전체 스파인 밀도 감소이나 버섯형 스파인 밀도 증가, sEPSC 진폭 증가—SOX2 발현이 멈춘 한참 후에도 신경세포 성숙에서 "지연된" 역할을 드러냈다.

---

## Perspective

본 연구는 이전에 인식되지 않았던 SOX2의 후성유전적 기능을 밝혀낸다: SOX2는 계열 특이적 전사인자로서 국소적으로 PRC2(EZH2/H3K27me3) 활성을 제한하여 초기 신경발생 유전자의 이가성/대기 염색질 상태를 유지하고, 이로써 신경발생 신호에 대한 강건한 유전자 활성화를 허가한다. 이는 SOX2가 조기 분화의 억제자이면서 동시에 신경발생에 필요하다는 역설을 해소한다—SOX2는 이 유전자들을 직접 활성화하지 않고 대기 상태로 유지한다. 저자들이 아는 한, 이는 계열 특이적 인자가 대기 프로모터의 이가성을 유지하여 발달 프로그램 개시를 조율하는 첫 사례이다.

이 발견은 해마 이상과 학습/기억 결함이 흔한 인간 SOX2 무안구증 증후군, 그리고 신경 재생·재프로그래밍의 광범위한 노력(SOX2는 섬유아세포를 NSC로, Mash1과 함께 혈관주위세포를 신경세포로 재프로그래밍할 수 있음)과 직접 관련된다. 단일 하류 proneural 유전자(NeuroD1)만으로 생존을 회복할 수 있다는 점은 가능한 중재를 시사한다. 저자들이 밝힌 한계로는 전장유전체 이가성/SOX2 지도가 hipNPC가 아닌 ES세포 유래 NPC에서 도출되었다는 점, 그리고 SOX2-PRC2 간섭의 정확한 기전(입체 경쟁, 보조인자 모집, DNA 메틸화, 염색질 재구성)이 아직 규명되지 않았다는 점이 있다. 향후 연구는 hipNPC 특이적 후성유전체 지도를 생성하고 이 대기 상태 유지의 하류 실행자를 규명해야 한다.

---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
