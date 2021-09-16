# Intro

### Command line instructions

You can also upload existing files from your computer using the instructions below.

**Git global setup**

```text
git config --global user.name "반재선 (IT BDO Group)"
git config --global user.email "jaesun.ban@kt.com"
```

**Create a new repository**

```text
git clone https://gitlab.dspace.kt.co.kr/AIBOT20/aibot20-sm.git
cd aibot20-sm
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
```

**Push an existing folder**

```text
cd existing_folder
git init
git remote add origin https://gitlab.dspace.kt.co.kr/AIBOT20/aibot20-sm.git
git add .
git commit -m "Initial commit"
git push -u origin master
```

**Push an existing Git repository**

```text
cd existing_repo
git remote rename origin old-origin
git remote add origin https://gitlab.dspace.kt.co.kr/AIBOT20/aibot20-sm.git
git push -u origin --all
git push -u origin --tags
```

