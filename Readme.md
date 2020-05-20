# Prototype_frontend
###### tags: `RN`

## 注意事項
1. <font color="red">**切記勿將機密資料提交到git repo紀錄裡
可在.gitignore新增機密資料的檔名，以避免在commit時提交credential**</font>
2. <font color="red">**不要在這個hackmd文件寫任何機密**</font>
### branch分配

|   Name   | Branch name |
|:--------:|:-----------:|
|   Bob    |    schua    |
|  yojin   |    yojin    |
|  caicai  |     cai     |
| michelle |  michelle   |
|  bobolu  |    bobo     |

### 開始coding前
將branch切回master
```bash=
git checkout master
```
如果你的branch存在且你branch裡的code都已經push了，那就刪除你的branch(以schua舉例)
```bash=
git branch -d schua
```
pull遠端的資料
```bash=
git pull
```
創你的branch並切到你的branch(以schua舉例)
```bash=
git checkout -b schua
```
下載別人裝的nodejs套件
```bash=
npm i
```
### code到一個段落後
追蹤所有檔案
```bash=
git add .
```
commit
```bash=
git commit -m "你剛剛做了甚麼"
```
### 覺得可以push了
在你的branch
```bash=
git push
```
### Push後的Merge與Conflict
> <font color="black">大家都可以做merge的動作，如果沒有conflict那就太棒了
> 但如果不幸有conflict也沒關係，可以嘗試自己修修看
> 如果要修的code不是自己的，問寫的人要怎麼修</font>
> [color=#ccaf10]


