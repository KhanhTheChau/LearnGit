

## I. Các lệnh git thông dụng:
### 1. Clone một repository từ xa:
```bash
git clone <URL>
```
### 2. Kiểm tra trạng thái của repository::
```bash
git status
```
### 3. Thêm file:
Thêm file vào staging area:
```bash
git add <tên_file>
```
hoặc để thêm tất cả các file:
```bash
git add .
```
### 4. Commit các thay đổi::
```bash
git commit -m "Thông điệp commit"
```
### 5. Kéo các thay đổi từ repository từ xa về:
```bash
git pull
```
### 6. Tạo một nhánh mới:
```bash
git checkout -b <tên_nhánh>
```
### 7. Gộp nhánh (merge):
```bash
git merge <tên_nhánh>
```
### 8. Chuyển nhánh:
```bash
git checkout <tên_nhánh>
```



## II. Các lệnh git khác:
### 1. Xóa nhánh:
```bash
git branch -d <tên_nhánh>
```
### 2. Xem các nhánh hiện có:
```bash
git branch
```
### 3. Đổi tên file:
```bash
git mv <tên_file_cũ> <tên_file_mới>
```
### 4. Đẩy các commit lên repository từ xa:
```bash
git push origin <nhánh>
```
### 5. Xem lịch sử commit:
```bash
git log
```