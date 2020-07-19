# MiraiGo
qq-android协议的golang实现 移植于Mirai

# 警告
本项目目前还处于功能填充阶段，将来API和项目结构可能会有调整，目前不推荐使用。

# 已完成功能/开发计划
#### 登录
- [x] 账号密码登录
- [x] 验证码提交
- [x] 设备锁验证
- [x] 错误信息解析

#### 消息类型
- [x] 文本
- [x] 图片
- [x] 表情
- [x] At
- [x] 回复
- [ ] 长消息
- [ ] 分享
- [ ] 富文本
- [ ] 转发

#### 事件
- [x] 好友消息
- [x] 群消息
- [x] 临时会话消息
- [ ] 讨论组消息
- [x] 登录号加群
- [x] 登录号退群(包含T出)
- [x] 新成员进群/退群
- [x] 群消息撤回 
- [x] 群禁言
- [x] 群成员权限变更
- [x] 收到邀请进群通知
- [x] 收到其他用户进群请求
- [ ] 新好友
- [x] 新好友请求
- [ ] 客户端离线

#### 主动操作
- [x] 发送群消息
- [x] 发送好友消息
- [ ] 发送临时会话消息
- [ ] 发送讨论组消息
- [x] 获取/刷新群列表
- [x] 获取/刷新群成员列表
- [x] 获取/刷新好友列表
- [ ] 获取/刷新讨论组列表
- [x] 处理加群请求
- [x] 处理被邀请加群请求
- [x] 处理好友请求
- [x] 撤回群消息
- [ ] 群公告设置
- [ ] 群设置
- [ ] 修改群成员Card
- [ ] 群成员邀请
- [ ] T出群成员
