# NeteaseCloudMusic-Download

免费下载网易云歌单里所有收费的会员歌曲，并且保存到网易云上

>仅供交流，严禁用于其他用途，产生后果自负

编译好的可执行程序下载地址：https://github.com/hongfeiyucode/NeteaseCloudMusic-Download/releases/tag/1.0


当然你也可以用python运行程序


最简单的如果你是windows系统，直接运行cmd命令，详见第三步


## 第一步

清空缓存目录

![Alt text](https://github.com/hongfeiyucode/NeteaseCloudMusic-Download/blob/master/1488671642143.png)

## 第二步

一次性把要下载的会员歌曲逐个听一遍，不必听完每首歌，但必须缓存完毕
![Alt text](https://github.com/hongfeiyucode/NeteaseCloudMusic-Download/blob/master/1488671711149.png)

## 第三步
### 方法一
复制第一步中的缓存位置，比如我的是`‪f:/Music/Cache`  ，注意这一步不能输错，就按网易云程序上的缓存目录输入即可
彻底退出网易云音乐

运行`NeteaseCloudMusic-Download.py`
### 方法二
打开缓存目录，里面有一个cache文件夹，里面有很多杂乱的文件，在进入后按住shift再右键


选择


`在此打开命令窗口`

输入
`ren *.uc *.mp3`

### 方法三

```
pip3 install you-get
you-get http://...
```

## 第四步

文件已经全部下载在缓存目录，用云盘上传所有mp3即可，文件名会自动转换不用管

>PS:因为你上传的文件在缓存目录里。如果清空缓存目录，再下载一次云盘里的歌曲即可
