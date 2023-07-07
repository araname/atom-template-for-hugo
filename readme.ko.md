# Atom Template for Hugo
Hugo가 Atom 피드를 여러분의 사이트에 생성할 수 있게 합니다

## 설치하기
이 저장소를 `<your-site-dir>/themes/atom-template-for-hugo` 디렉토리에 복제 또는 다운로드합니다.

## 구성하기
사이트 구성 파일에 현재 테마를 나타내도록 줄을 추가합니다:
1. `atom-template-for-hugo`를 테마 목록 변수의 가장 왼쪽 요소로 추가합니다. 예를 들면:
    ```
    theme = ['atom-template-for-hugo', 'my-theme']
    ```
2. `Atom`을 Atom 피드를 만드려는 모든 페이지 종류에 추가합니다 (기본값은 `['HTML', 'RSS']`):
    ```
    [outputs]
    home = ['HTML',  'Atom', 'RSS']
    section = ['HTML',  'Atom', 'RSS']
    taxonomy = ['HTML',  'Atom', 'RSS']
    term = ['HTML',  'Atom', 'RSS']
    ```
