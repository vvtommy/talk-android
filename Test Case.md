##  Test Case for Talk-Android

> **所有流程均需要验证**  
>
- **客户端登陆用户于客户端操作**  
- **客户端登陆用户于其他平台操作**  
- **其他用户于其他平台操作**

> **三种情况下的结果**  

### 关于特殊属性与权限

优先级自上至下递减  

- 团队noJoinable无成员相关操作
- general话题无法改名、踢出成员
- 仅团队管理员可以进行团队设置
- 仅团队管理员可以进行成员管理（角色、移除）
- 仅团队管理员或话题创建者可以进行话题设置

### 注册登陆
- [ ]手机号注册
- [ ]邮箱注册
- [x]teambition 账号登录
- [ ]手机号登录
- [ ]邮箱登录
- [ ]手机号找回密码
- [ ]邮箱找回密码
- [ ]退出登录

### 团队

- [x]创建团队流程
- [ ]二维码扫描加入团队
- [x]更改团队名称
- [x]更改团队颜色
- [x]设置团队别名
- [x]切换团队
- [x]退出团队

### 话题

- [x]创建话题
- [x]更改话题名称、目标、颜色
- [x]更改置顶属性
- [x]更改静音属性
- [x]更改私有话题属性
- [x]添加新成员
- [x]从团队添加成员
- [x]私有话题踢出成员
- [x]归档话题、解除归档
- [x]删除话题
- [x]退出话题

### 成员
- 添加团队成员

		1. [x]邮件邀请
		2. [ ]手机号邀请
		3. [x]二维码邀请

- [x]更改成员角色
- [x]移除成员
- [x]已离开成员查看
- [x]查看已离开成员聊天记录

### 最近
- [x]隐藏最近聊天消息
- [x]显示网络连接状态


### 消息

- 发送消息
  1. [x]文本消息
  2. [x]图片消息
  3. [x]语音消息
- [x]修改文字消息
- [x]删除消息
- [x]最近消息置顶
- [x]图片分享到简聊
- [x]静音消息显示（包括当前团队和其他团队）
- [x]被邀请进其他团队通知
- [ ]聚合消息显示、teambiton聚合消息跳转到Teambition客户端
- [ ]消息转发（聊天界面入口、收藏）

### 更多
- 个人收藏
   1. [x]长按消息添加收藏（图片浏览器收藏）
   2. [x]批量删除收藏
   3. [ ]搜索收藏
- 自动整理
   1. [x]各种整理查看
   2. [x]过滤整理
- 标签
   1. [x]长按消息添加标签
   2. [x]删除标签
   3. [x]进入标签入口，点击查看标签

- 团队设置
   1. [x]管理员修改团队颜色与名称
   2. [x]退出团队
- 个人设置
   1. [x]个人头像、姓名、电话、团队别名修改
   2. [x]账号绑定：邮件、手机、微信等 流程
   3. [x]通知设置：设置通知与振动
   4. [x]意见反馈与服务条款
   5. [x]退出登录

### 搜索
- [x]实时搜索本地话题与成员
- [x]记录搜索记录
- [x]点击搜索相关消息并可以跳转到消息上下文
