# 230927

안녕하세요. 동민아입니다.
테스트입니다.




1. replit 에서 import 를 해서 레포지토리(add readme.md c체크하긴 했는데 필수 사항인지는 모르겠음) 와 우선 연결함.
2. 보통의 git 연결과정과 비슷하게 진행.
3. git add.
4. git commit -m "커밋메시지"
5. git push origin main -> remote:permission to 사용자이름/git이름 denied to 사용자이름. fatal: unable to access 'git 주소' : the requested URL returned error: 403
   = > 관련으로 오류 검색하면 token 발급, 제어판 - 일반자격 증명자 내용이 나오는데 하나도 나에게는 적용이 안됐음

6. git push https://{token}@github.com/사용자이름/깃이름.git

contributions 및 git push(레포지스토리에 변동된 사항이 제대로 올라옴)이 정상적으로 됌.

이전에는 contributions만 반영되고 push 는 제대로 안됐는데(=잔디밭만 채워지고 코드가 올라가지 않음)

저 방법으로 push하니 정상적으로 반영됨.

추가) console 창에서 실행해야함!!!!!!!