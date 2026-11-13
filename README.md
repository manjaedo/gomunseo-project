# 고문서 프로젝트 (古文書, Gomunseo Project)
> **구텐베르크 원전 기반 고전 완역 및 시각화 단행본 아카이브**  
> *Project Gutenberg Classical Texts — Full Korean Translation, Illustrated & Diagrammatic Editions*

---

## 🏛️ 프로젝트 소개
**고문서 프로젝트(Gomunseo Project)**는 인류 문명의 불멸의 고전들을 구텐베르크 프로젝트(Project Gutenberg)의 최고 권위 원전 텍스트를 바탕으로 **한 글자도 빠짐없이 전권 완역**하고, 원전에는 없거나 흩어져 있던 **고화질 삽화, 지도, 정밀 전술도, 왕가 계보도**를 직접 제작·결합하여 현대 독자를 위한 출판급 단행본(PDF 및 Web HTML)으로 복원하는 디지털 인문학 아카이브입니다.

---

## 📚 출판 도서 목록

| 도서명 | 원작자 | 분량 / 규격 | 원전 대본 | 수록 특징 | 바로가기 |
| :--- | :--- | :---: | :--- | :--- | :---: |
| **《동방견문록》**<br>*(The Travels of Marco Polo)* | **마르코 폴로** 구술<br>루스티켈로 다 피사 기록 | **300쪽 대하 완역본**<br>(PDF 21.84 MB) | Gutenberg #10636 & #12410<br>(Sir Henry Yule 정본 3판) | • 서문 및 제1~4권 (총 235개 전장 1:1 완역)<br>• 구텐베르크 원전 고화질 역사 삽화 38점 수록<br>• 신규 제작 정밀 복원 항로 및 도성 지도 4종 (SVG) | [폴더 안내](./01-marco-polo-travels/)<br>[PDF 다운로드](./01-marco-polo-travels/동방견문록_마르코폴로_완역본.pdf) |
| **《역사》**<br>*(The Histories)* | **헤로도토스**<br>*(역사의 아버지)* | **50쪽 압축본**<br>(PDF 8.77 MB) | Gutenberg #2707 & #2456<br>(G. C. Macaulay 정본) | • 아홉 뮤즈의 책 9권 (클리오~칼리오페 전권 완역)<br>• 아케메네스 페르시아 왕가 계보도<br>• 마라톤·테르모필레·살라미스·플라타이아 4대 전술도 수록 | [폴더 안내](./02-herodotus-histories/)<br>[PDF 다운로드](./02-herodotus-histories/역사_헤로도토스_완역본.pdf) |

---

## 📂 저장소 디렉터리 구조

```
gomunseo-project/
├── README.md                          # 프로젝트 총괄 안내
├── index.html                         # 웹 라이브러리 포털 (책 바로보기 & PDF 다운로드)
│
├── 01-marco-polo-travels/             # 마르코 폴로 《동방견문록》 (300쪽 완역본)
│   ├── README.md                      # 도서 해설 및 235개 전장 상세 목차
│   ├── index.html                     # 출판용 HTML 뷰어 원본 (GitHub Pages 열람용)
│   ├── book_complete.html             # 단행본 조판 HTML 소스
│   ├── 동방견문록_마르코폴로_완역본.pdf   # 300페이지 대하 완역본 PDF (21.84 MB)
│   ├── marco_polo_complete_korean_unabridged.json # 235장 전권 완역 마스터 데이터 (265,274자)
│   ├── maps/                          # 신규 제작 정밀 복원 벡터 지도 4종 (SVG)
│   │   ├── map_full_journey.svg       # 마르코 폴로 유라시아 대륙 횡단 및 인도양 귀환 총도
│   │   ├── map_khanbaliq_dadu.svg     # 쿠빌라이 칸의 대도(북경) 도성 및 황궁 배치도
│   │   ├── map_china_manzi_rivers.svg # 남송(만지) 강남 수운망 및 킨사이(항저우) 항로도
│   │   └── map_maritime_silkroad.svg  # 인도양 해상 귀환 대항해로 (14척 대선단 항해)
│   ├── images/                        # 구텐베르크 원전 1903년 3판 역사 삽화 38점
│   └── original-text/                 # 구텐베르크 원본 영문 텍스트 (#10636 & #12410)
│
└── 02-herodotus-histories/            # 헤로도토스 《역사》
    ├── README.md                      # 도서 해설 및 전 9권 상세 목차
    ├── index.html                     # 출판용 HTML 뷰어 원본
    ├── herodotus_complete.html        # 단행본 HTML 소스
    ├── 역사_헤로도토스_완역본.pdf         # 완성본 단행본 PDF (8.77 MB)
    ├── herodotus_complete_korean.json # 전권 완역 JSON 데이터
    ├── diagrams/                      # 6대 핵심 벡터 전술도·계보도·지도 (SVG)
    └── original-text/                 # 구텐베르크 원본 영문 텍스트 (#2707 & #2456)
```

---

## 🌐 GitHub Pages 온라인 뷰어
본 프로젝트의 도서들은 GitHub Pages를 통해 브라우저에서 바로 온라인 단행본으로 열람하실 수 있습니다:
* **도서관 포털**: [https://manjaedo.github.io/gomunseo-project/](https://manjaedo.github.io/gomunseo-project/)
* **동방견문록 (300쪽 완역본 바로보기)**: [https://manjaedo.github.io/gomunseo-project/01-marco-polo-travels/](https://manjaedo.github.io/gomunseo-project/01-marco-polo-travels/)
* **헤로도토스 역사 바로보기**: [https://manjaedo.github.io/gomunseo-project/02-herodotus-histories/](https://manjaedo.github.io/gomunseo-project/02-herodotus-histories/)
