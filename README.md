# 网易云音乐 Discord Rich Presence (RPC)

## 介绍 About

由HackerRouter魔改的版本，支持显示歌曲封面、歌曲链接、听歌软件，在暂停时会显示Paused并隐藏歌曲

更改了数据刷新频率，使其贴合discord的刷新频率限制

支持播客里的歌曲显示

支持同步歌曲，歌手和目前歌曲的播放时长。歌曲的总时长暂不支持显示。

Supports synchronizing song, artist and current song's playing time. Total duration of the song is not supported yet.

纯Python写成，支持最新版网易云音乐，目前只支持Windows客户端。

Written in pure Python, supports latest version of NetEase Cloud Music. Currently only supports the Windows client.

目前只支持网易云音乐2.10.6 build 200601，还会继续支持未来的新版本。

Currently ONLY supports NetEase Cloudmusic Windows 2.10.6 build 200601. Support for future versions will be added once they are released.

旧版本(2.10.2及以下)可以使用这个项目：https://github.com/Kxnrl/NetEase-Cloud-Music-DiscordRPC

For older versions (2.10.2 and below), you can checkout this project: https://github.com/Kxnrl/NetEase-Cloud-Music-DiscordRPC

效果图 / Demo

![demo](demo.png)
![Modified Demo1](demoNew1.png)
![Modified Demo2](demoNew2.png)

## 使用方法 Usage
运行main.py

# 构建 Building
你需要 / You need:
- Python 3.6+
- `pip install -r requirements.txt`

运行build.txt里面的命令即可。

Run the commands in build.txt.

Inspired by https://github.com/Kxnrl/NetEase-Cloud-Music-DiscordRPC
