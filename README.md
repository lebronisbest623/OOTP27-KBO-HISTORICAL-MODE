# KBO Historical Mode for OOTP

**한국어** | [English](./README.en.md)

KBO 역사 모드용 배포 폴더입니다. OOTP에서 사용할 수 있도록 데이터베이스, 유니폼, 로고, 페이스젠, 구장, 스탯 자료를 한곳에 정리한 릴리즈 패키지입니다.

## 포함 내용

- `database`
- `logos`
- `uniforms`
- `facegen`
- `ballparks`
- `stats`
- `tools`

## 설치 방법

### 기본 설치

1. 이 폴더를 원하는 위치에 압축 해제하거나 복사합니다.
2. OOTP에서 새 게임 또는 관련 리그를 생성할 때 이 폴더 안 자산을 사용합니다.
3. 필요할 경우 `database`, `logos`, `uniforms`, `facegen`, `ballparks`, `stats` 폴더 내용을 리그 또는 모드 작업 폴더에 복사합니다.
4. 기존 파일이 있으면 덮어쓰기 전에 백업하는 것을 권장합니다.

### 권장 사항

- 가능하면 새 세이브에서 시작하는 것을 권장합니다.
- 적용 후 팀 로고, 유니폼, 구장, 페이스젠 연결 상태를 확인하세요.
- 기존 MLB/KBO 관련 파일을 덮어쓸 수 있으므로 원본 백업을 권장합니다.

## 폴더 구조

```text
kbo-historical/
├── ballparks/
├── database/
├── facegen/
├── logos/
├── stats/
├── tools/
└── uniforms/
```

## 기여

오류 수정, 누락 자산 추가, 데이터 개선 제안은 언제든 환영합니다.

- 기여 안내: [CONTRIBUTING.md](./CONTRIBUTING.md)
- 자주 묻는 질문: [FAQ.md](./FAQ.md)

## Special Thanks

- [LazyQuokka1218](https://github.com/LazyQuokka1218)
