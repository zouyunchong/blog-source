日常维护

1.环境准备：在新电脑安装 Git, Node.js, 并配置好 SSH Key。

2.克隆源码：
git clone git@github.com:zouyunchong/blog-source.git my-blog
cd my-blog

3.恢复依赖（不需要重新 hexo init）：
git remote add origin git@github.com:zouyunchong/blog-source.git
git branch -M main
git push -u origin main


日常维护

1.写文章、改代码：在本地修改。
2.发布网站
hexo g -d

3. 备份源码（养成习惯，写完就推）：
git add .
git commit -m "Update blog post"
git push



