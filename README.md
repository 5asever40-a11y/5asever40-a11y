# `security.log`

> **오한결 / Ozzy**
>
> 악성코드 분석 · 리버싱 · 탐지 엔지니어링을 공부하는 보안 엔지니어링 학습자입니다.
>
> GitHub: [5asever40-a11y](https://github.com/5asever40-a11y)

---

## 탐지와 분석 사이에서 기록을 남깁니다

저는 악성코드 분석, API 호출 기반 탐지, 리버스 엔지니어링, 그리고 로그 기반 탐지 엔지니어링에 관심이 있습니다.

단순히 문제를 푸는 것보다, 분석 과정에서 확인한 증거와 판단 근거를 남기는 것을 중요하게 생각합니다. 최근에는 PinTool 기반 API 호출 오프셋 분석, MITRE ATT&CK 기반 공격 시나리오 모델링, Splunk/ELK 기반 로그 분석, Windows/AD 보안 실습을 중심으로 공부하고 있습니다.

---

## 관심 분야

- 악성코드 행위 분석 및 탐지 로직 설계
- EXE/ELF 및 패킹 바이너리 리버싱
- PinTool 기반 API 호출 오프셋 분석
- Anti-Debugging / Anti-VM 기법 분석
- MITRE ATT&CK 기반 공격 흐름 및 탐지 시나리오 모델링
- Splunk / ELK 기반 로그 분석과 상관관계 탐지

---

## 기술 스택

- **언어**: C, C++, Python
- **리버싱**: IDA, x64dbg, pwndbg, PE/ELF 분석
- **악성코드 분석**: Anti-Debugging, Anti-VM, API Tracing, 행위 분석
- **계측 / 후킹**: PinTool, Frida
- **웹 / 보안 실습**: Burp Suite, WSL, VMware, VirtualBox
- **탐지 엔지니어링**: Splunk, ELK, MITRE ATT&CK, Correlation Rule

---

## 프로젝트

### AI + PinTool 기반 악성코드 탐지

- API 호출 오프셋 패턴을 활용한 악성코드 탐지 시스템 연구
- 정적/동적 특징 추출 및 탐지 모델 실험

### 백신 우회 악성코드 탐지 기법 연구

- WHS 3기 팀 프로젝트
- 메모리 기반 우회 행위 분석 및 탐지 아이디어 설계

### MITRE ATT&CK / ELK 기반 탐지 시나리오

- 공격 체인 모델링
- 로그 수집, 상관관계 분석, 탐지 규칙 설계

### KoBERT + YOLO 기반 개인정보 유출 방지

- 텍스트와 이미지 기반 민감정보 탐지
- 실시간 개인정보 유출 위험 탐지 아이디어 연구

---

## 취약점 제보 / CVE

| 식별자 | 대상 | 내용 | 상태 |
|---|---|---|---|
| **CVE-2026-50811** | FreeType | FreeType 관련 취약점 공동 제보 | Vendor acknowledged / CVE assigned |
| - | OpenHTJ2K | JPIPE server heap info leak 및 malicious JPP client-response heap write 제보 | 패치 릴리즈 완료 |
| - | OpenHTJ2K | PPM packet-header `pass_length[128]` heap overflow trigger 제보 | 패치 릴리즈 완료 |
| FVE-2025-c0d1-72680 | Vendor web service | `venue_code` 조작을 통한 타 매장 주문 생성 취약점 제보 | 제보 완료 |
| KVE-2025-0536 | V3 Lite | 자가 보호 우회 및 백신 설정 변경 취약점 제보 | 제보 완료 |

### CVE-2026-50811 References

- [FreeType GitLab Issue #1436](https://gitlab.freedesktop.org/freetype/freetype/-/issues/1436)
- [FreeType GitLab Patch Commit](https://gitlab.freedesktop.org/freetype/freetype/-/commit/5a280ecde6f324de0d226261036e736e0cb49a71)
- [FreeType GitHub Mirror Commit](https://github.com/freetype/freetype/commit/5a280ecde6f324de0d226261036e736e0cb49a71)
- [Analysis / PoC Gist](https://gist.github.com/junius-sec/6dd0fb25b643f89914083a38e5e57ace)

<p align="center">
  <img src="./assets/cve-2026-50811-ack.png" width="360" alt="CVE-2026-50811 acknowledgement screenshot" />
</p>

---

## 연구 / 논문

- **AI와 PinTool 기반 API 호출 오프셋 분석을 통한 악성코드 탐지 시스템**
  - API 호출 오프셋 패턴을 활용한 악성코드 탐지 연구

- **KoBERT와 YOLO를 활용한 실시간 개인정보 유출 방지 시스템**
  - 텍스트/이미지 기반 민감정보 탐지 연구

---

## 수상 / 활동

- KITRI 차세대 보안리더 양성 프로그램 화이트햇 스쿨 3기 **Top 20**
- WHS CTF **우수상 2nd**
- 상명대학교 캡스톤 경진대회 수상
- 대한전기학회 학생 논문 수상
- KISIA AI보안 기술개발 교육 과정
- KISIA 시큐리티 아카데미 진단분석트랙

---

## 요즘 공부하는 것

- Windows Internals와 악성코드 행위 분석
- 실제 로그 기반 탐지 엔지니어링
- Active Directory 공격 경로와 권한 상승
- 보안 실습 writeup 자동화와 재사용 가능한 분석 노트

---

## 앞으로 채워갈 저장소

1. `malware_detection_with_pintool_and_ai`
2. `security-notes`
3. `ctf-writeups`
4. `detection-engineering-labs`
5. `reverse-engineering-notes`
