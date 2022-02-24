##Setup guide
1. host is ubuntu 20.04 
2. install hugo
   > sudo apt-get install hugo
3. create new site
   > hugo new site hkmeta-news
   > cd hktmeta-news
   > git init
4. add diary theme
5. > git submodule add https://github.com/AmazingRise/hugo-theme-diary.git themes/diary
6. update config.toml from https://github.com/AmazingRise/hugo-theme-diary/blob/1.2.1/exampleSite/config.toml
7. add content
   >hugo new 20220131/news1.md
8. edit news1.md 
9.  start hugo server
    >hugo server -D
10. git related commands
    1.  clone this repository
        > git clone https://github.com/raymondyiu/hkmeta-news.git
    2.  check status
        > git status
    3.  update 
        > git add .
    4.  commit
        > git commit -m "update README.md"
    5.  branch if need
        > git branch -M newbranch
    6.  push to update github
        > git push origin main

- [x] desc1
- [ ] desc2

| check box | Description |
| ----------- | ----------- |
| - [x]  | setup beta |
| - [] | create a new branch |
