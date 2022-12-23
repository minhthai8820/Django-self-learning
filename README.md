# Django-self-learning
Học này học kia

## 1 Install and set up
- Dpwnload và Cài đặt Pycharm
- Download python jdk 3.9.x 
- Install python jdk (Lúc install nhớ tick chọn add variable to PATH) > Nếu quên vào PATH để thêm lại
- Kiểm tra xem đã install được chưa bằng `python -V`, `pip -V`


- Cài đặt pipenv
 `pip install pipenv`
- Tiếp tục vào PATH thêm 2 đườnng dẫn sau vào PATH 
 ```
 C:\Users\ocg\AppData\Roaming\Python\Python39\Scripts
 C:\Users\ocg\AppData\Roaming\Python\Python39\Site-Packages
 ```
- Kiểm tra xem đã setup được pipenv được hay chưa : `pipenv -h`
- Run lệnh `pipenv shell` + `pipenv install django` để install các package của django vào 


- Download và install Doker
- Tạo 1 thư mục mới trong ổ D: hoặc j đó
- Tạo mới 1 Database và connect vào DB
  VD: test-huh blablabla
  - Tại DB run các cmd sau:
```
INSERT INTO bgroup_docs.auth_group (id, name) VALUES (1, 'Tester');
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (1, 1, 1);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (2, 1, 2);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (3, 1, 3);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (4, 1, 4);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (5, 1, 5);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (6, 1, 6);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (7, 1, 7);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (8, 1, 8);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (9, 1, 9);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (10, 1, 10);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (11, 1, 11);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (12, 1, 12);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (13, 1, 13);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (14, 1, 14);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (15, 1, 15);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (16, 1, 16);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (17, 1, 17);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (18, 1, 18);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (19, 1, 19);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (20, 1, 20);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (21, 1, 21);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (22, 1, 22);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (23, 1, 23);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (24, 1, 24);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (25, 1, 25);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (26, 1, 26);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (27, 1, 27);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (28, 1, 28);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (29, 1, 29);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (30, 1, 30);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (31, 1, 31);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (32, 1, 32);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (33, 1, 52);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (34, 1, 85);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (35, 1, 86);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (36, 1, 87);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (37, 1, 88);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (39, 1, 90);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (38, 1, 92);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (40, 1, 96);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (41, 1, 100);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (43, 1, 101);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (44, 1, 102);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (45, 1, 103);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (46, 1, 104);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (47, 1, 105);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (48, 1, 106);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (49, 1, 107);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (50, 1, 108);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (51, 1, 110);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (42, 1, 112);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (52, 1, 113);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (53, 1, 114);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (54, 1, 115);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (55, 1, 116);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (56, 1, 117);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (57, 1, 118);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (58, 1, 119);
INSERT INTO bgroup_docs.auth_group_permissions (id, group_id, permission_id) VALUES (59, 1, 120);
```
- Mở terminal: run cmd
  ```docker run -v "${Thư mục đã tạo}/data":/var/lib/mysql --name mysql8 -e MYSQL_ROOT_PASSWORD=root -p {port muốn chạy} -d mysql:latest```
  
  
- Tại project đã tạo > Terminal: run
  ```
  python manage.py migrate
  python manage.py runserver
  ```
- Có thể thay port bằng cách thêm tham số phía sau:
 ```python manage.py runserver http://127.0.0.1:8080```
 
 ## 2 Django admin 
 - Customization
   ```
   admin.site.index_title = "The Bookstore" # thay đổi ở title trên title tag
   admin.site.site_header = "The Bookstore Admin" # thay đổi ở Title tag
   admin.site.site_title = "Site Title Bookstore" # thay đổi ở title trên title tag, 
   ```
 ## 3: Setup custom/multiple django admin sites
 - New admin area for the blog
 - Trong blog/admin.py, tạo class BlogAdminArea
 ```python
 from django.contrib import admin
 class BlogAdminArea(admin.AdminSite):
     site_header = "Blog Admin Area"
 blog_site = BlogAdminArea(name="Blog Admin")
 ```
 - Trong core/urls.py, import admin site
 ```python
 from blog.admin import blog_site
 ```
 - Thay chỗ url pattern
 ```python
 urlpatterns = [
     path('admin/', blog_site.urls),
 ]
 ```
 - Ra refresh -> thấy thay đổi là vào link admin/ sẽ hiển thị blog site admin. Tuy nhiên chưa có dữ liệu do chưa có gì cả.

 - Thêm model Post:
 - Vào trong blog/models.py
 ```python
 class Post(models.Model):

     title = models.CharField(max_length=100)
     def __str__(self):
         return self.title
 ```
 - Vào trong admin.py, thêm vào dòng sau:
 ```python
 from . import models
 # old codes...
 blog_site.register(models.Post)
 ```
 - Thay url vào admin: sửa trong core/urls.py là xong
 ```python
 urlpatterns = [
     path('blogadmin/', blog_site.urls),
 ]
 ```
 - Để chạy được code thì phải tạo migration và run:
 ```
 python3.9 manage.py makemigrations
 python3.9 manage.py migrate
 ```

 - Có thể dùng cả 2 cháu: admin và blog admin
 ```python
 urlpatterns = [
     path('admin/', admin.site.urls),
     path('blogadmin/', blog_site.urls),
 ]
 ```
 - Có thể register model Post vào admin site: ở blog/admin.py, thêm dòng sau:
```python
admin.site.register(models.Post)
```
### Overriding the default admin site
- Mặc định thì nó load admin trong thằng core.
- Có thể thay đổi mặc định bằng cách như sau:
  - Sửa file blog/apps, thêm class BlogAdminConfig
  - Sửa file core/settings.py, sử dụng BlogAdminConfig vừa tạo trong mục INSTALLED_APPS
  
```python
# blog/apps.py
from django.contrib.admin.apps import AdminConfig
class BlogAdminConfig(AdminConfig):
    default_site = "blog.admin.BlogAdminArea"
## core/settings.py
INSTALLED_APPS = [
    'django.contrib.admin'
# ...
```
## 4. Django tutorial 
https://docs.djangoproject.com/en/4.1/intro/tutorial01/
### Start new project
```django-admin startproject mysite``` > Tránh sử dụng name như django hoặc test vì sẽ bị conflic với django
Project origin structure
```
mysite/
    manage.py
    mysite/
        __init__.py
        settings.py
        urls.py
        asgi.py
        wsgi.py
```
- manage.py > là 1 utility cho phép tương tác với django project 
- __init__.py > là 1 file rỗng
- settings.py > file chứa các setting cho project
- urls.py > file định nghĩa các content cho các link khác nhau 

### Create new app
```
Sự khác biệt giữa một dự án và một ứng dụng là gì? Ứng dụng là ứng dụng web thực hiện điều gì đó – ví dụ: hệ thống blog, cơ sở dữ liệu hồ sơ công khai hoặc ứng dụng thăm dò ý kiến nhỏ. Dự án là tập hợp các cấu hình và ứng dụng cho một trang web cụ thể. Một dự án có thể chứa nhiều ứng dụng. Một ứng dụng có thể nằm trong nhiều dự án.
```
- Start new app 
 ```python manage.py startapp polls```
 - Include function
 ```
 Hàm include() cho phép tham chiếu các URLconf khác. Bất cứ khi nào Django gặp include(), nó sẽ cắt bỏ bất kỳ phần nào của URL khớp với điểm đó và gửi chuỗi còn lại tới URLconf được bao gồm để xử lý thêm.
 => You should always use include() when you include other URL patterns. admin.site.urls is the only exception to this.
 ```
 - Path() arguement: route
    - route là một chuỗi chứa mẫu URL. Khi xử lý một yêu cầu, Django bắt đầu ở mẫu đầu tiên trong các mẫu url và đi xuống danh sách, so sánh URL được yêu cầu với từng mẫu cho đến khi tìm thấy một mẫu phù hợp.
 VD: 
 ```
 https://www.example.com/myapp/, the URLconf will look for myapp/. In a request to https://www.example.com/myapp/?page=3, the URLconf will also look for myapp/.
 ```
 - Path() argument: name
    - Việc đặt tên cho URL của bạn cho phép bạn tham khảo nó một cách rõ ràng từ những nơi khác trong Django, đặc biệt là từ bên trong các mẫu. Tính năng mạnh mẽ này cho phép bạn thực hiện các thay đổi chung đối với các mẫu URL của dự án trong khi chỉ chạm vào một tệp duy nhất.

### Database
- Run cmd dưới khi có các thay đổi về models
```python manage.py makemigrations polls```
- Run cmd dưới để apply những thay đổi vào DB
``` python manage.py migrate```
- The sqlmigrate > biểu diễn lại các dòng lệnh ở file models dưới dạng 
- Sau đó run lại ```python manage.py runserver``` để tạo các table vào trong 

### Playing with API - Hỏi sếp phong để có guide học phần này

### Introducing django admin
- First > Tạo super user để có thể đăng nhập vào admin site
```python manage.py createsuperuser```
- Để apply app đã install (polls app) 
- Register Question vào admin.py 
```
from django.contrib import admin
from .models import Question

admin.site.register(Question)
```
### Writting django app
- Defind các trang view page mới
```
def detail(request, question_id):
    return HttpResponse("You're looking at question %s." % question_id)

def results(request, question_id):
    response = "You're looking at the results of question %s."
    return HttpResponse(response % question_id)

def vote(request, question_id):
    return HttpResponse("You're voting on question %s." % question_id)
```
- Sau đó phải chèn thêm path vào Urls để có thể mở vào page đó
```
    # ex: /polls/
    path('', views.index, name='index'),
    # ex: /polls/5/
    path('<int:question_id>/', views.detail, name='detail'),
    # ex: /polls/5/results/
    path('<int:question_id>/results/', views.results, name='results'),
    # ex: /polls/5/vote/
    path('<int:question_id>/vote/', views.vote, name='vote'),
 ```

