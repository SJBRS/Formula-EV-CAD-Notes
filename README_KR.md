# Formula-EV-CAD-Notes (한국어 요약)
> 🌐 **Language:** [🇺🇸 English (메인 페이지)](README.md) | **🇰🇷 한국어 (Korean)**

## 📌 프로젝트 개요
본 저장소는 **Formula EV(자작전기자동차)** 및 **하이브리드 에너지 저장 시스템(HESS: 배터리 + 슈퍼커패시터)**의 기구 패키징과 하드웨어 통합을 위해 **3DEXPERIENCE CATIA** 3D CAD 모델링을 체계적으로 학습하고 기록하는 공간입니다.

단순히 전자 회로(ECAD)만 설계하는 것을 넘어, **Altium Designer(ECAD)와 3DEXPERIENCE CATIA(MCAD)를 연계**하여 FSAE/KSAE 안전 규정을 충족하는 배터리·제어기 방수 하우징, 냉각 브래킷, 파워트레인 마운트를 직접 설계하는 것을 목표로 합니다.

---

## 🗺️ 4단계 학습 및 실전 설계 로드맵

- [x] **0단계 (Phase 0):** GitHub 저장소 세팅 및 엔지니어링 파일 명명 규칙 수립
- [ ] **1단계 (Phase 1): 단품 설계 기초 (`01_CATIA_Basics/`)**
  - 완전 구속(초록색 상태) 2D 스케치, `Pad`(돌출), `Pocket`(파내기), `Hole`, `Shaft`, `Edge Fillet` 기능 숙달
- [ ] **2단계 (Phase 2): 어셈블리 및 간섭 해석 (`02_Assembly_Kinematics/`)**
  - 다중 부품 조립 구속(`Coincidence`, `Contact`, `Offset`) 및 정적·동적 **간섭 검사(Clash Analysis)**
- [ ] **3단계 (Phase 3): 판금 및 곡면 설계 (`03_Surface_Aero_Practice/`)**
  - 공력 파츠를 위한 곡면 설계(GSD) 기초 및 보호 커버 제작용 판금(Sheet Metal) 굽힘 설계
- [ ] **4단계 (Phase 4): Formula EV & HESS 실전 패키징 (`04_Formula_EV_Packaging/`)**
  - FSAE EV 안전 규정을 준수하는 VCU PCB 및 HESS 모듈 전용 알루미늄 하우징 설계

---

## 📂 실습 기록 및 모델 갤러리

| 번호 | 폴더 / 모델명 | 사용 앱 (워크벤치) | 주요 학습 기능 | 진행 상태 |
| :--- | :--- | :--- | :--- | :--- |
| **01** | `01_Bracket_Extrude` | Part Design | 완전 구속 스케치, `Pad`, `Pocket`, `Fillet` | 🔄 진행 중 |
| **02** | `02_Shaft_Revolve` | Part Design | 회전체 단면 스케치, `Shaft`, `Groove`, `Chamfer` | ⏳ 예정 |
| **03** | `03_Simple_Assembly` | Assembly Design | `Coincidence` & `Contact` 구속, 간섭 체크 | ⏳ 예정 |

---

## 🛠️ 엔지니어링 파일 관리 규칙
* **파일 명명 규칙 (Naming Convention):** 프로그램 간 데이터 손상과 경로 오류를 방지하기 위해 영문, 숫자, 언더바(`_`)만 사용하며 중립 표준 포맷(`.stp`)으로 내보내기 합니다. (예: `01_Bracket_v1.stp`)
* **결과물 증빙 규칙 (Documentation):** 완료된 모든 모델은 설계 트리(**Specification Tree**)가 보이도록 캡처한 3D 등각 투영 이미지(`.png`)와 **3DEXPERIENCE**에서 추출한 `.stp` 파일을 함께 업로드합니다.
