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
5.git push -u origin master (lần đầu, lần 2 trở đi chỉ có git push)

<!-- GIT ALIAS -->
<!-- TẠO NHÁNH -->
*******Commit trước khi chuyển nhánh************

// tạo nhánh khi code chức năng mới hoặc fix bug thì mới tạo nhánh

git checkout -b name

**********chuyển nhánh:git checkout name********



