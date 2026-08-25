# Magic Note (매직 노트) 랜딩 페이지

macOS용 네이티브 스마트 메모 앱 **Magic Note**의 공식 다운로드 및 설치 안내 랜딩 페이지입니다.

## 🔗 구글 드라이브 다운로드 링크
- **URL**: [Google Drive 다운로드 링크](https://drive.google.com/file/d/16Qkdp1PL6v5PnHdcx_lznPVb0yeWUWc6/view?usp=sharing)

## 📌 주요 구성 내용
1. **Hero & Download CTA**: 원클릭으로 구글 드라이브 다운로드 이동 버튼
2. **보안 및 게이트키퍼(Gatekeeper) 해결 가이드**:
   - Apple 미인증 앱 안내 문구
   - **방법 1 (추천)**: Finder에서 마우스 우클릭 → [열기] → 보안 확인창에서 [열기]
   - **방법 2**: 시스템 설정 → 개인정보 보호 및 보안 → [확인 없이 열기]
   - **방법 3**: 터미널 명령어 원클릭 복사 (`xattr -cr /Applications/MagicNote.app`)
3. **앱 프리뷰 목업**: macOS 창 스타일의 인터랙티브 UI 데모
4. **주요 특징 (Features) & 자주 묻는 질문 (FAQ)**

## 💻 로컬 미리보기 방법
1. Finder에서 `index.html` 파일을 더블 클릭하여 기본 웹 브라우저에서 바로 확인
2. 또는 Python 로컬 서버 실행:
   ```bash
   python3 -m http.server 8000
   ```
   브라우저에서 `http://localhost:8000` 접속

## 🚀 배포 방법 (선택 사항)
- **GitHub Pages**: 본 저장소를 GitHub에 푸시 후 Settings > Pages에서 배포
- **Vercel / Netlify**: 저장소 연동 후 별도 빌드 설정 없이 즉시 배포 가능
