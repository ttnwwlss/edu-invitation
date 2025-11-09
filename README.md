# 교육 안내 페이지 생성기 (GitHub Pages용)

이 저장소는 **모바일 청첩장 스타일의 교육 안내 페이지**를 손쉽게 생성/배포할 수 있는 도구를 제공합니다.

## 기능
- Pretendard 폰트, 4가지 컬러 테마 (Yellow/Green/Blue/Orange)
- 로고/대표 이미지 업로드 (카카오톡 공유 썸네일용 og:image 지원)
- **교육명 토글 표시**, 브랜드명 직접 입력
- 6개 섹션(on/off): 배경이미지 / 교육 개요 / 셔틀탑승 안내 / 교육 일정표(표형) / 기타 안내사항 / 사전교육(YouTube 썸네일 리스트)
- LocalStorage 저장/불러오기, **HTML로 내보내기** (완성 페이지 생성)
- GitHub Pages 배포 최적화

## 사용법
1. `index.html`을 브라우저로 열기
2. 좌측 패널에서 내용 입력 → 우측 미리보기 실시간 반영
3. **저장** 버튼으로 입력값 보존 (브라우저별 저장)
4. **HTML로 내보내기** 버튼으로 완성 페이지를 파일로 저장
5. GitHub 저장소의 `/generated/` 폴더에 업로드하여 배포

## 카카오톡 공유 썸네일(og:image)
- 대표 이미지 업로드 시 `og:image`가 자동 설정됩니다.
- 일부 플랫폼은 `data:` URL을 지원하지 않을 수 있으므로, **가능하면 외부 URL**(예: 해당 저장소의 이미지 RAW URL)을 `og:image URL` 칸에 입력하는 것을 권장합니다.

## GitHub Pages 배포
- 저장소 Settings → Pages → Branch: `main` / root → Save
- 배포 주소 예: `https://username.github.io/edu-template/`

---

© 2025
