JIKEFM - 即刻电台📻
---
[![Build Status](https://travis-ci.com/0neSe7en/jikefm.svg?branch=master)](https://travis-ci.com/0neSe7en/jikefm)

![即刻电台](https://raw.githubusercontent.com/0nese7en/jikefm/master/dist/example.gif)

## Feature

- 查看即友对推荐歌曲的介绍
- 依次播放即友推荐歌曲
- 动态加载更多
- 支持晚安电台、早安歌曲、即友在听什么歌

## Dependencies

Linux 系统需要依赖 libasound2-dev，安装方法：

`sudo apt-get install libasound2-dev`

- [beep](https://github.com/faiface/beep)
- [tview](https://github.com/rivo/tview)
- [tview](https://github.com/gdamore/tcell)
- [qrterminal](https://github.com/mdp/qrterminal)

## Install

`go get -u github.com/0nese7en/jikefm`

## TODO

- [x] 扫码登录(不登录无法获取超过一页的歌曲)
- [x] 支持动态添加更多音乐
- [ ] 支持广场动态
- [x] 支持更多的Topic
- [x] 优化UI
- [ ] 支持除网易云音乐以外的更多歌曲

---

受 https://github.com/findingsea/jikeme 启发

