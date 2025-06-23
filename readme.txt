git is a distributed version control system.
git is free software distributed under the GPL.
git init            to create an resposity
git add             to add the change    
git status          
git diff            check the change 
git commit          to store the change 
git log         check emmit history
git reflog      check order history
git reset --hard commit_id      back to commit_id version
the version HEAD point to is now version,therefore ,git allow us to go 
from older to new version.
git push origin master
我现在想试试中文能不能保存进入git中

git remote -v
查看远程库信息
git remote rm origin
此处的“删除”其实是解除了本地和远程的绑定关系，并不是物理上删除了远程库。
远程库本身并没有任何改动。
要真正删除远程库，需要登录到GitHub，在后台页面找到删除按钮再删除。
