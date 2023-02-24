<h1>Git 기초</h1>

- 메인 관리자는 Master branch, main에 덧붙이는 사람들을 각각 branch라고 함. 

- 다른 branch들을 확인하여 declined / comment를 통해 피드백 가능. -> merge로 메인 코드에 추가.
</br>
----------------------
</br>

1. git init : 폴더에 git성격.



2. git remote add origin : 깃허브 코드저장소와 폴더를 연결.
> user.name과 user.email 항상 주의할 것.

3. git add . : 폴더 안의 모든 파일들을 올릴 준비.

4. git commit -m 'message' : 메시지 내용과 함께 올릴 코드 준비.

5. git push (origin master) : 해당 branch에 코드 push.
> origin은 저장소 / master은 branch
> 
> git add -> commit -> push 

6. git clone 'address' : 해당 깃헙 저장소에 있는 소스코드 내려받음.