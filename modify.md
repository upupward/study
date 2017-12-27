* 更新上传视频时候出错，uploadTask not file
    解决：(imgVideosi.indexOf('http://tmp') == -1将网络地址用continue剔除)
* continue  中断循环中的迭代，如果出现了指定的条件，然后继续循环中的下一个迭代。
