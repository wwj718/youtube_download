#youtube tools
在本地控制国外服务器下载youtube视频，为非技术人员准备

#Install 
```bash
pip install fabric
git clone https://github.com/wwj718/youtube_download.git
cd youtube_download
```

#setting
在settings.py里填写服务器的账户和密码

#Usage
###查看所有可用指令
`fab -f youtube.py -l`


###安装youtube
`fab -f youtube.py install`

###开始下载
`fab -f youtube.py start_download`

###拉到本地
`fab -f youtube.py pull`

#Todo
使用图形化的界面：[Gooey](https://github.com/chriskiehl/Gooey)

