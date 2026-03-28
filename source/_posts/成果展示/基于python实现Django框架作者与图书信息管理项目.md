---
title: 基于Python实现Django框架作者与图书信息管理项目
date: 2026-03-01 10:00:00
tags: Django, Python, 后端开发
description: 基于Django框架实现的作者与图书信息管理系统，包含模型定义、Admin后台管理、图书查询和统计功能
---

# 📌 项目简介

基于 **Django** 框架实现的作者与图书信息管理系统，采用标准的Django项目架构，包含完整的模型定义、Admin后台管理和图书查询统计功能。项目结构清晰，功能完善，适合作为Django入门学习的实践案例。

---

# 🎬 演示地址

**[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**

---

# 📸 成果展示

## 🎬 视频演示



---

## 🖼️ 图片展示

<div align="center">
  <table>
    <tr>
      <td align="center"><img src="/img/works/django/01.png" width="250" style="border-radius:8px;transition:transform 0.3s ease,box-shadow 0.3s ease;" onmouseover="this.style.transform='scale(1.05)';this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'"></td>
      <td align="center"><img src="/img/works/django/02.png" width="250" style="border-radius:8px;transition:transform 0.3s ease,box-shadow 0.3s ease;" onmouseover="this.style.transform='scale(1.05)';this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'"></td>
      <td align="center"><img src="/img/works/django/03.png" width="250" style="border-radius:8px;transition:transform 0.3s ease,box-shadow 0.3s ease;" onmouseover="this.style.transform='scale(1.05)';this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'"></td>
      <td align="center"><img src="/img/works/django/04.png" width="250" style="border-radius:8px;transition:transform 0.3s ease,box-shadow 0.3s ease;" onmouseover="this.style.transform='scale(1.05)';this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'"></td>
    </tr>
  </table>
</div>

---

# ✨ 功能展示

## 🔧 核心功能

| 功能 | 说明 |
|------|------|
| 📚 作者与图书模型 | 定义Author和Book两个核心模型，建立一对多关系 |
| 🔍 Admin后台管理 | 完整的后台管理界面，支持数据的增删改查 |
| 📊 图书查询功能 | 支持查询所有图书、按作者查询图书 |
| 📈 统计分析 | 提供图书总数量、平均页数、最老/最新图书统计 |

---

## 📁 项目结构

**项目架构采用标准Django结构：**

```
webwork/
├── library/                    # 应用目录
│   ├── migrations/            # 数据库迁移文件
│   ├── admin.py               # Admin后台配置
│   ├── models.py              # 模型定义
│   ├── views.py               # 视图函数
│   └── ...
├── library_project/           # 项目配置目录
│   ├── settings.py            # 项目设置
│   └── urls.py                # URL配置
├── manage.py                  # Django管理脚本
├── db.sqlite3                 # 数据库文件
└── 任务.txt                   # 任务要求文档
```

---

## 🛠️ 技术实现

### 模型定义

**Author模型：**
- name：作者姓名
- birth_year：出生年份
- country：国籍

**Book模型：**
- title：图书标题
- author：外键关联Author
- publisher：出版社
- pub_year：出版年份
- pages：页数

### Admin后台配置

**Author后台：**
- 显示字段：id, name, birth_year, country
- 支持按name搜索

**Book后台：**
- 显示字段：id, title, author, publisher, pub_year, pages
- 支持按author、pub_year筛选
- 默认按pub_year降序排列

### 视图功能

1. **查询所有图书**：`/books/all/`
2. **按作者姓名查询图书**：`/books/by_author/<str:author_name>/`
3. **图书统计信息**：`/books/stats/`

---

## 🚀 使用方法

### 1. 创建超级用户
```bash
python manage.py createsuperuser
```

### 2. 启动开发服务器
```bash
python manage.py runserver
```

### 3. 访问页面
- **Admin后台**：http://127.0.0.1:8000/admin/
- **查询所有图书**：http://127.0.0.1:8000/books/all/
- **按作者查询**：http://127.0.0.1:8000/books/by_author/张三/
- **图书统计**：http://127.0.0.1:8000/books/stats/

### 4. 添加测试数据
1. 访问Admin后台，先创建作者
2. 然后为作者添加图书
3. 测试数据示例：
   - 张三，出生年份：1980，国籍：中国
   - 李四，出生年份：1985，国籍：中国
   - 图书：Django入门、Python编程、C语言程序设计、Django实战

---

<div align="center">
  <p style="color:#888;font-size:14px;margin-top:30px;">
    使用 Django 框架构建 ❤️
  </p>
</div>