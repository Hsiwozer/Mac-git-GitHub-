# 解决 github 文件夹有向右的白色箭头并且不能打开的解决办法 

### ❓问题描述：

###### 若使用 Git 上传项目至 GitHub 后发现如下图标，则表示为子模块，无法打开该文件夹。

![image-20220906192917648](/Users/hsiwozer/Library/Application Support/typora-user-images/image-20220906192917648.png)

### ❗️解决方法：

1. #### 删除子文件夹中的 .git 文件。注意：.git 文件为隐藏文件。

2. #### 依次执行一下命令

   ```bash
   git rm --cached 文件夹名
   git add \*
   git commit -m "commit msg"
   git push origin main
   ```

   

3. #### 刷新 GitHub，上传完成 ✅