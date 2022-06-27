# github博客搭建1
## 访问地址
- https://github.com/

## 注册登录
> 略

## 开始搭建博客

1. 先创建一个Repositories

![](https://youyongba.oss-cn-beijing.aliyuncs.com/图片/WX20220623-103507%402x.png?versionId=CAEQHhiBgIDY1tO5jBgiIGQyMmI4NGZiYjQ0ZjQ2NjI4NTNmOTU5OWVhY2Q0OTli '微信扫码交流')


2. 然后给自己的Repositories取一个名字，注意：名称格式最好为：用户名.github.io

![](https://youyongba.oss-cn-beijing.aliyuncs.com/图片/2.png?versionId=CAEQHhiBgMDI0Ye6jBgiIGViNzUxM2RiMDdiMjRjMTE5ODAzN2E5YjgxNmYyYTI5 '创建Repositories')

3. 创建内容


![](https://youyongba.oss-cn-beijing.aliyuncs.com/图片/3.png?versionId=CAEQHhiBgICz25K6jBgiIDhjZjY0MWFkZGYzNjQzNTZiOTA0ZDJlODZmNWU2MWQ0 '创建内容')


```bash
echo "# youyongba.github.io" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/youyongba/youyongba.github.io.git
git push -u origin main
```
