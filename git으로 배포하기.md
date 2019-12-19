# 하 ㅠㅠ
### github은 spa를 지원해주지 않는다
따라서 다음과 같은 트릭이 필요하다
#### 방법 1 404page.html 만들기
router의 route를 인식하지 못하고 404page를 반환하기때문에 이렇게 해줌<br/>
https://iamsjy17.github.io/react/2018/11/04/githubpage-SPA.html
<br/>
#### 방법 2 Hashrouter 사용
뭔지는 모르겠는데 gh-page는 browserRouter를 인식하지 못한다고 함 그래서 Hashrouter를 사용함 
https://juunone.github.io/cra-ghpages2/

#### 방법 3 Heroku
gh-page안되서 빡쳐서 heroku로 하려했는데 실패함 
https://www.youtube.com/watch?v=r0ECufCyyyw
