========= GIT & GITHUB 연습 ===========

git과 gitHub를 연습하고 있습니다.

pwd         현재 어디있는지 확인
cd c:       c 드라이브로 이동
cd ..       상위 디렉토리로 이동
cd ~        최상위 티렉토리, 루트로 이동
ls          현재 위치해있는 디렉토리 폴더와 파일보임


git inint   저장소로 만든다
ls -al      숨긴파일 까지 다 보임
git status  현재 상태 확인

global user.email "메일"
git config --global user.name"아이디"

커밋지정 (하나의 버전)
git add 파일 명 / git add.(추가하지 않은 모든 파일) 
git commit -m"메세지"    
git push -u origin master       파일 올리기

git remote set-url origin https://<발급받은토큰>@github.com/<아이디>/<리파지토리>
