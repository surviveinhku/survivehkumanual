# 科学上网

> 信息校对：B27 冯雪菲

近期部分新生收到了Master Registration的邮件，搞定了Portal登录后，大家就可以开始使\
用港大科学上网神器HKUVPN了！



港大VPN是一条供校内网络外的教职员工、学生、荣誉聘任人员和部门账户持有人访问校园\
网络的通道。它支持用户通过安全连接访问IT系统和电子资源，就像在校园内一样。它也可\
以帮助我们在内地使用Google搜索、Gmail、YouTube等工具。



### 一、登记使用MFA

多因素认证（MFA）是一种安全方法，要求用户在访问M365账户时提供两种或更多类型的证明来确认其身份。通过要求多种验证因素，MFA增加了一层额外的安全性，使得未经授权的人员获取敏感信息或账户变得更加困难。\
如果你已经配置过MFA，可以跳过当前部分。

> 注：自2025年3月6日起，所有学生从校外网络登录香港大学门户网站时都必须使用MFA。

\
登录个人portal，在“Campus Information Services”中的“Central IT Services”栏目内点选“Register to use MFA”并在弹出的网页内填妥对应信息。

**Step1：**&#x767B;入Portal → Campus Information Services → Central IT Services → Register to\
use MFA



<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

***

**Step2** 填写Alternate邮箱与手机号码

> 注：Alternate邮箱须与portal邮箱不同（不可以是HKU邮箱），RIC建议大家填写在内地可以> 登录的邮箱地址。

**Step 3** 确认信息无误点击Confirm即可

> 注：此后如需修改alternate邮箱地址，步骤与以上所示首次登记步骤基本相同。

二、下载VPN客户端

> 注：若此前已经下载过客户端可以选择跳过此步

同样在“Central IT Services”栏目内，选择“Download HKUVPN Client”，大家就会看到不同设备的客户端下载链接。

港大VPN使用Cisco Secure Client应用程序进行连接，Cisco Secure Client 是由思科开发的一款综合性安全客户端软件，主要用于提供安全的远程访问和端点保护。

<figure><img src="../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

***

请根据自己的设备下载对应的客户端

Windows x86（这是大多数的选择） [https://its.hku.hk/download/?wpdmdl=28989](https://its.hku.hk/download/?wpdmdl=28989)

Windows arm64   [https://its.hku.hk/download/wpdmdl=56377](https://its.hku.hk/download/?wpdmdl=56377)

\
macOS[ https://its.hku.hk/download/?wpdmdl=28999](https://its.hku.hk/download/?wpdmdl=28999)

\
Linux[ https://its.hku.hk/download/?wpdmdl=29002](https://its.hku.hk/download/?wpdmdl=29002)



\
Android（Google Play）\
[https://play.google.com/store/apps/details?id=com.cisco.anyconnect.vpn.android.avf](https://play.google.com/store/apps/details?id=com.cisco.anyconnect.vpn.android.avf)

\
iOS [https://apps.apple.com/us/app/cisco-secure-client/id1135064690](https://apps.apple.com/us/app/cisco-secure-client/id1135064690)



***

三、安装客户端并连接\
由于不同设备的安装与连接方式不尽相同，大家可以复制以下链接至浏览器查看详细教程

[https://www.its.hku.hk/documentation/guide/network/remote/hkuvpn2fa](https://www.its.hku.hk/documentation/guide/network/remote/hkuvpn2fa)

安装Cisco Secure Client\
由于不同的设备具有不同的的安装过程，你可以访问如下地址查看HKU官方提供的安装教程\
Windows

{% embed url="https://its.hku.hk/kb/setup-procedure-of-hkuvpn-with-multi-factor-authentication-mfa-for-windows/" %}

_macOS_

{% embed url="https://its.hku.hk/kb/setup-procedure-of-hkuvpn-with-multi-factor-authentication-mfa-for-macos/" %}

Linux

{% embed url="https://its.hku.hk/kb/setup-procedure-of-hkuvpn-with-multi-factor-authentication-mfa-for-linux/" %}

_Android_

{% embed url="https://its.hku.hk/kb/setup-procedure-of-hkuvpn-with-multi-factor-authentication-mfa-for-android/" %}

_ios_

{% embed url="https://its.hku.hk/kb/setup-procedure-of-hkuvpn-with-multi-factor-authentication-mfa-for-ios/" %}

虽然不同的设备具有不同的UI界面，但是此部分的最终目的都是添加一个服务器地址。\
它们的连接过程通常是：输入邮箱和Portal密码 -> 输入一次性密码代码 -> 连接成功

需要注意的是，MS Authenticator一次性密码代码 **每30秒刷新一次，刷新后原密码失效，**&#x56E0;此请尽快输入

以下为Windows/Mac安装客户端后的连接流程<br>

Step 1 启动客户端，在栏内填写“vpn2fa.hku.hk”，点击Connect

<figure><img src="../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

Step 2 通过Portal信息验证

\
![](<../../.gitbook/assets/image (3) (1).png>)

Step 3 通过一次性验证码验证

第二步通过后，大家会在之前填写的Alternate邮箱中收到一个6位验证码，将验证码填写到“Answer”栏中，点击Continue即可（此步骤在收到验证码5分钟内完成）

注：验证码信息可能会被投放至垃圾邮箱中，若大家在通过第二步验证后未在收件夹中收到验证码，可检查一下垃圾邮箱。\
目前港大VPN支持多种设备，港大ITS部门也针对各种设备为大家准备了相应的设置流程。\
大家可以通过复制以下链接至浏览器查看（此链接无需VPN即可使用）。

{% embed url="https://its.hku.hk/kb/hkuvpn-connection-with-2fa/" %}

也可以具体查看RIC推送如何优雅地使用港大VPN\
查看详细操作教程。

{% embed url="https://mp.weixin.qq.com/s/ZT2goxcfaVQmyalveCAYoQ" %}

常见问题：

在连接VPN时一个比较常见的问题是客户端提示「登录失败」，出现这个问题的原因可能有\
很多，但通常建议依次排查如下几个方面：\
1.确保用户名和密码填写正确，其中用户名需要包含邮箱后缀（@connect.hku.hk）

\
2.确保一次密码代码输入及时且准确，由于验证码每30秒刷新一次，若发现剩余时间较短，建议等待刷新后再填写\
3.确保你的学校Microsoft账号添加了MFA验证方法，若已添加，可尝试删除当前MFA验证，并重新按照推送第一部分的方式添加\
4.确保你的设备在连接HKUVPN前并未连接到任何 其它代理工具\
5.若上述方法均无效，可尝试卸载并根据推送第二部分的方式重新安装CiscoSecureClient





_Licensed under CC BY-NC-ND 4.0. Copyright © 2026 HKURIC. All Rights Reserved._ _未经许可，禁止演绎、修改或商业用途。_
