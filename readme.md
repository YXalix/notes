# program learn
* Git op

    1. ```git init ```
       > 初始化git本地数据库
    2. ```git status```
       > 确认工作树和索引的状态
    3. ```git add <file>..```
       > 将文件加到索引、tips：git add . 可添加所有
    4. ```git commit -m "" ```
       > 提交文件
    5. ```git log ```
       > 查看提交记录
    6. ```git remote add <name> <url> ```
       > 添加远程数据库，name 一般默认 origin
    7. ```git push <repository> <refspec>...```
       > 推送更改内容，like ```git push -u origin master```
    8. ```git clone <repository> <directory>```
       > 复制数据库
    9. ```git pull <repository> <refspec>...```
       > 拉去远程数据库的内容
    10. > 自动修正冲突、手动修正冲突：先拉取，修改后提交
    11. ```git branch <branchname>```
       > 创建分支
    12. ```git checkout <branchname>
       > 切换分支