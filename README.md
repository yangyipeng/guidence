# guidence
查看git版本
git --version


配置SSH
ssh-keygen -t rsa -C "youremail@example.com"


查看本机SSH
cat ~/.ssh/id_rsa.pub


验证是否联通
ssh -T git@github.com


配置本地git信息
git config --global user.name "Your Name"  

git config --global user.email "youremail@domain.com"  


初始化本地库
git init


第一次同步时，把github上的文件先pull到本地
git pull origin master


添加所有文件
git add .


提交到本地库
git commit -m "提交内容说明"


提交到远程库
git push -u origin maste
第一次是这个，之后git push origin master
