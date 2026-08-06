# Wizardry 8 한국어 패치

Wizardry 8과 Fan Patch 1.28을 위한 비공식 한국어 패치입니다.

## 최신 릴리스

- Wizardry 8
- 원본 1.24: `Wizardry8_KoreanPatch_1.24_TopicFix_v0.2.6.zip`
- Fan Patch 1.28 build 6735: `Wizardry8_KoreanPatch_1.28_TopicFix_v0.2.6.zip`
- 한국어 패치 v0.2.6 (대화 토픽 입력 보조판)

두 ZIP은 서로 다른 게임 버전용입니다. 파일을 섞어 설치하지 마세요.

## 설치

1. 정품 Wizardry 8을 설치합니다.
2. 사용 중인 게임 버전에 맞는 [v0.2.6 릴리스](../../releases)의 ZIP 하나를 받습니다.
3. 압축 안의 내용을 Wizardry 8 게임 폴더에 덮어씁니다.
4. Fan Patch 1.28 사용자는 런처 언어를 **ENG**로 두고 `Wiz8_v128.exe`를 실행합니다.

대화의 영문 토픽은 더블클릭해 입력할 수 있습니다. 현재 저장에 이미 기록된
`[소문]` 같은 한국어 토픽을 자동으로 기존 영문 토픽으로 변환하지는 않습니다.

`KOR` 외부 로캘은 사용하지 않습니다. 수정된 `Wiz8_v128.exe`가 NPC 스크립트의
한국어 문자열 변환 로캘과 버퍼를 직접 처리합니다. Fan Patch 추가 옵션 문자열은
`Wiz8.dll` 내부에 직접 적용했습니다.

권장 `wiz8.ini` 설정:

```ini
Language=2
Fan_Patch_1_28_Localization=
DontShowDialogLauncher=0
```

## 포함 범위

- 본편 UI와 지역 메시지
- 플레이어 음성 자막
- NPC 대화 스크립트
- 퀘스트 저널 기록 333문장
- 아이템 이름 819개
- 아이템 및 주문 설명
- Fan Patch 1.28 build 6735 추가 옵션
- 갈무리9 기반 한글 비트맵 글꼴과 한국어 문자 매핑
- 8×7 초소형 글꼴은 프리텐다드 사용

## 글꼴 고지

- Noto Sans KR: Copyright 2014-2021 Adobe, SIL Open Font License 1.1
- Pretendard: SIL Open Font License 1.1
- 릴리스에는 게임용으로 래스터화한 비트맵 글리프만 포함됩니다.

## 주의

- 설치 전 게임 폴더를 백업하세요.
- 한국어 패치가 설치된 폴더에서 Fan Patch 자동 업데이트를 실행하지 마세요.
- 게임 본편과 Fan Patch는 이 저장소 및 릴리스에 포함되지 않습니다.
- 이 프로젝트는 Sir-Tech, GOG 또는 Fan Patch 제작진과 관계없는 비공식 작업입니다.
