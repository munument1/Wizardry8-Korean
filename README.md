# Wizardry 8 한국어 패치

Wizardry 8과 Fan Patch 1.28을 위한 비공식 한국어 패치입니다.

## 최신 안정 대상

- Wizardry 8
- Fan Patch 1.28 build 6709
- 한국어 패치 v0.1.0

build 6735 호환판은 별도 시험 중이며, 현재 6709용 파일을 6735에 덮어쓰면 안 됩니다.

## 설치

1. 정품 Wizardry 8을 설치합니다.
2. Fan Patch 1.28 build 6709를 설치합니다.
3. [Releases](../../releases)에서 `Wizardry8_Korean_Patch_1.28.6709_v0.1.0.zip`을 받습니다.
4. 압축 안의 `Patch Files` 폴더 내용물을 Wizardry 8 게임 폴더에 덮어씁니다.
5. Fan Patch 런처의 언어는 **ENG**로 두고 `Wiz8_v128.exe`를 실행합니다.

`KOR` 외부 로캘은 사용하지 않습니다. build 6709의 외부 로캘 로더가 한글
바이트를 손상시키기 때문에, Fan Patch 추가 옵션 문자열은 `Wiz8.dll` 내부에
직접 적용했습니다.

권장 `wiz8.ini` 설정:

```ini
Language=2
Fan_Patch_1_28_Localization=
```

## 포함 범위

- 본편 UI와 지역 메시지
- 플레이어 음성 자막
- NPC 대화 스크립트
- 아이템 및 주문 설명
- Fan Patch 1.28 build 6709 추가 옵션
- 굴림 기반 한글 비트맵 글꼴과 한국어 문자 매핑

## 주의

- 설치 전 게임 폴더를 백업하세요.
- 6709 한국어 작업본에서 Fan Patch 자동 업데이트를 실행하지 마세요.
- 게임 본편과 Fan Patch는 이 저장소 및 릴리스에 포함되지 않습니다.
- 이 프로젝트는 Sir-Tech, GOG 또는 Fan Patch 제작진과 관계없는 비공식 작업입니다.

