# 디지몬 스토리 문라이트 한글 패치 v1.0.1

일본판 Nintendo DS용 한글 패치입니다. **[릴리스에서 xdelta 다운로드](https://github.com/TeamLimRyan/DIGIMON_STORY_MOONLIGHT_KOREAN_LOCALIZATION_RELEASE/releases/tag/v1.0.1)**

패치 파일: [`DIGIMON_STORY_MOONLIGHT_KO_v1.0.1.xdelta`](DIGIMON_STORY_MOONLIGHT_KO_v1.0.1.xdelta)

## 원본·적용 후·패치 해시

| 대상 | 크기(bytes) | SHA-256 |
|---|---:|---|
| 원본 일본판 ROM | 67108864 | `fdf159fe6d493a70fbe343a70a7e71656c4b53130f473dfe9c8f77f45d0a6220` |
| 패치 적용 후 ROM | 67108864 | `3d4ed4abd2b30b3577a333e9c831445bae087c5086a517a5626e64abd173341d` |
| xdelta 패치 | 559177 | `92a64e42fafd00b66b6a43bdef1b607a6a64fc5bae9e53d44d8e99aa6a408ba7` |

원본 해시가 일치하는 ROM에만 적용하세요. 다른 지역판, 다른 버전, 트리밍한 ROM, 이미 수정한 ROM은 지원하지 않습니다.

## 적용 방법

1. 직접 보유한 일본판 원본의 SHA-256을 위 표와 비교합니다.
2. xdelta3로 아래 명령을 실행합니다. 원본과 출력은 서로 다른 파일이어야 합니다.

```text
xdelta3 -d -s "original.nds" "DIGIMON_STORY_MOONLIGHT_KO_v1.0.1.xdelta" "korean.nds"
```

3. `korean.nds`의 SHA-256을 적용 후 해시와 비교합니다.

[상세 설치·복구](INSTALL.md) · [호환성과 검증 범위](COMPATIBILITY.md) · [문제 신고](SUPPORT.md) · [권리 안내](NOTICE.md)

게임 ROM, BIOS, 세이브, 키는 포함하지 않습니다. 비공식 한국어화 패치입니다.
