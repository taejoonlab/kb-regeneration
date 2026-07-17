---
tags: [2026-07, SpinalCord, RawDataAvailable]
extract: 2026-07-16
extract_file: extract/2026-07-16_p03.txt
raw_data:
  - "SRA: PRJNA512373, PRJNA515075"
log:
  - "2026-07-16 · create · Claude Fable 5 (Claude Code)"
  - "2026-07-17 · edit · Claude Fable 5 (Claude Code) · add RawDataAvailable tag, raw_data, Data Availability section"
---

# Acoel genome reveals the regulatory landscape of whole-body regeneration

## Citation (NLM)
Gehrke AR, Neverett E, Luo YJ, Brandt A, Ricci L, Hulett RE, Gompers A, Ruby JG, Rokhsar DS, Reddien PW, Srivastava M. Acoel genome reveals the regulatory landscape of whole-body regeneration. Science. 2019;363(6432):eaau6173. doi:10.1126/science.aau6173

**DOI:** [https://doi.org/10.1126/science.aau6173](https://doi.org/10.1126/science.aau6173)

---

## Background
많은 동물이 상처를 치유하지만, 일부는 작은 조각으로부터 몸 전체를 재구성(whole-body regeneration)할 수 있다. 이 과정은 상처 신호전달, 줄기세포 동역학, 위치 정체성의 상호작용을 요구하며 지금까지 주로 단백질 코딩 수준에서 연구되었다. 비코딩 유전체(noncoding genome)가 상처에 반응하여 유전자 발현을 제어하고 재생을 개시하는 방식은 거의 알려지지 않았다. 저자들은 재생능이 뛰어난 무장류(acoel) 벌레 *Hofstenia miamia*(three-banded panther worm)의 유전체를 시퀀싱했다. 이 종은 다른 모든 좌우대칭동물(Nephrozoa)의 자매 계통(Xenacoelomorpha)이라는 핵심 계통학적 위치를 차지하며, 크로마틴 프로파일링으로 재생 중 활성화되는 조절 영역을 규명했다.

---

## Key Experiment Methods
1. *Hofstenia miamia* 전장 유전체 시퀀싱/조립(~89.6× Illumina, Chicago 법; Oxford Nanopore 장기 리드와 REAPR로 검증); Augustus로 유전자 예측.
2. 절단 후 0, 3, 6, 12, 24, 48시간(hpa) 시점 머리/꼬리 조각 상처 부위에 ATAC-seq 수행하여 재생 반응성 크로마틴 확인.
3. chromVAR로 386개 전사인자 결합 모티프의 크로마틴 "가변성" 순위 분석 및 동적 TF 모티프 식별.
4. egr(및 runt, deaf1) RNAi 억제와 0, 1, 3, 6, 12 hpa RNA-seq으로 상처 유도 유전자 및 Egr 표적 규명.
5. In situ hybridization으로 상처 유도 발현 및 RNAi 표현형 검증.
6. egr-RNAi 개체 ATAC-seq으로 Egr "재생 cistrome" 규명; PIQ footprinting(chromatin opening index)으로 pioneer factor 활성 및 RUNT 결합 평가; 편형동물 *Schmidtea mediterranea* 비교 ATAC-seq.

---

## Results
- *Hofstenia* 유전체 조립체는 총 ~950 Mb(53% 반복서열), 22,632개 유전자 모델, 예상 메타조아 BUSCO 유전자의 90% 포함; 표준적인 동물 유전자 구성을 가짐.
- 재생은 약 18,000개의 동적 크로마틴 변화를 유도했으며 대부분 인트론과 유전자 간 영역에 위치하고, 대부분의 peak가 6 hpa 이내에 열리고 24–48 hpa에 닫힘.
- EGR(early growth response) 결합 모티프가 재생 중 가장 가변적으로 접근성이 변하는 단일 모티프였음. *Hofstenia*는 단일 egr 오솔로그를 가지며 1 hpa에 표피·근육·신경·neoblast 등 여러 세포유형에서 상처 유도됨.
- egr-RNAi 개체는 blastema 재생에 완전히 실패(새 머리/꼬리 형성 불가, 100%, n=150)하여 egr가 마스터 조절자임을 규명.
- RNA-seq으로 61개 상처 유도 유전자 확인; 검증된 13개 중 12개가 egr-RNAi에서 6 hpa에 상향조절 실패. EGR 사이트를 가진 재생 반응성 peak가 egr-RNAi에서 열리지 않아 직접 조절을 시사.
- Egr는 pioneer factor 유사 거동을 보임: 높은 chromatin opening index(439개 모티프 중 상위 5위), 크로마틴을 닫힘→열림으로 전환; egr 유전자좌에 자가조절 루프 존재.
- GRN 확장: Egr가 전사인자 runt와 deaf1을 직접 활성화; runt-RNAi는 재생을 차단하고 Runt가 neuregulin-1(nrg-1)을 직접 조절하여 egr→runt→nrg-1 캐스케이드 확립.
- 편형동물에서도 EGR 모티프가 가장 가변적인 모티프 중 하나이며, Egr 제어 GRN의 상동유전자들이 편형동물·불가사리·척추동물에서 보존/요구됨.

---

## Perspective
본 연구는 몸 전체 재생을 개시하는 최초의 크로마틴 수준 유전자 조절 네트워크를 확립하고, Egr를 마스터 조절 유전자로 작동하는 pioneer factor 후보로 규명한다. 재생을 에피게놈 관점에서 봄으로써, 전장 크로마틴 접근성 + 기능적 RNAi 접근법은 원연관 동물 간 재생 경로 비교의 틀을 제공하며 다른 모델 및 신흥 시스템으로 확장 가능하다. 편형동물·불가사리·척추동물에서의 EGR 제어 네트워크 보존성은 이 재생 네트워크가 조상 수준에서 보존된 것인지 수렴 진화한 것인지의 미해결 질문을 제기한다. 지식베이스 관련성: Egr/neuregulin 상동유전자는 척추동물 신경 재생 및 axolotl 사지 재생에 관여하여, 이 무척추동물 조절 논리를 CNS/부속지 재생과 연결한다.

## 데이터 이용 가능성

**본 연구가 생성·기탁한 원시 데이터:**
- SRA: PRJNA512373, PRJNA515075


---

*Processed by **Claude Fable 5** (Claude Code) on 2026-07-16*
