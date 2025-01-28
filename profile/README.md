<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Feventor-site&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>

# 모든 이벤트 정보를 제공하는 사이트

**https://www.eventor.store**

<div align="center" dir="auto">
  <div class="markdown-heading" dir="auto">
    <h3 class="heading-element" dir="auto"> Eventor 팀 </h3>
  </div>
  <markdown-accessiblity-table data-catalyst="">
    <table>
      <thead>
        <tr>
          <th><a href="https://github.com/Kayas2580"><img src="https://github.com/Kayas2580.png" width="100px" style="max-width: 100%;"><br>장우혁</a></th>
          <th><a href="https://github.com/dlrudgjs104"><img src="https://github.com/dlrudgjs104.png" width="100px" style="max-width: 100%;"><br>이경헌</a></th>
          <th><a href="https://github.com/leesong-h"><img src="https://github.com/leesong-h.png" width="100px" style="max-width: 100%;"><br>이송호</a></th>
        </tr>
      </thead>
    </table>
</markdown-accessiblity-table>
</div>

<br><br>

#  Eventor_Repository

- [FRONT](https://github.com/eventor-site/eventor-front)
- [BACK](https://github.com/eventor-site/eventor-back)
- [AUTH](https://github.com/eventor-site/eventor-auth)
- [GATEWAY](https://github.com/eventor-site/eventor-gateway)

---


# 사이트 [https://www.eventor.store](https://www.eventor.store)
- Front-End Server: 8081
- API Gateway Server: 8090
- Auth Server: 8070
- Back-End Server: 8083
  
# 코드 컨벤션
- SonarLint
- 네이버 포멧터 적용(1.1.3 까지만 진행)
[https://bestinu.tistory.com/64](https://bestinu.tistory.com/64)

RESTful 관점
**GET**은 데이터 조회에 사용하며, 서버의 상태를 변경하지 않는 안전한 요청(Safe Method)으로 간주됩니다.
**POST**는 데이터를 서버로 전송하여 서버가 작업을 처리하도록 요청할 때 사용됩니다. 존재 여부 확인은 단순 조회라기보다는 데이터를 전달하여 검증 작업을 수행하는 과정이므로, POST가 더 RESTful에 부합합니다

# Git-Branch 전략

# Commit 컨벤션
```
feat : 새로운 기능 추가
fix : 버그 수정
docs : 문서 수정
style : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
refactor : 코드 리펙토링
test : 테스트 코드, 리펙토링 테스트 코드 추가
chore : 빌드 업무 수정, 패키지 매니저 수정
```
