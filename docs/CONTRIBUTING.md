# 기여 가이드 / Contributing Guide

이 저장소는 한봄고등학교 웹사이트의 기록 보존을 위한 프로젝트입니다. 기여를 원하시는 분들은 아래 가이드를 확인해 주세요.

This repository is a project for preserving records of the Hanbom High School website. If you would like to contribute, please check the guide below.

---

## 아카이빙 도구 / Archiving Tool

아카이빙에는 **SingleFile** (Chrome/Firefox 확장 프로그램) 사용을 권장합니다.

We recommend using **SingleFile** (Chrome/Firefox extension) for archiving.

1.  **SingleFile** 설치 / Install **SingleFile**.
2.  아카이브할 페이지로 이동 / Navigate to the page you want to archive.
3.  SingleFile 아이콘을 클릭하여 페이지를 저장 / Click the SingleFile icon to save the page.
4.  저장된 파일은 모든 리소스가 포함된 단일 HTML 파일이어야 합니다. / The saved file must be a single HTML file containing all resources.

---

## 파일 명명 규칙 / Naming Conventions

파일 이름은 웹사이트의 메뉴 구조와 일치하도록 지정해 주세요.

Please name the files to match the menu structure of the website.

-   **예시 (Example):** `학교소개 > 학교상징` 페이지는 `Archiv/학교소개/학교상징.html`로 저장합니다.
-   폴더 구조는 실제 웹사이트의 상단 메뉴 구성을 따릅니다. / The folder structure follows the top menu configuration of the actual website.

---

## 디렉터리 구조 / Directory Structure

```
Archiv/
├── [메뉴 명]/
│   └── [서브메뉴 명].html
└── 한봄고등학교.html (메인)
```

---

## 주의사항 / Important Notes

-   개인정보가 포함된 페이지는 아카이브하지 마세요. / Do not archive pages containing personal information.
-   로그인이 필요한 페이지는 신중하게 검토 후 아카이브하시기 바랍니다. / Please carefully review and archive pages that require login.
