index.html: 프로젝트의 메인 HTML 파일입니다.
scss/: 스타일시트를 저장하는 폴더입니다. 주로 styles.css 파일이 포함됩니다.
js/: JavaScript 파일을 저장하는 폴더입니다. 주로 scripts.js 파일이 포함됩니다.
images/: 프로젝트에 사용되는 이미지 파일들을 저장하는 폴더입니다.
assets/: 폰트, 아이콘 등 기타 정적 파일들을 저장하는 폴더입니다.
README.md: 프로젝트에 대한 설명과 사용법을 기록하는 파일입니다.
.gitignore: Git에서 추적하지 않을 파일이나 폴더를 명시하는 파일입니다.


폴더 및 파일 설명
base/: 기본적인 스타일을 정의하는 파일들입니다.
    _reset.scss: 브라우저 기본 스타일을 초기화하는 코드.
    _typography.scss: 기본 타이포그래피 스타일 정의.

utils/: 변수와 믹스인 등을 정의합니다.
    _variables.scss: SCSS 변수 정의.
    _mixins.scss: 재사용 가능한 믹스인 정의.

style: 페이지별 스타일 정의
    'style/header';
    'style/footer';
    "style/style.scss";

main.scss: 모든 개별 SCSS 파일들을 임포트하여 하나의 CSS 파일로 컴파일합니다.

