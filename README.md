# cs-interview-visuals

모의면접 중 이해가 안 된 개념을 설명하려고 만든 **인터랙티브 HTML 그림** 모음입니다.
GitHub Pages로 배포하고, 노션 정리 페이지에 웹 주소로 임베드해서 봅니다.

- 목록: https://aleexender.github.io/cs-interview-visuals/

## 폴더 규칙

주제별 폴더에 **그 주제에 해당하는 그림만** 넣습니다. 폴더는 파일이 생길 때 만듭니다.

| 폴더 | 주제 |
|---|---|
| `db/` | 트랜잭션, 격리 수준, MVCC, 락, 인덱스 |
| `spring/` | `@Transactional`, 프록시, 트랜잭션 동기화, MVC |
| `jvm/` | 메모리 구조, GC, 클래스 로딩 |
| `concurrency/` | 스레드, 동시성, `volatile`, 락 |
| `network/` | TCP/IP, HTTP, TLS, DNS |
| `os/` | 프로세스, 시스템 콜, I/O, 소켓 |
| `jpa/` | 영속성 컨텍스트, N+1, 페치 전략 |

- 파일 이름: 영문 소문자 kebab-case (`mvcc-read-view.html`). URL이 깔끔해집니다.
- 새 파일을 넣으면 `index.html` 목록에도 한 줄 추가합니다.
- 각 HTML은 외부 의존성 없이 파일 하나로 동작합니다.
