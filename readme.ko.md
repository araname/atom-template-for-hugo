# Atom Template for Hugo
Hugo가 Atom 피드를 여러분의 사이트에 생성할 수 있게 합니다

## 적용하기
1. 이 저장소를 `<your-site-dir>/themes/atom-template-for-hugo` 디렉터리에 복제 또는 다운로드합니다.
2. 여러분의 사이트의 `config.toml`에 다음과 같이 추가합니다:
    1. `atom-template-for-hugo`를 테마 목록 변수의 가장 왼쪽 요소로 추가합니다. 예를 들면:
    ```
    theme = ["atom-template-for-hugo", "my-theme"]
    ```
    2. `Atom`을 Atom 피드를 만드려는 모든 페이지 종류에 추가합니다 (기본값은 `["HTML", "RSS"]`):
    ```
    [outputs]
    home = ["HTML", "RSS", "Atom"]
    section = ["HTML", "RSS", "Atom"]
    taxonomy = ["HTML", "RSS", "Atom"]
    term = ["HTML", "RSS", "Atom"]
    ```
