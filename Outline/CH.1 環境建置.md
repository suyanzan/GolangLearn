# 環境安裝
* 使用Virtual Box 6.1
* OS 如下圖
* Go Version 如下圖
* 指令:
``` linux command
lsb_release -a
```
![GITHUB](https://github.com/suyanzan/GolangLearn/blob/main/Img/6.jpg)
* 其中lsb指令表示(Linux Standard Base):
* 是一個在Linux基金會結構下對Linux發行版的聯合項目，其目標使Linux作業系統符合軟體系統架構(Reference Wiki)
* 指令共享資料夾 mount(掛載) -t vboxsf $local資料夾 $vm共享資料夾:
``` linux command
sudo mount -t vboxsf Golang /home/suyanzan/Desktop/Window_Goling
```
* 共享資料夾可參考此連結
[VirtualBox與Windows共享資料夾](https://blog.xuite.net/yh96301/blog/76237032# "Title")
