# GitProject
# GitProject

Bài tập thực hành sử dụng Git và GitHub - khóa học CodeGym.

## Thành phần dự án
- `README.md`: Giới thiệu dự án
- `source/index.html`: Trang chủ
- `source/news.html`: Trang tin tức
- <!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Index Page</title>
</head>
<body>
    <h1>Welcome to Index Page</h1>
</body>
</html>
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>News Page</title>
</head>
<body>
    <h1>Welcome to News Page</h1>
</body>
</html>

# 1. Khởi tạo và cấu hình (nếu chưa cấu hình)
git config --global user.name "Tên Của Bạn"
git config --global user.email "email@example.com"

# 2. Đẩy file README.md lên
git add README.md
git commit -m "Add README.md"
git push origin main

# 3. Đẩy thư mục source lên
git add source/
git commit -m "Add source files"
git push origin main
