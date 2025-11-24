# KAMDA Conference 2025 - Project Plan

## Project Overview

KAMDA (Korean-American Medical Device Association) 컨퍼런스 발표 자료를 웹으로 공개하기 위한 프로젝트

**GitHub Repository**: https://github.com/erickimme/KAMDA-Conference-2025
**Live Site**: https://erickimme.github.io/KAMDA-Conference-2025/

---

## 작업 완료 (2024-11-24)

### 1. Session I 슬라이드 구조 변환
새로운 슬라이드 구조 적용:
```markdown
#### Slide N
![image](path)

**요약**
> 핵심 내용 요약

<details>
<summary>📄 Slide Transcript</summary>
전체 트랜스크립트
</details>
```

**완료된 발표자:**
- ✅ Haja Sittana El Mubarak (12 slides) - FDA Trends & Global Regulation Insights
- ✅ ByungSik Chang (15 slides) - FDA Approval Strategies and Success Cases
- ✅ JungYoup Han (31 slides) - FDA Preparation and Approval Strategy (CRO)
- ✅ Sung Park (7 slides) - Appropriate Risk Allocation in the FDA World

### 2. GitHub Pages 배포
- Git LFS 설정 (PDF, HEIC, PPTX, ZIP, M4A)
- docs 폴더의 이미지는 일반 파일로 저장 (GitHub Pages 호환)
- 메인 페이지 생성 (docs/index.md)
- Session I 네비게이션 추가 (Back to Schedule, Back to Top)

### 3. 파일 구조 정리
```
/docs/                          # GitHub Pages 배포 폴더
├── index.md                    # 메인 페이지 (스케줄)
├── program.png                 # 프로그램 이미지
└── KAMDA Conference 2025 - OCT 23/
    ├── Session I Strategies and FDA Considerations for U.S. Market Entry.md
    └── images/                 # 슬라이드 이미지들
```

---

## 현재 상태

### 배포 완료
- ✅ 메인 페이지 (스케줄, 프로그램 이미지)
- ✅ Session I 상세 페이지 (4명 발표자, 65개 슬라이드)

### 미완료 세션
- ⏸️ Opening Remarks (HeaYeon Lee, YoungHo Choi)
- ⏸️ Session II: U.S. Market Entry Strategy and Insights
- ⏸️ Sponsored Session
- ⏸️ Panel Session

---

## 다음 작업 (TODO)

### 우선순위 높음
1. [ ] Opening Remarks 슬라이드 구조 변환
   - HeaYeon Lee (34 slides)
   - YoungHo Choi (21 slides)
   - 주의: 현재 요약 quotes 없음 - 트랜스크립트에서 생성 필요

2. [ ] Session II 슬라이드 구조 변환
   - MinSoo Seo
   - JungHee Cho
   - Curie Choi
   - Eunjean Je

### 우선순위 중간
3. [ ] Sponsored Session 구조 변환
4. [ ] Panel Session 구조 변환
5. [ ] 각 세션 페이지에 네비게이션 추가

### 우선순위 낮음
6. [ ] 메인 페이지 디자인 개선
7. [ ] 모바일 최적화 확인
8. [ ] 검색 기능 추가 (선택)

---

## 기술 노트

### Git LFS 설정
`.gitattributes`:
```
*.pdf filter=lfs diff=lfs merge=lfs -text
*.heic filter=lfs diff=lfs merge=lfs -text
*.png filter=lfs diff=lfs merge=lfs -text
*.jpg filter=lfs diff=lfs merge=lfs -text
docs/**/*.jpg !filter !diff !merge -text
docs/**/*.png !filter !diff !merge -text
```

### 주요 파일 경로
- 원본 Notion Export: `/Exports/Notion/KAMDA Conference 2025 - OCT 23/`
- 작업 파일: `/Private & Shared/KAMDA Conference 2025 - OCT 23/`
- 배포 파일: `/docs/`

### GitHub Pages 설정
- Source: `main` branch, `/docs` folder
- URL: https://erickimme.github.io/KAMDA-Conference-2025/

---

## 링크

- **메인 페이지**: https://erickimme.github.io/KAMDA-Conference-2025/
- **Session I**: https://erickimme.github.io/KAMDA-Conference-2025/KAMDA%20Conference%202025%20-%20OCT%2023/Session%20I%20Strategies%20and%20FDA%20Considerations%20for%20U.S.%20Market%20Entry
- **GitHub Repo**: https://github.com/erickimme/KAMDA-Conference-2025
- **KAMDA Website**: https://kamdausa.org/
- **Event Page**: https://www.milgram.io/community/kamdakoreanamericanmedicaldevicesassociation/events

---

*Last updated: 2024-11-24*
