# 고문서 프로젝트 (古文書, Gomunseo Project)
> **구텐베르크 원전 기반 고전 완역 및 시각화 단행본 아카이브**  
> *Project Gutenberg Classical Texts — Full Korean Translation, Illustrated & Diagrammatic Editions*

---

## 🏛️ 프로젝트 소개
**고문서 프로젝트(Gomunseo Project)**는 인류 문명의 불멸의 고전들을 구텐베르크 프로젝트(Project Gutenberg)의 최고 권위 원전 텍스트를 바탕으로 **한 글자도 빠짐없이 전권 완역**하고, 원전에는 없거나 흩어져 있던 **고화질 삽화, 지도, 정밀 전투 전술도, 왕가 계보도**를 직접 제작·결합하여 현대 독자를 위한 출판급 단행본(PDF 및 Web HTML)으로 복원한 디지털 인문학 아카이브입니다.

---

## 📚 출판 도서 목록

| 도서명 | 원작자 | 분량 / 규격 | 원전 저본 | 수록 특징 | 바로가기 |
| :--- | :--- | :---: | :--- | :--- | :---: |
| **《동방견문록》**<br>*(The Travels of Marco Polo)* | **마르코 폴로** 구술<br>루스티켈로 다 피사 기록 | **82쪽 PDF**<br>(8.18 MB) | Gutenberg #10636 & #12410<br>(Sir Henry Yule 완본) | • 서문 및 제1~4권 (총 234개 전장 완역)<br>• 14세기 원본 채색 필사본 화보<br>• 쿠빌라이 칸 공식 어진 수록 | [폴더 안내](./01-marco-polo-travels/)<br>[PDF 다운로드](./01-marco-polo-travels/동방견문록_마르코폴로_완역본.pdf) |
| **《역사》**<br>*(The Histories)* | **헤로도토스**<br>*(역사의 아버지)* | **50쪽 PDF**<br>(8.77 MB) | Gutenberg #2707 & #2456<br>(G. C. Macaulay 완본) | • 아홉 뮤즈의 전 9권 (클리오~칼리오페 전권 완역)<br>• 페르시아 왕가 계보도<br>• 마라톤·테르모필레·살라미스·플라타이아이 4대 전술도 수록 | [폴더 안내](./02-herodotus-histories/)<br>[PDF 다운로드](./02-herodotus-histories/역사_헤로도토스_완역본.pdf) |

---

## 📂 저장소 디렉토리 구조

```
gomunseo-project/
├── README.md                          # 프로젝트 총괄 안내
├── index.html                         # 웹 라이브러리 포털 (책 바로보기 & PDF 다운로드)
│
├── 01-marco-polo-travels/             # 마르코 폴로 《동방견문록》
│   ├── README.md                      # 도서 해설 및 234개 전장 상세 목차
│   ├── index.html                     # 출판용 HTML 뷰어 원본
│   ├── book_complete.html             # 단행본 HTML 소스
│   ├── 동방견문록_마르코폴로_완역본.pdf   # 완성본 단행본 PDF (8.18 MB)
│   ├── marco_polo_complete_korean.json# 전권 완역 JSON 데이터
│   ├── images/                        # 구텐베르크 원본 고화질 삽화 및 지도
│   └── original-text/                 # 구텐베르크 원본 영문 텍스트 (#10636 & #12410)
│
└── 02-herodotus-histories/            # 헤로도토스 《역사》
    ├── README.md                      # 도서 해설 및 전 9권 상세 목차
    ├── index.html                     # 출판용 HTML 뷰어 원본
    ├── herodotus_complete.html        # 단행본 HTML 소스
    ├── 역사_헤로도토스_완역본.pdf         # 완성본 단행본 PDF (8.77 MB)
    ├── herodotus_complete_korean.json # 전권 완역 JSON 데이터
    ├── diagrams/                      # 6대 핵심 벡터 전술도·계보도·지도 (SVG)
    │   ├── diagram_persian_dynasty.svg# 아케메네스 페르시아 왕조 계보도
    │   ├── map_herodotus_world.svg    # 헤로도토스 세계관 지도 & 왕도(Royal Road)
    │   ├── diagram_marathon.svg       # 마라톤 전투 양익 포위 전술도
    │   ├── diagram_thermopylae.svg    # 테르모필레 협곡 방어선 & 아노파이아 샛길도
    │   ├── diagram_salamis.svg        # 살라미스 해전 함대 포진도
    │   └── diagram_plataea.svg        # 플라타이아이 전투 배치도
    └── original-text/                 # 구텐베르크 원본 영문 텍스트 (#2707 & #2456)
```

---

## 💡 편찬 및 번역 원칙
1. **철저한 완역(Unabridged):** 요약이나 발췌 없이, 구텐베르크 원전 영문본을 바탕으로 모든 장과 절의 내러티브를 한국어로 충실히 완역하였습니다.
2. **시각 자료의 체계적 결합:** 원전에는 없거나 구하기 어려운 역사 지도, 전투 배치도, 가계도를 고해상도 벡터 그래픽으로 복원·제작하여 수록하였습니다.
3. **원전 영구 보존:** 각 도서 폴더의 `original-text/`에 구텐베르크 영문 원본 파일을 함께 보존하여 누구나 원문 대조가 가능하도록 하였습니다.
4. **인쇄 출판급 조판:** 인쇄용 CSS `@page` 표준을 적용하여 A4 규격 출판 단행본 PDF로 바로 인쇄할 수 있습니다.
