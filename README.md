# 一、项目准备篇
================================================================
## 1、更改本地前端启动端口号
   -  将 package.json 中的 scripts 中的 dev 由 vite 改为 `vite --port 2023`
   `"scripts": {`
      `"dev": "vite --port 2023",`
      `"build": "vue-tsc && vite build",`
      `"preview": "vite preview"`
   `},`
----------------------------------------------------------------
## 2、git 篇
### - 将本地代码仓库绑定远程代码仓库
### - git 指令篇 [git 指令练习](https://learngitbranching.js.org/?locale=zh_CN)
      - git reset --  
      - git branch  查看本地代码分支
      - git checkout ***  && git chekout -b ***  切换当前分支（第二种用于切换并且创建，适用于本地没有目标分支的情况）
      - git log   查看当前分支下代码提交记录
      - git merge ***   将 *** 分支合并过来
      - git status   查看本地代码状态（是否发生改变，哪些文件发生了改变）
      - git add .   添加代码
      - git commit -m '**'    提交本地代码到本地仓库（用于 git add . 后的操作）
      - git push && git push -u origin ***   提交本地代码到远程仓库（第一种远程已有该分支。第二种远程没有该分支，该分支第一次提交）
      - git pull && git pull origin ***  拉取远程分支 （等同于 git fetch + git merge）
      - git stash   暂存本地分支