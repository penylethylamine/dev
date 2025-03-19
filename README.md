# dev
## 소개
2 주차 연습 과제
## 시작하기
### 필요 조건
- npm version 6.x
- Node.js version 12.x
### 설치 방법
bash
git clone https://github.com/username/repo.git
cd repo
npm install
변경사항 저장 및 푸시하기
git add README.md
git commit -m "Update README.md with comprehensive structure"
git push origin main
추가 팁
배지(Badges) 추가하기
빌드 상태, 라이선스, 버전 등 표시
스크린샷이나 GIF 추가
목차 제공 (큰 문서의 경우)
간결하고 명확하게 작성
README.md 예시 (계속)
사용법
기본적인 사용 예시를 코드와 함께 제공합니다.
const example = require('example-module');
example.doSomething();
기능
주요 기능 목록을 작성합니다:
기능 1: 설명
기능 2: 설명
기능 3: 설명
기여 방법
기여에 관심이 있으시면 CONTRIBUTING.md를
참조해주세요.
라이선스
이 프로젝트는 MIT 라이선스 하에 배포됩니다 - 자세한 내용은
LICENSE.md 파일을 참조하세요.
CONTRIBUTING.md의 목적
기여자에게 프로젝트 참여 방법 안내
코드 작성 스타일, 커밋 메시지 규칙 등 가이드라인 제공
기여 프로세스 설명
기본 구조
기여 프로세스 개요
코드 스타일 가이드
커밋 메시지 형식
이슈 및 PR 작성 방법
테스트 지침
행동 강령(Code of Conduct)
CONTRIBUTING.md 예시 (시작 부분)
# 기여 가이드라인
프로젝트에 기여해 주셔서 감사합니다! 이 문서는 기여 과정을 안내합니다.
## 기여 프로세스
1. 먼저 이슈를 확인하거나 새로운 이슈를 생성하세요.
2. 프로젝트를 포크(Fork)하세요.
3. 새 브랜치를 생성하세요 (`git checkout -b feature/amazing-feature`).
4. 변경사항을 커밋하세요 (`git commit -m 'Add amazing feature'`).
5. 브랜치를 푸시하세요 (`git push origin feature/amazing-feature`).
6. Pull Request를 생성하세요.
변경사항 저장 및 푸시하기
git add CONTRIBUTING.md
git commit -m "Add CONTRIBUTING.md with guidelines"
git push origin main
추가 팁
새 기여자를 위한 "good first issue" 태그 소개
개발 환경 설정 방법 상세 설명
커뮤니케이션 채널 (Discord, Slack 등) 안내
코드 리뷰 과정과 기대사항 설명
CONTRIBUTING.md 예시 (계속)
## 커밋 메시지 형식
커밋 메시지는 다음 형식을 따릅니다:
- feat: 새로운 기능 추가
- fix: 버그 수정
- docs: 문서 변경
- style: 코드 스타일 변경 (기능 변경 없음)
- refactor: 코드 리팩토링
- test: 테스트 추가 또는 수정
- chore: 빌드 프로세스 또는 도구 변경
## 코딩 스타일
* 인덴트는 스페이스 2칸을 사용합니다.
* 함수와 변수 이름은 camelCase를 사용합니다.
* 클래스 이름은 PascalCase를 사용합니다.
* 상수는 UPPER_SNAKE_CASE를 사용합니다.
## Pull Request 가이드라인
* 모든 PR은 기존 이슈를 참조해야 합니다.
* PR 설명에 변경사항과 목적을 명확히 작성하세요.
오픈소스 라이선스의 중요성
코드의 사용, 수정, 배포 권한을 명확히 정의
법적 보호와 책임의 한계 설정
프로젝트의 철학과 의도 반영
주요 오픈소스 라이선스 종류
1. MIT 라이선스: 매우 허용적, 간단한 조건
2. Apache 라이선스 2.0: 특허권 명시적 부여
3. GPL: 파생 작업도 같은 라이선스 적용
4. BSD 라이선스: 간단하고 허용적인 라이선스
GitHub을 통한 라이선스 추가
1. 저장소에서 "Add file" > "Create new file" 클릭
2. 파일 이름에 "LICENSE" 또는 "LICENSE.md" 입력
3. 창 위쪽에 "Choose a license template" 버튼 클릭
4. 원하는 라이선스 선택 후 정보 입력
5. "Commit new file" 클릭
변경사항 동기화
git pull origin main
