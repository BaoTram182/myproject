#  Task API Project

##  Mô tả
Dự án Django REST Framework dùng để quản lý Task.



##  Cài đặt

### 1. Tạo môi trường ảo
python -m venv venv

### 2. Kích hoạt môi trường

Windows:
venv\Scripts\activate

Mac/Linux:
source venv/bin/activate



### 3. Cài thư viện
pip install -r requirements.txt



### 4. Chạy migrate
python manage.py migrate



### 5. Tạo admin
python manage.py createsuperuser



### 6. Chạy server
python manage.py runserver



## 🌐 API

- Danh sách task:
http://127.0.0.1:8000/api/tasks/

- Swagger:
http://127.0.0.1:8000/swagger/