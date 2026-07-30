# GitHub Pages로 포트폴리오 배포하기

이 폴더에는 `index.html`과 포트폴리오에 쓰이는 모든 이미지·영상 파일이 들어있습니다.
GitHub 계정만 있으면 명령어(git) 없이 웹 화면만으로 5분 안에 배포할 수 있습니다.

## 1. 새 저장소(Repository) 만들기
1. [github.com](https://github.com) 로그인
2. 오른쪽 위 **+** 버튼 → **New repository** 클릭
3. Repository name 입력 (예: `yewon-portfolio`)
4. **Public** 선택 (Pages 무료 사용을 위해 Public 권장)
5. 그 외 옵션은 그대로 두고 **Create repository** 클릭

## 2. 파일 업로드
1. 방금 만든 저장소 페이지에서 **Add file → Upload files** 클릭
2. 이 폴더 안의 파일을 **전부** 선택해서 끌어다 놓기 (index.html 포함, 폴더째로 말고 안의 파일들을 전부)
   - 영상 파일 용량이 커서 업로드가 오래 걸릴 수 있어요 (총 약 60MB)
3. 하단 **Commit changes** 클릭

## 3. GitHub Pages 활성화
1. 저장소 상단 메뉴에서 **Settings** 클릭
2. 왼쪽 메뉴에서 **Pages** 클릭
3. **Source**를 `Deploy from a branch`로 설정
4. Branch를 `main` (또는 `master`), 폴더를 `/ (root)`로 선택 후 **Save**
5. 1~2분 정도 기다리면 페이지 상단에
   `Your site is live at https://[사용자이름].github.io/[저장소이름]/`
   라는 링크가 표시됩니다. 이 링크가 제출용 포트폴리오 링크입니다.

## 참고 사항
- 파일명을 `index.html`로 그대로 유지해야 링크 주소만으로 바로 열립니다.
- 영상 파일이 큰 편이라 (특히 `hambyeokru-showcase.mp4`, `dog-animation.mp4`) GitHub 저장소 용량 제한(무료 기준 1GB)에는 문제없지만, 페이지 로딩이 다소 느릴 수 있습니다.
- 이후에도 내용을 계속 수정하고 싶다면, 저장소 페이지에서 파일을 다시 업로드(덮어쓰기)하면 자동으로 사이트에 반영됩니다.
