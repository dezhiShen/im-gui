**因为 go-sciter的 bug [issues#297](https://github.com/sciter-sdk/go-sciter/issues/297) 暂未修复,无法继续开发,所以暂停本项目,使用 pyqt5重新开发**
**新项目在 [dezhiShen/im-gui-pyqt5](https://github.com/dezhiShen/im-gui-pyqt5)

# im-gui
即时通讯界面

本项目意在完成一个包含基本功能的即时通讯的客户端,
只提供基本的聊天功能界面,不提供任何的服务端交互实现,
只提供接口和启动入口,需要自行实现自己的服务端协议

* 使用[go-sciter](https://github.com/sciter-sdk/go-sciter)
* 提供接口

## 功能
* [ ] 启动入口
* [ ] 登录接口
* [ ] 下线接口
* [ ] 展示会话列表
    * [ ] 刷新好友/群组列表
    * [ ] 会话列表页
    * [ ] 移除会话列表
* [ ] 消息管理
    * [ ] 持久化存储
    * [ ] 删除
    * [ ] 从远端加载
* [ ] 发送消息
* [ ] 接收消息
* [ ] 界面拓展接口
