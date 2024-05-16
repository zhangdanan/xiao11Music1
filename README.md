# xiao11Music1

## 基本操作



`Space空格键`：暂停/播放音乐

`上/下方向键`：增加/减少音量

`左/右方向键`：上一曲/下一曲

## 修改歌单/私有部署与配置



### ID 编号



播放列表的id，可以从音乐歌单分享的链接中获取，例如`https://y.qq.com/n/ryqq/playlist/8668419170`中，id为`8668419170`

### Server 服务器



播放列表的服务商，例如`netease`（网易云音乐）,`tencent`（腾讯）,`kugou`（酷狗）,`xiami`（小米音乐）,`baidu`（百度音乐）

### Type(可选）



播放列表的类型，例如`song`（单曲）, `playlist`（歌单，默认）, `album`（专辑）, `search`（搜索结果）, `artist`（歌手）

## 使用URL参数（推荐）



HeoMusic支持URL参数 `https://music.zhheo.com/?id=`+ id +`&server=` + server

例如：

**HeoMusicTop:** https://music.zhheo.com/?id=8668419170&server=tencent
HeoMusicTop：https://music.zhheo.com/?id=8668419170&server=tencent

**鸡你太美:** https://music.zhheo.com/?id=7363728147&server=netease

## 修改HTML的方法（需要自行搭建）



编辑`index.html`的相关代码，填写歌单id和服务商

[![修改id和server](https://github.com/zdnzs11/Xiao11Music/raw/main/img/help.webp)](https://github.com/zdnzs11/Xiao11Music/blob/main/img/help.webp)

直接访问首页`index.html`即可