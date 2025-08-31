# TODO App (Django)

این یک پروژه TODO ساده با جنگو میباشد که میتوان کارها را اضافه، ویرایش و حذف کرد.  
امکانات:
- ثبت‌نام، ورود و خروج کاربر
- لیست کردن کارها
- اضافه کردن کار جدید
- ویرایش و حذف با تایید
- راست‌چین برای فارسی
- قالب آماده با Bootstrap

## نصب و اجرا
1. پروژه را کلون کنید:
git clone https://github.com/USERNAME/TodoProject.git

2. محیط مجازی بسازید و فعال کنید.

3. پکیج‌ها رو نصب کنید: 
pip install -r requirements.txt

4. مایگریشن‌ها را اجرا کنید:
python manage.py migrate

5. یک سوپر یوزر ایجاد کنید:
python manage.py createsuperuser

6. سرور را اجرا کنید:
python manage.py runserver

حال سرور با این آدرس برای شما فعال میباشد:
http://localhost:8000