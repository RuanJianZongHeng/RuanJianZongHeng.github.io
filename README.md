# RJZH-wiki

使用 [MkDocs](https://www.mkdocs.org/) 搭建

主题使用 [squidfunk/mkdocs-material: Documentation that simply works (github.com)](https://github.com/squidfunk/mkdocs-material)

有关参与方式以及格式的规范文档目前还未完成，目前可以随意一些，简单参考 [如何参与 - OI Wiki](https://oi-wiki.org/intro/htc/)
和 [格式手册](https://oi-wiki.org/intro/format/)

本项目使用 pipenv 管理依赖，需要 python3.11+：

```shell
pip install pipenv
pipenv install
```

本地服务器：

```shell
pipenv run mkdocs serve
```

构建：

```shell
pipenv run mkdocs build
```
