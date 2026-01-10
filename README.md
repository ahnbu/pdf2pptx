# PDF to PPTX Converter

> **구글 NotebookLM**에서 생성된 PDF 슬라이드를 **편집 가능한 PowerPoint (PPTX)** 파일로 변환해주는 웹 도구입니다.

이 프로젝트는 NotebookLM이 생성해주는 유용한 요약 및 슬라이드 자료를 실제 프레젠테이션에서 바로 활용할 수 있도록 돕기 위해 제작되었습니다. 서버로 파일을 전송하지 않고 **브라우저에서 100% 로컬 처리**되므로 보안 걱정 없이 안전하게 사용할 수 있습니다.

## ✨ 주요 기능

- **📂 PDF to PPTX 변환**: PDF의 각 페이지를 고화질 이미지로 변환하여 16:9 비율의 PPTX 슬라이드로 생성합니다.
- **🖼️ 이미지 추출**: 필요한 페이지만 선택하여 개별 PNG 이미지로 다운로드할 수 있습니다.
- **🔒 강력한 보안**: 모든 변환 과정이 클라이언트(브라우저) 내부에서만 수행됩니다. 파일이 외부 서버로 업로드되지 않습니다.
- **✅ 선택적 변환**: 전체 페이지를 한 번에 변환하거나, 원하는 페이지만 콕 집어 변환할 수 있습니다.
- **👀 미리보기 지원**: 변환 전 PDF 내용을 바로 확인하고 확대해서 볼 수 있습니다.

## 🚀 사용 방법

1. `index.html` 파일을 웹 브라우저로 엽니다 (또는 호스팅된 페이지 접속).
2. 변환하고 싶은 PDF 파일을 화면 중앙의 영역으로 **드래그 앤 드롭**하거나 클릭하여 선택합니다.
3. 파일 로딩 후 하단에 생성된 슬라이드 미리보기를 확인합니다.
4. 변환할 페이지를 체크박스로 선택합니다 (기본적으로 전체가 선택됩니다).
5. 우측 상단의 **'PPTX 다운로드'** 버튼을 클릭하여 결과물을 저장합니다.

## 🛠️ 기술 스택

이 프로젝트는 가볍고 빠른 실행을 위해 프레임워크 없이 순수 웹 기술로 구현되었습니다.

- **Frontend**: HTML5, CSS3 (Modern Vanilla CSS), JavaScript
- **Libraries**:
  - [PDF.js](https://mozilla.github.io/pdf.js/): PDF 파일 파싱 및 렌더링
  - [PptxGenJS](https://gitbrent.github.io/PptxGenJS/): 클라이언트 측 PPTX 파일 생성
  - [Lucide](https://lucide.dev/): 아이콘 세트

## 👨‍💻 개발자 정보

**안병욱 (Byungwook An)**

*   📧 **Email**: [byungwook.an@gmail.com](mailto:byungwook.an@gmail.com)
*   🧵 **Threads**: [@byungwook.an](https://www.threads.com/@byungwook.an)

---
© 2026 Byungwook An. All rights reserved.
