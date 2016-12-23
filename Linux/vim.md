# 解决中文乱码
/etc/vimrc中添加set fencs=utf-8,GB18030,ucs-bom,default,latin1
# 添加行号
/etc/vimrc中添加set number
# 复制多行
* 光标移动到起始位置按v
* 光标移动到结束位置按y
* 光标移动到要复制的位置按p
# 复制一行
yy复制，p粘贴
# 删除一行
dd
# 撤销操作
u
# 恢复上一步被撤销的操作
ctrl+r
# 查找字符串
* /
* n 匹配下一个
* N 匹配上一个
# 替换字符串
* :%s/A/B/g
# 软连接
ln -s A B