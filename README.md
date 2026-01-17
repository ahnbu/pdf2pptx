# NotebookLM 변환기 (NotebookLM Converter)

> **구글 NotebookLM**에서 생성된 PDF를 분석하여 **워터마크를 자동으로 제거**하고, **편집 가능한 PowerPoint (PPTX)** 파일로 변환해주는 웹 도구입니다.

이 프로젝트는 NotebookLM이 생성해주는 요약 및 슬라이드 자료에서 로고를 깔끔하게 지우고, 실제 프레젠테이션 환경에서 즉시 활용할 수 있도록 제작되었습니다. 모든 과정은 **100% 브라우저 로컬 환경**에서 처리되어 보안이 유지됩니다.

## ✨ 주요 기능

- **� 워터마크 자동 제거 (NEW)**: NotebookLM 특유의 우측 하단 워터마크를 고도의 알고리즘(Canvas API)으로 감쪽같이 제거합니다.
- **�📂 고화질 PDF to PPTX 변환**: PDF를 **Scale 2.0 (144 DPI)**의 고해상도 이미지로 렌더링하여 선명한 16:9 비율의 PPTX 슬라이드를 생성합니다.
- **🖼️ 이미지 추출**: 특정 슬라이드만 선택하여 고화질 PNG 파일로 개별 다운로드할 수 있습니다.
- **🔒 오프라인급 보안**: 파일이 외부 서버로 전혀 업로드되지 않으며, 모든 변환 작업이 사용자의 기기 내에서만 수행됩니다.
- **✅ 스마트 선택 기능**: 전체 선택/해제 및 개별 페이지 선택을 통해 필요한 부분만 효율적으로 변환할 수 있습니다.
- **👀 실시간 미리보기**: 변환된 결과물을 다운로드 전에 즉시 확인하고 크게 볼 수 있는 모달 뷰어를 제공합니다.

## 🚀 사용 방법

1. `index.html` 파일을 웹 브라우저로 엽니다 (크롬 브라우저 권장).
2. 업로드 영역 하단의 **'워터마크 제거 (NotebookLM)'** 설정을 확인합니다 (기본 활성).
3. 변환할 PDF 파일을 화면 중앙으로 **드래그 앤 드롭**하거나 클릭하여 선택합니다.
4. 로딩 완료(약 10초 이내) 후 나타나는 슬라이드 목록을 확인합니다.
5. 우측 상단의 **'PPTX 다운로드'** 또는 **'이미지 다운로드'** 버튼을 클릭하여 결과물을 저장합니다.

## 🛠️ 기술 스택

프레임워크 없이 순수 웹 기술로 구현되어 매우 가볍고 빠릅니다.

- **Frontend**: HTML5, Vanilla CSS (Modern Design), JavaScript (ES6+)
- **Libraries**:
  - [PDF.js](https://mozilla.github.io/pdf.js/): PDF 파싱 및 고품질 렌더링
  - [PptxGenJS](https://gitbrent.github.io/PptxGenJS/): 클라이언트 사이드 PPTX 파일 생성
  - [Lucide](https://lucide.dev/): 모던 UI 아이콘 세트
- **Core Logic**: Canvas API를 활용한 픽셀 데이터 조작 및 워터마크 영역 패칭

## 👨‍💻 개발자 정보

**안병욱 (Byungwook An)**

- 📧 **Email**: [byungwook.an@gmail.com](mailto:byungwook.an@gmail.com)
- 🧵 **Threads**: [@byungwook.an](https://www.threads.net/@byungwook.an)

---

© 2026 Byungwook An. 모든 권리 보유.
