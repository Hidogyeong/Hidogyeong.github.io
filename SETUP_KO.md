# 홈페이지 공개 순서

## 1. 템플릿에서 저장소 만들기

1. https://github.com/academicpages/academicpages.github.io 접속
2. **Use this template → Create a new repository** 선택
3. Owner: **Hidogyeong**
4. Repository name: **Hidogyeong.github.io**
5. **Public** 선택, **Include all branches**는 선택하지 않기
6. **Create repository** 클릭

저장소: https://github.com/Hidogyeong/Hidogyeong.github.io

## 2. 준비된 내용 반영

이 패키지는 단순 덮어쓰기용 파일 모음이 아니라 샘플 자료를 정리한 전체 사이트 소스입니다. 새 템플릿 저장소에 반영할 때 기존 샘플 논문·이력·페이지도 함께 정리해야 합니다.

논문 정보는 `_data/publications.yml` 한 곳에서 Home, CV, Publications에 공통으로 반영됩니다. Google Scholar 프로필 자체와 PDF 이력서는 별도 자료입니다.

## 3. GitHub Pages 켜기

내용 반영 후 저장소의 **Settings → Pages**에서:

- Source: **Deploy from a branch**
- Branch: **master**
- Folder: **/(root)**
- **Save** 클릭

Actions의 Pages build and deployment 결과를 확인합니다. 별도 `Jekyll build` 작업은 빌드 검사이며 Pages 공개 설정을 대신하지 않습니다. 공개 후 https://hidogyeong.github.io 에서 Home·CV·Publications와 각 링크를 확인합니다.

## 4. CV 보완

현재는 확인된 박사과정 소속과 연구·구현 경험만 넣었습니다. 아래 정보를 제공하면 완성도를 높일 수 있습니다.

- 학사·석사 학교, 학과/전공, 입학·졸업 연월
- 박사과정 학과/전공 및 표시할 지도교수·연구실
- 공개할 이메일
- 선택: 프로필 사진, 기존 CV PDF

현재 프로필 이미지는 이름 이니셜입니다. 학사·석사 이력, 연구실 세부 정보, 연락처, 수상, 미공개 논문은 추측해서 추가하지 않았습니다.

공식 안내: https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template

GitHub Pages 설정: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
