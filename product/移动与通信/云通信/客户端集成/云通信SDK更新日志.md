#### IM SDK 4.3.81  2019-4-24
**iOS：**
1. 修复草稿箱添加消息元素 Crash 的问题
2. 修复某些账户在 App 卸载重装后拉取不到会话列表的问题
3. 修复在登录的状态下 usersig 过期，不重启 App 的情况下会一直登录失败的问题
4. 修复在登录的状态下 usersig 过期，发消息失败，收不到 usersig 过期回调的问题
5. 修复修复群成员获取数量问题
6. 优化请求超时（错误码6012）问题

**Android：**
- 新增功能：
 补齐老版本 SDK 的好友黑名单功能，好友分组功能，以及加好友请求处理等关系链功能
- 修复问题：
 1.修复一处 App 主进程被杀后的报错问题
 2.修复修复群成员获取数量问题
 3.修复群自定义字段和群成员自定义字段的设置和获取问题
 4.修复获取群信息超时后，没有 onError 回调出去的问题
 5.修复某些账户在 App 卸载重装后拉取不到会话列表的问题
 6.修复在登录的状态下 usersig 过期，不重启 App 的情况下会一直登录失败的问题
 7.修复在登录的状态下 usersig 过期，发消息失败，收不到 usersig 过期回调的问题
 8.修复消息乱序问题
 9.优化请求超时（错误码6012）问题
 10.更新关系链错误码
 11.TUIKit 修复日期工具类出错的严重bug（github issue#75）
 12.TUIKit 修改一处崩溃（github issue#86）
 13.TUIKit 修复无权限时，使用SDK的一些问题
 14.TUIKit 修复删除会话，删除消息，然后长按后的一些崩溃问题
 15.TUIKit 修复 popupwindow 长驻不消失问题
 16.TUIKit 修复消息重复问题
 17.TUIKit 拦截发送空格空消息问题
 18.TUIKit 修复删除会话后，未读消息未更新问题
 19.TUIKit 修复发送消息最大字符限制问题
 20.TUIKit 体验优化和修复若干数组越界问题

**Windows：**
1. 修复部分崩溃问题
2. 优化请求超时（错误码6012）问题
3. 修复某些账户在 App 卸载重装后拉取不到会话列表的问题
4. 修复在登录的状态下 usersig 过期，不重启 App 的情况下会一直登录失败的问题
5. 修复在登录的状态下 usersig 过期，发消息失败，收不到 usersig 过期回调的问题

#### IM SDK 4.2.52  2019-4-17
**iOS：**
- 新增功能：
 补齐老版本 SDK 的好友黑名单功能，好友分组功能，以及加好友请求处理等关系链功能
- 修复问题：
 1.优化 API 接口注释
 2.修复群自定义字段和群成员自定义字段不生效的问题
 3.优化 TIMMessage 获取 senderProfile 拿不到用户资料信息的问题
 4.修复已读回执回调及状态问题
 5.修复同步未读消息最新一条消息不回调问题
 6.修复群消息偶尔收不到问题
 7.修复 login 回包无法解密问题
 8.增加 IP 连接和 login 信息统计上报
 9.修复消息seq错误

**Android：**
- 新增功能：
 补齐老版本 SDK 的好友黑名单功能，好友分组功能，以及加好友请求处理等关系链功能
- 修复问题：
 1.修复 Android 的 jni 泄漏
 2.修复群组成员角色错误问题
 3.修复退群在加群后，群组消息撤回崩溃问题
 4.修复 TUIKit Demo 表情不显示问题
 5.修复群聊会话获取消息，第二页大概率获取重复消息问题
 6.修复 TUIKit Demo 中的部分 Crash 问题
 7.优化 TIMMessage 获取 senderProfile 拿不到用户资料信息的问题
 8.修复已读回执回调及状态问题
 9.修复同步未读消息最新一条消息不回调问题
 10.修复群消息偶尔收不到问题
 11.修复 login 回包无法解密问题
 12.增加 IP 连接和 login 信息统计上报
 13.修复消息 seq 错误

**Windows：**
- 新增功能：
 补齐老版本 SDK 的好友黑名单功能，好友分组功能，以及加好友请求处理等关系链功能
- 修复问题：
 1.优化 TIMMessage 获取 senderProfile 拿不到用户资料信息的问题
 2.修复已读回执回调及状态问题
 3.修复同步未读消息最新一条消息不回调问题
 4.修复群消息偶尔收不到问题
 5.修复 login 回包无法解密问题
 6.增加 IP 连接和 login 信息统计上报
 7.修复消息 seq 错误

#### IM SDK 4.2.28  2019-4-8
**iOS：**
1. 优化未读计数相关的问题
2. 优化消息已读状态的问题
3. 优化 REST API 发的 C2C 消息排序异常的问题
4. 优化获取漫游消息偶现重复的问题
5. 优化 uniqueId 空实现的问题

**Android：**
- 新增功能：
 新增好友增/删/查逻辑
- 修复问题：
 1.优化未读计数相关的问题
 2.优化消息已读状态的问题
 3.优化 REST API 发的 C2C 消息排序异常的问题
 4.优化获取漫游消息偶现重复的问题
 5.优化 uniqueId 空实现的问题

**Windows：**
1. 优化未读计数相关的问题
2. 优化消息已读状态的问题
3. 优化 REST API 发的 C2C 消息排序异常的问题
4. 优化获取漫游消息偶现重复的问题

#### IM SDK 4.2.10  2019-3-29
**iOS：**
- 新增功能：
 新增好友增/删/查逻辑
- 修复问题：
 1.优化超时问题
 2.优化自动登录逻辑
 3.优化 Crash 问题
 4.优化偶现网络连接异常 bug

**Android：**
1. 优化超时问题
2. 优化自动登录逻辑
3. 优化 JNI 泄漏问题
4. 优化 Crash 问题
5. 优化偶现网络连接异常 bug

**Windows：**
1. 优化超时问题
2. 优化 Crash 问题
3. 优化偶现网络连接异常 bug

#### IM SDK 4.2.9  2019-3-27
**iOS & Mac：**
修复 IPv6 环境下 Crash 的问题
修复资料设置整数失败的问题

**Android：**
修复资料设置整数失败的问题

#### IM SDK 4.2.2  2019-3-14
**iOS：**
- 新增功能：
 1.SDK 新增用户资料逻辑
 2.SDK 新增自动登录逻辑
 3.SDK 新增错误码枚举类 TIMErrorCode.h
 4.DEMO 新增推送设置示例代码
- 修复问题：
 1.修复 OfflinePushInfo 设置和获取无效的问题
 2.修复本地消息没有保存 pushinfo 中的 descr 和 ext 字段的问题
 3.修复调用 setAPNS Crash 的问题
 4.修复 TUIKit 偶现 Crash 的问题
 5.修复切换帐号 longloop 偶现异常的问题
 6.修复消息重复检测偶现异常的问题
 
**Android：**
- 新增功能：
 1.SDK 新增用户资料逻辑
 2.SDK 新增自动登录逻辑
- 修复问题：
 1.修复本地消息没有保存 pushinfo 中的 descr 和 ext 字段的问题
 2.修复切换帐号 longloop 偶现异常的问题
 3.修复消息重复检测偶现异常的问题
 4.修复内存泄漏问题

**Windows：**
修复切换帐号 longloop 偶现异常的问题


#### IM SDK 4.2.1  2019-3-14
**iOS：**
1. 优化后台解散群组, 客户端收不到相应指令的问题
2. 修复调用 deleteConversationAndMessage() 无效问题
3. 优化网络重新连接后收不到消息的问题

**Android：**
1. 修复群组获取未决和已决信息返回不正确问题
2. 修复客户端进入后台 Crash 问题
3. 修复优化网络重新连接后收不到消息的问题
4. 修复偶现消息排序错误的问题
5. 修复偶现消息发送失败的问题

**Web：**
新增 Web IM 支持播放 .amr 录音格式的功能

**Windows：**
1. 新增 /source-charset:.65001 编译选项
2. 修复在文件系统直接运行 IMAPP.exe Crash 问题
3. 修复部分编译出错，以及 Crash 问题
4. 移除 X64 编译 (暂不支持)

#### IM SDK 4.0.13  2019-3-12
**iOS：**
1. 新增支持 pod 直接集成 TUIKit.framework
2. 修复从 3.x 升级到 4.x 版本后登录引起 Crash 的问题

**Android：**
修复从 3.x 升级到 4.x 版本后登录引起 Crash 的问题

**Windows：**
1. 新增以 duilib 库为 UI 组件的 IM Demo
2. 新增使用说明及相关集成指引文档


#### IM SDK 4.0.12  2019-3-11
**iOS：**
1. 新增 TUIKit.framework 支持 bitcode 2
2. 修复群组禁言无效问题
3. 修复修改用户群内身份功能

**Android：**
1. 修复群组禁言无效问题
2. 修复修改用户群内身份功能
3. 修复修改群消息接收选项
4. 修复离线推送开关无效问题


#### IM SDK 4.0.10  2019-3-7
修复 AVChatRoom 进入房间超过100人之后收消息异常的问题

#### IM SDK 4.0.8  2019-3-6
TUIkit 音频播放逻辑优化

#### IM SDK 4.0.7  2019-3-1
1. 修复新老版本语音，文件，视频消息互通的问题
2. 解决-5 tls exchange failed 卸载应用重新安装才能登录成功 

#### IM SDK 4.0.4  2019-2-28
1. 解决 userSig 过期后再次登录返回错误码不正确问题，应该返回6206
2. 优化互踢逻辑


#### IM SDK 4.0.3  2019-2-25
修复第三方离线推送问题

#### IM SDK 4.0.2  2019-2-20
修复开启 bitcode 打包失败的问题

#### IM SDK 4.0.1  2019-2-20
修复登录返回-5的问题

#### iOS--IM SDK 4.0.0.1  2019-1-21
新增 TUIKIt

#### IM SDK 3.3.2 2018-7-5
1. 默认禁用自动已读上报 
2. 资料关系链的自定义信息类型新增整型支持
3. 修复通过本地存储获取到的群成员个数不准确的问题
4. 修复用户在收到单聊消息中携带的昵称没有实时更新的问题

#### IM SDK 2.7.2 2018-7-5
1. 默认禁用自动已读上报
2. 资料关系链的自定义信息类型新增整型支持
3. 增加消息撤回功能
4. 修复用户在收到单聊消息中携带的昵称没有实时更新的问题

#### Windows--IM SDK 2.5.8 2018-7-5
1. 修复了某些情况下无法登录的问题
2. 资料关系链的自定义信息类型新增整型支持

#### IM SDK 3.3.0 2018-4-4
**iOS：**
TIMUserProfile 新增 level 和 role 两个字段

**Android：**
1. 增加魅族离线推送支持
2. 用户资料标准属性新增 level、role
3. 修复登出后再重新登录导致 ugc 小视频发送失败的问题

#### IM SDK 2.7.0 2018-4-4
**iOS：**
1. 邀请成员入群接口添加自定义数据参数

**Android：**
1. 增加魅族离线推送支持
2. 邀请加入群组接口允许指定自定义数据

#### Windows--IM SDK 2.5.7 2018-3-13
1. 修改了登录模块，提高了通讯的安全性
2. 优化了弱网络下发消息的能力
3. 修复了打印日志过程中可能出现的 crash 问题

#### iOS--IM SDK 2.6.0 2018-3-13
1. 提供删除漫游消息的接口
2. 提供序列化、反序列化消息对象的接口
3. 修复部分历史问题

#### iOS--IM SDK 3.2.0 2018-3-13
1、修复 getUserProfile 包含好友自定义字段时报错的问题
2、优化群组未读计数跟新策略
3、优化消息本地存储逻辑策略
4、修复部分 Crash 问题

#### Android--IM SDK 3.2.0 2018-3-13
1. 修复发送 ugc 小视频可能失败的问题
2. 修复在断网情况下发送消息没有回调的问题
3. 修复全员禁言不生效问题
4. 优化消息本地存储逻辑策略
5. 修复部分 Crash 问题

#### Android--IM SDK 2.6.0 2018-3-13
1. 提供删除漫游消息的接口
2. 提供序列化、反序列化消息对象的接口
3. 修复部分历史问题

#### IM SDK 3.1.2 2017-12-12
1. Android 端网络超时问题优化
2. Android 端语音下载异常问题修复
3. Android 端若干 crash 问题修复

#### IM SDK 2.5.7 2017-11-08
1. 修复了 SDK 在 App 进程被杀时出现 Crash 的问题
2. 修复重复推送离线消息的问题
3. 修复同时调用 initStorage 和 login 接口，可能出现内部帐号为空的问题
4. 优化网络探测策略
5. 修复获取好友列表异常问题
6. 修复其他一些 Crash 问题

#### IM SDK 3.1.1 2017-8-16
1. 完善 LOG 定时清除机制
2. 修复 iOS QALSDK 在初始化时卡死的问题
3. 添加群组全员禁言功能
4. 修复 iOS 多用户登录失败的问题 
5. 修复 Android 没有登录的时候获取群组列表导致 crash 的问题

#### IM SDK 2.5.6 2017-7-14
1. 修复登录登出期间可能的 crash 问题
2. 修复推流录制中可能的 crash 问题

#### IM SDK 3.1.0 2017-7-3
1. 新增 IMUGCExt.framework 和 TXRTMPSDK.framework，提供小视频录制和上传功能
2. 新增消息撤回功能


#### IM SDK 2.5.5 2017-6-6
1. 优化内部回包逻辑，减少耗时
2. LOG 时间精度精确到毫秒
3. 修复了部分 Crash 和消息同步的问题

#### IM SDKV3 3.0.2 2017-5-22
1. 修复 AVChatRoom 可能无法接收到群消息的问题
2. 接口调整
    i. 废弃 TIMFileElem，TIMSoundElem 中的 setData 接口
    ii. 修正 TIMManagerExt 中的接口拼写： getConversionList => getConversationList

#### IM SDKV3 3.0.1 2017-5-15
1. 修复部分 so 库无法兼容 Android 5.0 以下机器的问题

#### IM SDKV3 3.0 2017-5-8
1. 将 ImSDK 和 IMCore 重新组合为 ImSDK、IMMessageExt、IMGroupExt 和 IMFriendExt
2. 优化 ImSDK 初始化方法为 initSdk： 和 setUserConfig
3. 整理 ImSDK 中接口命名和 Protocol 回调方法命名，统一小写字母开头
4. ImSDK 功能：基本的登录、收发消息、资料和群组功能
5. IMMessageExt 功能：全量消息功能，包括拉取消息、本地存储、未读计数等
6. IMGroupExt 功能：全量群组功能，包括所有群组类型管理、群成员管理等
7. IMFriendExt 功能：全量资料关系链功能，包括好友列表、黑名单等

#### IM SDK 2.5.4 2017-4-28
1. 修复 IMSDK 中定时器机制的 BUG

#### IM SDK 2.5.3 2017-4-17
**iOS:**
1. sendOnlineMessage 接口支持群组类型消息，消息不存本地、不存离线、不计入未读
2. 提供 findMessages 方法，提供按消息 ID 获取本地消息
3. TIMIOSOfflinePushConfig 提供设置 APNs 推送静音选项
4. 修复高频接收消息时，内存上涨问题

**Android:**
1. 增加查找消息接口（详情请查看 TIMConversation 下的 findMessages）
2. sendOnlineMessage 接口支持群组类型消息，消息不存本地、不存离线、不计入未读
3. APNS 推送新增接收端不播放提示音且不振动的配置选项（参见TIMMessageOfflinePushSettings.IOSSettings.NO_SOUND_NO_VIBRATION）
4. 网络优化，增强 SDK 对弱网络场景的抗性

**Windows:**
1. 修复了可能导致 crash 的问题

**接口变更：**
1. TIMMessageOfflinePushSettings.AndroidSettings 及 TIMMessageOfflinePushSettings.IOSSettings 构造方式变更。
详情请参见官网文档 [离线推送](https://cloud.tencent.com/document/product/269/9234) 文档。

#### IM Android SDK 2.5.2 2017-3-1
1. 修复偶现发包返回超时的问题（返回码 6205）

#### IM SDK 2.5.1 2017-2-16
1. 限制 LOG 文件大小为 50M 以内
2. 修复登出后切后台，用户状态返回在线的 BUG
3. iOS 更新下载语音、文件的策略，同时支持 HTTP 和 HTTPS 下载
4. 修复未登录用户时，发送消息失败后状态不匹配的BUG

#### IM Web SDK 1.7 2016-12-20
1. 支持多实例互踢
2. 同时支持多实例同时在线
3. 支持群已读消息同步
4. 支持 C2C 已读消息同步
5. 优化 Demo 目录结构和代码
6. 新增最近联系人列表

#### IM SDK 2.5 2016-12-16
1. 优化了 TIMOfflinePushInfo 对象结构
2. 修复 iOS9.1 下载语音、文件失败的问题
3. 优化了网络操作
4. 修复了部分 bug

#### IM SDK 2.4.1 2016-11-24

1. 修复 TIMGroupAssistant 在进入 AVChatRoom 后异常拉取群组资料的 bug
2. 修复禁用控制台打印失效的 bug
3. Android 端修复初始化后登录前登出导致各种监听器失效问题

#### IM SDK 2.4 2016-11-09
1. 全面兼容 ATS 模式
2. 消息转发功能：提供 copyFrom 接口，可以跳过下载步骤，直接拷贝图片、文件等消息后直接转发
3. 支持 AVChatRoom 群组动态更新群成员数：TIMGroupEventListener 接口返回当前群成员数目
4. AVChatRoom 支持消息过滤自定义
5. TIMOfflinePushInfo 属性支持小米华为推送相关设置
6. 优化拉取群组漫游消息流程
7. 优化语音、文件、微视频上传下载流程
8. 支持设置拉取最近联系人列表时禁止抛出 onNewMessage

#### IM SDK 2.3 2016-9-13
1. 支持同一 appid 多应用消息推送
2. Android 版本增加带回调的 setOfflinePushToken 接口
3. 消息删除逻辑优化，拉取消息时，自动过滤状态为DELETED的消息
4. iOS 版本将数据库文件从 Library/Caches/ 子目录搬迁到 Document/ 子目录，避免被系统清除
5. iOS 版本可以添加和删除多个 TIMMessageListener
6. iOS 版本对常驻线程进行统一命名
7. 获取会话列表接口，自动过滤消息数为0的会话

#### IM Web SDK 1.6 2016-8-15
1. Web 广播消息需求
2. 新增好友系统通知
3. 新增资料系统通知

#### IM SDK 2.2 2016-8-10
1. 支持会话草稿功能
2. 支持会话标记是否存储消息，提升消息处理灵活性
3. 漫游消息支持从旧到新遍历消息，适用消息记录场景
4. 消息增加推送的 ext 和声音，可对某些消息设置推送信息
5. Android 增加 stopQALService 接口，可以在退出应用的时候关掉 QALService
6. 支持网络状态监控，增加网络问题错误码

#### IM SDK 2.1 2016-7-15
1. 支持小米、华为手机消息推送功能
2. 支持已读回执功能，客户可根据产品需求决定是否需要已读回执
3. 支持正在输入状态提醒，客户可根据产品需求决定是否需要提醒正在输入
4. 资料关系链增加性别、生日、地址、语言等标准字段
5. 进出群通知带群内人数，提供接口易用性
6. 修复 SDK 和 Demo 的部分 bug

#### IM Web SDK 1.5 2016-7-13
1. 合并直播聊天室 SDK 能力
2. 修复了 IE8 、9 上传图片问题
3. 进群和退群提示消息新增群成员数字段
4. 修复 SDK 和 Demo 的部分 bug

#### IM SDK 2.0 2016-6-16
1. 多终端已读同步，可以做到多终端在线时未读计数的同步
2. APP 迁移时支持历史消息导入，保证平滑迁移
3. 群消息属性增加消息提醒状态，以提升易用性
4. 支持消息优先级灵活设置
5. 推送通过属性和标签过滤

#### IM Web SDK 1.4 2016-6-7
1. 支持拉取好友历史消息
2. 支持发送红包、点赞消息
3. 创建群接口支持自定义群 ID 和直播聊天室
4. 优化 SDK API 接口，合并登录和初始化接口
5. 优化 Demo 目录结构和代码

#### IM SDK 1.9.3 2016-5-31
1. 修正 winsdk 进程退出的资源析构死锁问题

#### IM SDK 1.9.2 2016-5-27
1. 增加票据过期回调
2. 支持 IPv6（IOS）

#### IM SDK 1.9 2016-5-4
1. 支持超过 1 万人大群（不限制群内人数，适用直播场景）
2. 重构 IM Demo，体验优化，易用性更佳
3. 分优先级发送消息
4. 增加群资料与关系链的存储和缓存
5. 增加群资料与关系链的同步获取接口和变更回调
6. 支持获取好友资料（包括备注、分组）
7. 支持设置群资料与关系链默认拉取字段
8. 支持禁用拉取最近联系人
9. 会话列表增加同步获取最后一条消息
10. 指定拉取某些群成员的群资料（如群名片等）
11. 语音消息和文件消息支持传入文件路径（可支持消息重发）
12. 适配 6.0 动态权限问题

#### IM SDK 1.8.1 2016-4-13
1. Android 优化自启动流程（需要修改配置，请参考 ReadMe.txt 进行配置）
2. 增加单聊发在线消息接口（只有对方在线能收到，离线情况下不存储消息）
3. 增加多发消息接口
4. Android 性能优化

#### IM SDK 1.8 2016-3-23
1. Android 离线推送
2. 增加检测是否好友接口
3. 增加关系链自定义字段接口
4. 增加消息自定义本地存储（可以标识语音是否已读等状态）
5. 图片压缩接口，满足了脱离通信场景下的图片压缩需求
6. 自定义消息 sound 字段，指定 apns 声音
7. 在线状态变更等回调接口完善


#### IM SDK 1.7 2016-1-25
1. 支持群内发言频率限制
2. 支持群转让
3. 支持群消息通知强度可定制
4. CS 通道建设，可帮助客户省去 App 与后台服务器长连接，达到省电功效
5. 消息和最近联系人漫游开关/存储时长/多终端同时在线开关等配置项添加，提高运营效率
6. 下行消息带群成员昵称、名片，帮助客户完善用户体验，优化易用性
7. SDK 精简，有效帮助客户控制安装包大小


#### IM SDK 1.6 2015-12-25
1. 支持微视频消息类型，满足更多视频消息和社交需求
2. 支持群成员列表规则排序，满足群排序需求
3. 支持关系链好友分组能力，满足用户分组需求
4. 群名称/公告/简介敏感词过滤，资料更安全
5. 支持群成员名片，帮助用户识别群成员
6. 支持消息提醒开关，用户可自由选择开关单聊群聊消息提醒

#### IM SDK 1.5  2015-11-16

1. 支持消息记录异步下载
2. 支持 Server 端删除群消息
3. 支持通过用户昵称检索用户
4. 支持通过群名称检索群
5. 支持事件回调控制台自助配置
6. 支持管理员帐号对应用户凭证下载
7. 部分 demo 和技术逻辑优化


#### IM SDK 1.4  2015-10-16
1. 多终端同时登录
2. 不可接收拉黑用户消息
3. 好友推荐删除
4. APNS 推送昵称
5. 群名称敏感词过滤
6. 群公告敏感词过滤
7. Demo 支持游客模式和第三方帐号登录

#### IM SDK 1.3  2015-09-10
1. 支持游客登录模式，无需用户名密码即可登录
2. 支持消息漫游（默认保存 7 天消息）
3. 支持最近联系人漫游和删除
4. 支持通过回调做消息实时同步
5. 支持好友推荐，客户定义推荐逻辑后即可实现好友推荐
6. 支持选择原图或缩略图发送消息，帮助提升用户体验
7. 支持 PUSH 通知消息（Android 仅在线用户可触达）
8. 支持平滑迁移方案，客户迁移，来去自如
9. 支持本地消息删除，帮助用户保护隐私

#### IM SDK 1.2  2015-08-18
1. 支持 Web 平台的 C2C 单聊
2. 群成员上限扩大到 1 万
3. 消息广告和敏感词过滤
4. 提供消息 ID 的 API，可精确定位到消息
5. 用户资料增加好友备注
6. 支持离线状态查看本地消息

#### IM SDK 1.1 2015-07-13
1. 支持 Windows C++ 平台
2. 支持公有群/聊天室群类型
3. 支持增加群简介和群公告，增加禁言、消息屏蔽、群身份设置
4. 用户资料和关系链操作接口（昵称/加好友/黑名单设置等）
5. 支持文件类型消息
6. 图片类型消息优化：图片质量分为原图/缩略图/大图，上传下载接口变更，传递图片路径
7. 日志回调接口增加日志级别
8. 增加同一帐号重复登录，另一方强制下线逻辑
9. 增加 crash 自动上报功能
10. 新增支持托管模式下的自有帐号和第三方帐号集成
11. 新增短信验证注册登录模式
12. 新增支持下载腾讯生成的公私钥做票据验证
13. 新增用户和群组管理

#### IM SDK 1.0  2015-05-11
1. 支持 Android/iOS 平台
2. 支持自有/第三张帐号登录集成
3. 支持单聊、群聊（讨论组）的会话类型
4. 支持文本、表情、图片、语音、地理位置、自定义消息的消息类型
5. APNs 离线推送（上报 Token，前台后切换事件上报）
6. 消息本地存储
