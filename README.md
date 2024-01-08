GitHub上传项目方法

使用ssh代理
eval "$(ssh-agent -s)"

添加密钥
ssh-add

克隆项目，例如
git clone https://github.com/39998/book.git

在进入项目目录
cd book

在添加上传的文件
git add * 

提交备注
git commit  -m  "提交信息"

设置 Git 仓库的远程仓库地址
git remote set-url origin git@github.com:39998/set.git

上传项目
git push -u origin main
