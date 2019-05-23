### 一、安装django reset framework框架
```python
# 安装django及依赖
pip install django
pip install djangorestframework
pip install markdown
pip install django-filter
```
### 二、开始项目
#### 1、创建项目
```python
# 创建django项目
django-admin startproject tutorial
cd tutorial
django-admin startapp start
```
#### 2、同步数据库
```python
python manage.py migrate
```
#### 3、创建超级用户
```python
python manage.py createsuperuser --email plyx_46204@126.comm --username admin
```
#### 4、启动
```python
python manage.py runserver
```