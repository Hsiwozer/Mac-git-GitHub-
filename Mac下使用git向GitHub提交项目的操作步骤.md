# Mac下使用git向GitHub提交项目的操作步骤

1. 在GitHub上新建仓库

2. **第一次**使用git，需要配置好全局选项

   ```git
   git config --global user.name "用户名"
   git config --global user.email "邮箱"
   ```

3. 在终端使用cd命令进入项目目录

4. 初始化仓库

   ```git
   git init
   ```

5. 将项目文件添加至本地仓库

   ```git
   git add \*
   ```

6. 将项目文件提交至本地仓库

   ```git
   git commit -m "提交信息"
   ```

7. 添加远程库

   ```git
   git remote add origin 仓库地址（SSH）
   ```

8. 把本地库的所有内容推送到远程库上

   ```git
   git push -u origin master
   ```

9. 刷新GitHub，提交成功