# spring_data
pdf docs

# github   <br />
git init              -->  .git 폴더 생성됨 , git 로컬디렉토리 만듬

git status

git add Readme.txt   --> Readme.txt 저장소 추가 ( git add . => 모든파일 추가)

git commit -m "Add Readme.txt"  --> 커밋 스넵샷 


git remote add origin https://github.com/kysong/spring_data.git

git remote -v

git push             --> 원격저장소로 변경사항 반영  <br />
git push origin master  --> github로 push



D:\git\spring_data [master]> git remote -v  <br />
origin  https://github.com/kysong/spring_data (fetch)  <br />
origin  https://github.com/kysong/spring_data (push)  <br />


D:\git\spring_data [master]> git push origin master  <br />
fatal: unable to access 'https://github.com/kysong/spring_data/': error setting certificate verify locations:  <br />
  CAfile: C:\Users\ESIS_KYSONG\AppData\Local\GitHub\PortableGit_d93ee8917cfa9add  <br />  
886773e6be9ec08609a502b6\mingw32/usr/ssl/certs/ca-bundle.crt  <br />
  CApath: none  <br />

  
D:\git\spring_data [master]>


D:\git\spring_data [master]> git config --global http.sslverify false   <br />
D:\git\spring_data [master]> git push   <br />
Counting objects: 3, done.  <br />
Delta compression using up to 4 threads.  <br />
Compressing objects: 100% (3/3), done.   <br />
Writing objects: 100% (3/3), 1.08 MiB | 118.00 KiB/s, done.  <br />
Total 3 (delta 0), reused 0 (delta 0)  <br />
To https://github.com/kysong/spring_data   <br />
1e3cdab..8fa44df  master -> master  <br />

   
D:\git\spring_data [master]>


