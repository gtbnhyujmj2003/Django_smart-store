# Django_smart-store
利用Django開發點數制商城

# Django Mall MVP - For Learning and Portfolio

這是一個以 Django 製作的最小商城系統，用於學習與展示用途。

## ✅ 功能
- 使用者註冊 / 登入 / 登出
- 點數儲值（假資料模擬）
- 商品列表 + 圖片 + 描述
- 點數購買商品（含交易紀錄）
- 個人頁面顯示餘額與購買紀錄
- Django Admin 後台管理商品與交易

## 🔧 技術
- Django 4+
- SQLite (可換成 PostgreSQL)
- Bootstrap for simple layout
- 支援圖片上傳與 CSRF 安全機制

## 🧪 本地啟動方法
```bash
git clone ...
cd myshop-mvp
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

