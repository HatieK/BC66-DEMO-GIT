git: version control system ==> phần mềm quản lý code
github:nơi lưu trữ code online (driver, icloud)


* Repository: folder tương tác với git

* Repo local: folder chứa source code trên laptop
* Repo remote: project trên github
* Branch: tạo nhánh mới khi cần fix bug / feature

đẩy code từ máy lên github ==> push
lấy code mới nhất từ github về máy ==> pull
khi mới join vào dự án và chưa có source ==> clone

<!-- KHỞI TẠO DỰ ÁN -->
1.git init
2.git remote add origin + link

<!-- ĐẨY CODE TỪ LOCAL LÊN REMOTE -->
<!-- bước cố định  -->
3.git add -A
4.git commit -m "create home.html"
5.git push -u origin master

<!--  -->
Đưa code từ nhánh phụ về nhánh chính
git merge name(tên nhánh phụ)

