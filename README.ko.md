<div align="center">

# Velora

**Designed for effortless listening.**

[![Latest Release](https://img.shields.io/github/v/release/veloraplayer/Velora?style=flat-square&color=3B82F6)](https://github.com/veloraplayer/Velora/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/veloraplayer/Velora/total?style=flat-square&color=10B981)](https://github.com/veloraplayer/Velora/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%2064--bit-0078D6?style=flat-square)](https://github.com/veloraplayer/Velora/releases/latest)
[![Ko-fi](https://img.shields.io/badge/Support-Ko--fi-FF5E5B?style=flat-square)](https://ko-fi.com/velora_player)

[English](README.md) | **한국어**

[⬇️ 최신 버전 다운로드](https://github.com/veloraplayer/Velora/releases/latest) · [🐛 버그 제보](https://github.com/veloraplayer/Velora/issues) · [📧 피드백 메일](mailto:veloraplayer@gmail.com)

</div>

---

<!-- 여기에 메인 화면 / 감상 모드 대표 스크린샷 또는 GIF를 드래그 앤 드롭하세요 -->

**Velora(벨로라)**는 깔끔한 디자인, 부드러운 애니메이션, 몰입감 있는 감상 경험에 초점을 맞춘 Windows용 로컬 음악 플레이어입니다.

## ✨ 주요 기능

- **몰입형 감상 모드 (Listening Mode)** — 하단 플레이어 바를 더블클릭하거나 위로 드래그하면 앨범 아트 기반의 블러 배경(5단계 강도 조절), 커버 모핑 전환, 슬라이드 재생 대기열, 유휴 시 컨트롤 자동 숨김을 지원하는 감상 화면으로 전환됩니다.
- **4종 실시간 FFT 오디오 비주얼라이저** — **Frame**, **Circular**, **Studio**, **Horizon** 4가지 스타일을 지원하며 컬러 톤(*모노크롬 / 앨범 포인트 톤 / 샴페인 골드*)과 반응 민감도를 조절할 수 있습니다.
- **실시간 10밴드 이퀄라이저** — 31 Hz ~ 16 kHz 10밴드 DSP EQ와 프리앰프, 8가지 기본 프리셋(*Flat, Bass Boost, Vocal, Pop, Rock, Jazz, Classical, Electronic*) 및 사용자 설정을 지원합니다.
- **플로팅 미니 플레이어** — 항상 위(Always on Top) 표시, 위치 고정, 부드러운 배경 크로스페이드, 마우스 휠 볼륨 조절을 지원합니다.
- **Windows 환경 최적화** — 플레이어 내에서 오디오 출력 장치(스피커/헤드셋 등) 즉시 전환, Windows 미디어 컨트롤(SMTC) 연동, 단일 인스턴스 실행 및 오디오 파일 연결을 지원합니다.
- **간편한 라이브러리 & 재생목록** — 다중 폴더 스캔 및 캐시, 앨범 그리드·곡 목록 보기, 실시간 검색, 드래그 앤 드롭 재생목록 관리, 좋아요 표시, 마지막 재생 위치 및 대기열 자동 복원.
- **테마 & 8개 언어 지원** — 다크 / 화이트 테마 전환, 애니메이션 끄기(성능 우선 모드) 옵션, 8개 언어(한국어, English, 日本語, 简体中文, 繁體中文, Español, Français, Deutsch) 지원.

<!-- 여기에 미니 플레이어 / 이퀄라이저 / 화이트 테마 스크린샷을 드래그 앤 드롭하세요 (선택) -->

## 🎵 지원 오디오 포맷

`MP3` · `FLAC` · `WAV` · `M4A` · `AAC` · `OGG` · `OPUS` · `AIFF`

## ⬇️ 다운로드 및 설치 (Windows 64-bit)

**[GitHub Releases](https://github.com/veloraplayer/Velora/releases/latest)** 페이지에서 원하는 버전을 다운로드하세요.

| 배포 형태 | 설명 |
| :--- | :--- |
| **`Velora-Setup-x.x.x-win64.exe`** *(권장)* | Windows 설치 파일. 기본값으로 관리자 권한이 필요 없으며, 오디오 파일 연결 옵션을 지원합니다. |
| **`Velora-Portable-x.x.x-win64.zip`** | 무설치 포터블 버전. 압축을 풀면 바로 실행되며 설정과 재생목록은 실행 폴더 내 `data/`에 저장됩니다. |
| **`SHA256SUMS.txt`** | 파일 무결성 검증용 SHA-256 체크섬 파일. |

> [!NOTE]
> **Windows SmartScreen 경고 안내:** 개인 배포 프로그램으로 유료 코드 서명이 적용되어 있지 않아, 최초 실행 시 *"Windows의 PC 보호"* 안내가 표시될 수 있습니다. **추가 정보 → 실행**을 눌러 실행하실 수 있으며, `SHA256SUMS.txt`로 파일 무결성을 확인하실 수 있습니다.

## ⌨️ 주요 조작 및 단축키

| 기능 | 단축키 / 제스처 |
| :--- | :--- |
| 재생 / 일시정지 | `Space` |
| 감상 모드 진입 / 닫기 | 하단 플레이어 바 더블클릭 또는 위/아래 드래그 |
| 비주얼라이저 전환 (감상 모드) | 앨범 아트 좌클릭 (우클릭으로 세부 설정) |
| 감상 모드 배경 블러 강도 변경 | 감상 모드 배경 빈 공간 우클릭 |
| 전체화면 전환 | `F11` / `Alt+Enter` |
| 앨범 커버 · 곡 목록 크기 조절 | `Ctrl` + 마우스 휠 |
| 환경 설정 / 도움말 및 단축키 | `Ctrl+,` / `F1` |

## 💬 피드백 및 후원

버그 제보, 개선 아이디어, 사용 후기 모두 환영합니다!

- **GitHub Issues:** [github.com/veloraplayer/Velora/issues](https://github.com/veloraplayer/Velora/issues)
- **이메일:** veloraplayer@gmail.com
- **개발 후원 (선택):** [ko-fi.com/velora_player](https://ko-fi.com/velora_player)

## 📄 라이선스

Velora는 무료로 제공되는 프리웨어(독점 소프트웨어)입니다. Copyright © 2026 Velora. All rights reserved.  
PySide6/Qt6 및 libsndfile(LGPL 동적 링크) 등 오픈소스 서드파티 라이선스 고지는 [THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt)에서 확인하실 수 있습니다.
