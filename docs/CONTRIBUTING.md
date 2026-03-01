# 기여 가이드 / Contributing Guide

이 저장소는 한봄고등학교 웹사이트의 기록 보존을 위한 프로젝트입니다. 기여를 원하시는 분들은 아래의 **상세 가이드**를 반드시 확인해 주세요.

This repository is a project for preserving records of the Hanbom High School website. If you would like to contribute, please **must** check the detailed guide below.

---

## 아카이빙 방법 / Archiving Method

아카이빙에는 **SingleFile** (Chrome/Firefox 확장 프로그램)을 사용하며, 다음의 절차를 엄격히 준수해야 합니다.

We use **SingleFile** (Chrome/Firefox extension) for archiving, and the following procedures must be strictly followed.

### 1. 폴더 구조 생성 / Create Folder Structure
- **大탭 (Main Tabs)**: 웹사이트 상단 네비게이션 바의 대분류 이름을 그대로 사용하여 `Archiv/` 내에 폴더를 생성합니다. (파일명 사용 불가 특수문자는 공백으로 대체)
- **小탭 (Sub Tabs)**: 대분류 안에 소분류가 있다면 마찬가지로 폴더를 생성합니다.
- **Main Tabs**: Create folders in `Archiv/` using the exact names of the main navigation tabs. (Replace invalid characters with spaces).
- **Sub Tabs**: If there are sub-menus within a main tab, create corresponding sub-folders.

### 2. 페이지 저장 (SingleFile) / Save Page (SingleFile)
- 해당 탭의 이름을 그대로 사용하여 `.html` 파일로 저장합니다.
- **중요**: 저장 전, 페이지 디자인 및 리소스가 완벽히 로드되도록 **페이지 맨 아래까지 스크롤**해야 합니다.
- **PDF 뷰어 등**: 페이지 내에 PDF 뷰어나 문서 미리보기가 포함된 경우, 해당 영역도 최소 한 번은 맨 아래까지 스크롤하여 모든 페이지가 로드되게 해야 합니다.
- Save as an `.html` file using the name of the tab.
- **IMPORTANT**: Before saving, you **must scroll to the bottom** of the page to ensure all design elements and resources are fully loaded.
- **PDF Viewers, etc.**: If the page includes a PDF viewer or document preview, scroll that area to the bottom at least once to ensure all contents are captured.

### 3. 별도 리소스 다운로드 / Downloading Separate Resources
- 별도로 다운로드해야 하는 파일(PDF, HWP, 이미지 등)이 있는 경우, 해당 폴더 내에 `세부`, `pdf`, `문서`, `hwp`, `사진`, `이미지` 중 적절한 이름의 폴더를 만들어 저장합니다.
- If there are files that must be downloaded separately (PDF, HWP, images, etc.), create a folder named appropriately (e.g., `details`, `pdf`, `docs`, `hwp`, `photos`, `images`) and save them there.

### 4. 파일 크기 및 압축 / File Size & Compression
- 개별 파일의 크기는 **100MB**를 초과할 수 없습니다.
- 무손실 방식으로 크기를 줄일 수 없는 경우, **분할 압축**하여 업로드해야 합니다.
- Individual file size **must not exceed 100MB**.
- If the size cannot be reduced losslessly, you must use **split archiving (multi-part compression)** for the upload.

---

## 주의사항 / Important Notes

- 개인정보가 포함된 페이지는 아카이브하지 마세요. / Do not archive pages containing personal information.
- 로그인이 필요한 페이지는 신중하게 검토 후 아카이브하시기 바랍니다. / Please carefully review and archive pages that require login.
