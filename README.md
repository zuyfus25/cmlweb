git init __ bien du an thanh repo
git status __ check trang thai cua repo
git add __ cbi luu lai repo 
git add .  __ cbi luu lai tat ca file
git reset __ huy cbi luu
git commit -m ''  __ luu lai 1 thoi diem tren repo
(initial commit, second commit)
git log __ xem thoi diem da luu
git log --oneline __
git checkout {branch name} __ xem code
git branch __ xem branch hien co
git checkout -b {branch name} __ tao branch moi
git merge {branch name}
git branch -d {branch name} __ xoa branch

//day code tu may len github
tao repo tren github
lay link
git push {link} {branch name} __day repo local len remote 
git remote add {name alias} {link} __tao alias cho dg dan
                origin
git push {name alias} {branch name}

//day branch moi len github
git push -u {name alias} {branch name} __ 1 lan
git push __sau nay

//lay code tu github ve may 
cop link
terminal: cd {link folder}
git clone {link}
ls __check cac file trong folder
cd {ten file} __lay dg dan vao file
code . __mo code
Luu y: k can tao alias --> git push __cap nhat code len github

//lay branch tu github ve may
tao branch
git checkout master __quay ve master branch
git fetch origin
          {name alias}
git checkout -b {branch name} origin/{branch name}

//sau khi merge
git checkout master __quay ve master branch
git pull







