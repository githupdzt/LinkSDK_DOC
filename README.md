### AndroidLinkSDK API https://githupdzt.github.io/LinkSDK_DOC/

#### 初始化
1. initServices(Context context),用来启动网络层的两个服务。
2. setApplicationVersion()，设置程序的版本号。
3. login(Context context, String userName, String lenovoId, String language), 登陆到服务器。调用者需要提供用户名，lenovoId,和程序的语言等。
4. checkLoginState(),检查登陆状态,其它命令没有先后顺序的关联

### 如何登录Link服务器？
1. 使用Lenovoid-sdk-custom sdk 登录/注册到Lenovo服务器，登录成功后获取，lenovoid,token 等参数。
2. 使用Link_SDK 的Commder.login(name,lenovoId,token..)方法即可登录到link服务器。

### 如何绑定设备？
```
sequenceDiagram
A->>B: How are you?
B->>A: Great!
```


### 如何控制设备？




