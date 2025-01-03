# look

> 정렬된 파일에서 특정 접두사로 시작하는 줄을 표시.
> 참고: 파일 내의 줄은 정렬되어 있어야 합니다.
> 같이 보기: `grep`, `sort`.
> 더 많은 정보: <https://man.openbsd.org/look>.

- 특정 파일에서 특정 접두사로 시작하는 줄 검색:

`look {{접두사}} {{경로/대상/파일}}`

- 대소문자 구분 없이 ([f]) 영숫자 문자만으로 검색 ([d]):

`look -f -d {{접두사}} {{경로/대상/파일}}`

- 문자열 종료 문자 지정 (기본값은 공백):

`look -t {{,}}`

- `/usr/share/dict/words`에서 검색 (`-d`와 `-f`가 기본적으로 적용됨):

`look {{접두사}}`
