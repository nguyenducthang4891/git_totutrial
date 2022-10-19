1. Tạo git local

    mkdir git_toturial
    cd git_toturial
    git init
    touch info.txt
    echo "Hello" > info.txt
    git diff   # xem sự thay đoeoỉ file



2. Tạo 1 repo trên github

    git --global user.email nguyenducthang4891@gmail.com
    git --global user.username nguyenducthang4891

    git remote add orifin url_git_remote

    git push origin master

3. Tạo first_branch 

    git branch first
    git checkout first

    touch first.txt
    git add .
    git commit -m "add first branch file"
    gish push

    