# Choice of Robots 한글패치

Steam 게임 [Choice of Robots](https://store.steampowered.com/app/339350/Choice_of_Robots/)의 한글 번역 패치입니다.

## 다운로드

[![GitHub Release](https://img.shields.io/github/v/release/Rein-DevOps/choice-of-robots-korean)](https://github.com/Rein-DevOps/choice-of-robots-korean/releases/latest)

[Releases](https://github.com/Rein-DevOps/choice-of-robots-korean/releases)에서 최신 버전을 다운로드하세요.

## 설치 방법

1. ZIP 파일을 다운로드하여 압축 해제
2. `install.bat` 실행 (자동으로 게임 경로를 찾아 패치 적용)

### 수동 설치
1. Steam 게임 폴더의 `resources` 폴더로 이동
   - 기본: `C:\Program Files (x86)\Steam\steamapps\common\ChoiceOfRobots\resources\`
2. 기존 `app.asar` 파일 백업
3. 패치의 `app.asar`를 해당 폴더에 복사
4. 게임 실행

## 번역 범위

- ✅ 전체 스토리 텍스트 (7개 챕터)
- ✅ 모든 선택지
- ✅ 스탯 화면 및 챕터 요약
- ✅ 업적 72개
- ✅ 고유 명사 음역 (v1.1.0+)

### 고유 명사 번역 (v1.1.0)

| 영문 | 한글 |
|------|------|
| Professor Ziegler | 지글러 교수 |
| President Irons | 아이언스 대통령 |
| San Francisco | 샌프란시스코 |
| Silicon Valley | 실리콘 밸리 |
| Nimbus | 님버스 |
| Pentagon | 펜타곤 |
| White House | 백악관 |

## 알려진 제한사항

- 영어 대명사(He/She/the one 등)가 한국어에서 어색할 수 있음
  - 한국어는 주어 생략이 자연스러워서 발생하는 번역의 한계
- 일부 동적 텍스트는 변수 참조로 인해 영문 유지

## 원본 복구

- `uninstall.bat` 실행 또는
- Steam에서 게임 파일 무결성 검사

## 버전 히스토리

| 버전 | 날짜 | 변경사항 |
|------|------|----------|
| v1.1.0 | 2024-12-04 | 고유 명사 음역 추가, Stats 6-7장 요약 완역 |
| v1.0.2 | 2024-12-03 | 변수 손상 수정, Steam 연동 복구 |
| v1.0.1 | 2024-12-03 | 번역 품질 개선 |
| v1.0.0 | 2024-12-03 | 최초 릴리즈 |

## 라이선스

이 패치는 개인 사용 목적으로만 배포됩니다. 원본 게임의 저작권은 Choice of Games LLC에 있습니다.
