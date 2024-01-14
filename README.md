# 創建虛擬環境
    1.python -m venv venv
    
    以下是如何進到 虛擬環境
    2.venv\Scripts\activate (這是windows)
    3.source venv/bin/activate (這是macOS/Linux)


# 進到虛擬環境到testcases執行套件安裝
    1.執行 pip install -r requirements.txt


# 以下是本地須執行指令
資料庫遷移
python manage.py migrate

後台創建django管理員介面
python manage.py createsuperuser

啟動本地伺服器
python manage.py runserver
