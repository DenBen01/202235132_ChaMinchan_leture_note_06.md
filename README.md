# 202235132_ChaMinChan_lecture_note_6.md
-------------------------------------------
- **git --version**  
: 버전확인  
- **git config --system option**  
: 제일 상위 단계 /시스템관리권한필요.  
- **git config --global option**  
: 글로벌 단계or유저 단계 / 현재유저의 모든레파지토리에 적용(가장많이쓸것)   
- **git config --local option**  
: 제일 하위 단계  
- **git config --list --show-origin**    
: 어떤 레벨에서 설정되어있는지 확인가능
--------------------------------------------
- **git status**   
: 어디에 어떻게 저장돼있는지 및 Untracked files 확인가능  
- **git add [file_name]**    
: Untracked files 내역의 파일 추가가능  
> git add 이후 파일 변동 내역이 있을땐, 다시 git add 해주는것이 좋다.   
- **git add .**  
: Untracked files인 모든 파일을 add  
- **git rm --cached [file_name]**   
: 특정 Commited file을 Untracted로 변경
----------------------------------------------
## Ignoring a file  
![이그노어](https://user-images.githubusercontent.com/113030260/195088524-58a87d4f-8037-4df9-975e-4e96eda028c0.PNG)
---------------------------------------------------------
- **git commit -m "commit messege"**  
: 작업한 파일들을 스냅샷 ( 특정버전으로 기록가능 )  
- **git log**  
: 지금까지의 commit을 한 내역 확인가능
