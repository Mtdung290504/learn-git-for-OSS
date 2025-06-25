- Xem DS nhánh: `git branch`
- Xem nhánh đang ở: `git branch --show-current`

- Tạo nhánh: `git branch <name>`
- Chuyển sang nhánh khác: `git checkout <name>`
- Tạo & chuyển qua: `git checkout -b <name>`
- Xóa nhánh: `git branch -d <name>`

- Đổi tên nhánh đang ở và ghi đè nếu tên đã tồn tại: `git branch -M <new-name>`
    - `-M` là viết tắt của `--move --force`
        - -> `git branch -m <old> <new>`: đổi tên nhánh `<old>` thành `<new>`, báo lỗi nếu có nhánh tên `<new>` đã tồn tại.
        - -> `git branch -M <old> <new>`: như trên nhưng thay vì báo lỗi thì ghi đè
