- git add `file`: Thêm `file` vào staging, rồi tạo commit đầu tiên chứa nó.
    - Ví dụ, sau khi `git add .\README.md`, xem status sẽ hiện:
        ```
            git status
            On branch master

            No commits yet

            Changes to be committed:
            (use "git rm --cached <file>..." to unstage)
                    new file:   README.md

            Untracked files:
            (use "git add <file>..." to include in what will be committed)
                    commands.md
        ```

- git rm --cached `file`: unstage file
    