# Cocos-Creator插件小王子官方文档
## 本地开发编写
1. 首先需要安装python环境,版本2.7
2. 安装mkdocs模块: **pip install mkdocs**
3. 新建一个文档工程:  **mkdocs new mydoc**
4. 启动server预览:**mkdocs serve**  
此命令会构建一个本地server,浏览器打开[http://127.0.0.1:8000/](http://127.0.0.1:8000/)即可预览访问文档

## 部署命令
```txt
mkdocs gh-deploy
```
- 该命令会将文档生成到site目录,并自动上传到gh-pages分支,理论上是不能手动修改该分支的

- 详细的说明见[MKDoc官方部署文档](https://www.mkdocs.org/user-guide/deploying-your-docs/)


## 说明
因为技术栈使用的是python,所以,不是太喜欢,最终决定采用和cocos creator官方一致的gitbook来编写文档