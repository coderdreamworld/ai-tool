# **小白搭**

# **chatgpt**

# **代理！**

# **0**

# **基础实操的无敌详细图文帖**

只需3个环节：需要准备：一个[服务器](https://c1n.cn/UnHK0)[vps](https://c1n.cn/UnHK0)、自备一个[chatgpt key](https://platform.openai.com/account/api-keys)（不懂如何申请gpt，想白嫖？[戳这里，楼主给你找个插件](https://vw33bncyqrt.feishu.cn/docx/BHa0dG9fxoExg7xvgpScEL9Gnxb#Seisd2YIAoWQyoxSAUZcZlabnYc)）、一个qq号。

（想学搭微信的gpt？我写了另一篇超详细教程： [简单！小白](https://vw33bncyqrt.feishu.cn/docx/PfymdoumHoaBYUxyLyycjTpznqc)[0代码搭微信chatgpt，无敌图文教程！](https://vw33bncyqrt.feishu.cn/docx/PfymdoumHoaBYUxyLyycjTpznqc) ）

本文全程图片介绍，简单清晰，好处：

**1**** 、随时随地可用，不担心科学网络问题**

**2**** 、手机、电脑均可用**

**3**** 、可浏览器访问，也可在 ****QQ**** 中使用**

| ![]([RackMultipart20230402-1-u1j1vg_html_b201019086613d18.png](https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/v2/cover/boxcn3cXbqpMlsEs1HVh8pCH4ib/?fallback_source=1&height=1280&mount_node_token=A2E8dM4Aio4s6MxUzdtcaEYyn6e&mount_point=docx_image&policy=equal&width=1280)) | ![]([RackMultipart20230402-1-u1j1vg_html_e8f1523f3ee8bfd7.png](https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/v2/cover/boxcnnh0fnesIyOOKBj3Mlj0D9U/?fallback_source=1&height=1280&mount_node_token=PqscdYGAUosGSOxKCD0cxZZynQf&mount_point=docx_image&policy=equal&width=1280)) |
| --- | --- |

**第零章：教程说明**

Hey hey hey！听说你想学习如何搭建一个真正能和你聊天的AI助手？那你可来对地方了！我刚刚写了一篇神仙级chatgpt搭建教程，让你轻轻松松愉快地玩转这个AI世界！

嗯？不会申请服务器？没关系！我的教程图文并茂、详细易懂，为你从服务器的申请到环境的配置，全方位呈现出每一个细节！能作为一只小白都不必惧怕~

哪怕是原来不想学技术，看了这篇超级吸睛的教程后，相信你也会重新对它心生热爱。更爆炸的是，我还会告诉你如何在QQ上让chatgpt随时随地为你服务！每次的无聊时光如此取消！

来吧，别再拖延了！相信我，用一个下午的时间学习这篇教程，你将打开一扇前所未有的大门，那里有无限可能等待你的探索！

**嗯，这段就是在**** QQ ****中用**** ChatGPT ****生成的**

![](RackMultipart20230402-1-u1j1vg_html_eb92127657fef9fb.png)

接下来，进入真正的教程吧~

**第一章：申请服务器**

**这里以**** vultr ****为例，其他服务器例如** [**Sugarhost**** 官网**](https://vw33bncyqrt.feishu.cn/docx/BHa0dG9fxoExg7xvgpScEL9Gnxb#JgiSdMyYUoYUCmxCcM1cI9TznQc)**、**[**腾讯云官网**](https://vw33bncyqrt.feishu.cn/docx/BHa0dG9fxoExg7xvgpScEL9Gnxb#Vs2udUWYGoGgMGxykLhcTPk4nXf)**也可以的（不推荐阿里云，后面有写原因），最低配就能满足了。**

**购买服务器地址：** [**https://c1n.cn/UnHK0**](https://c1n.cn/UnHK0) **（**** 点链接送 ****100**** 额度，也防止找到假冒的 ****）**

**1.1**  **注册账号**

**用你常用的邮箱，注册**** vultr ****账号，**** qq ****邮箱也可以的**

![](RackMultipart20230402-1-u1j1vg_html_1943b205e7239840.png)

**1.2**  **配置一台服务器**

**在**** Products ****界面，点**** + ****，然后选第一个**  **Deploy New Server**

![](RackMultipart20230402-1-u1j1vg_html_19f7a97012d94927.png)

**型号，选最基础的**  **Cloud Compute**  **即可**

![](RackMultipart20230402-1-u1j1vg_html_36983997b95a31ce.png)

**地区，可任意选（注意查一下**** ChatGPT ****不支持的地区），为了访问速度快，建议**  **Tokyo**

![](RackMultipart20230402-1-u1j1vg_html_96fe226189a33e1d.png)

**系统，我用默认的**** Debian11 **** （如果你有一定的技术基础，用其它也可）**

![](RackMultipart20230402-1-u1j1vg_html_b3e4430ce80cfe6b.png)

**备份功能对我们没用处，可以关闭，省点钱**

![](RackMultipart20230402-1-u1j1vg_html_99c559f2aaae3bed.png)

**服务器配置，也选最小的**

![](RackMultipart20230402-1-u1j1vg_html_12b8706a63c4799b.png)

**最下面的服务器名，随便你自己填。如果你要申请很多服务器，可以用来区分用途**

**然后点击**  **Deploy Now**  **，提交申请**

![](RackMultipart20230402-1-u1j1vg_html_4e74bc50062127e6.png)

**等待**** 1 ****分钟，服务器申请好了，显示**  **Running**  **运行中**

![](RackMultipart20230402-1-u1j1vg_html_c881fd718afc074e.png)

**点击进去，可以看到配置，包括**  **IP**** 地址 服务器账号、密码**

![](RackMultipart20230402-1-u1j1vg_html_299eb7207a49e6bd.png)

以上，已经拿到了服务器。（有些ip可能访问有异常，可以ping一下，不会ping也没关系，后面会有其他方法）

**1.3 ping**** 检查 ****ip**** 地址是否正常**

**Windows**** 电脑，点击键盘的 ****windows+R**** ，弹出命令窗口，输入 **** cmd ****，点确定**

![](RackMultipart20230402-1-u1j1vg_html_ebf3dff77e3d3df1.png)

**输入**  **ping +**  **你的**** ip ****地址，回车，看输出信息**

**如果界面上显示 "请求超时"，那这个服务器在国内就访问不到。需要重新申请一个服务器**

![](RackMultipart20230402-1-u1j1vg_html_81a5ff7a0e423cad.png)

**第二章：安装服务器环境配置**

**2.1 XShell**** 安装**

这是个免费的工具，打开XShell官网 https://www.xshell.com/zh/xshell/ ，点下载

![](RackMultipart20230402-1-u1j1vg_html_319cce932d6229a8.png)

**许可类型，找右边的 免费授权页面，点击进去**

![](RackMultipart20230402-1-u1j1vg_html_fb19ef5207762da2.png)

**输入你的信息，姓名随便填，邮箱能收到邮件即可。点击下载，会把下载链接发到你的邮箱**

![](RackMultipart20230402-1-u1j1vg_html_cdd15cdda5e8adab.png)

**下载后，安装。这个不用教吧**

![](RackMultipart20230402-1-u1j1vg_html_b5b3a3bf93cecf3e.png)

**启动**** XShell ****，点左上角**  **+**  **新建一个会话，准备连上你的服务器**

![](RackMultipart20230402-1-u1j1vg_html_b875c5c4f9434a19.png)

**在配置页面，输入你的服务器**** ip ****。 名称随便填，也是为了区分多个会话的。 然后点 连接**

![](RackMultipart20230402-1-u1j1vg_html_e0d068b57bb5fac7.png)

**第一次连接，会弹出一个**** SSH ****警告，选 接受并保存**

![](RackMultipart20230402-1-u1j1vg_html_14067bbcc1e9b36e.png)

**弹出一个登录框，填入用户名，一般都是**  **root**** 。 在你服务器的配置页面上能看到**

![](RackMultipart20230402-1-u1j1vg_html_ef930cb4742886c3.png)

![](RackMultipart20230402-1-u1j1vg_html_c3aef43b73c21781.png)

**输入密码，也是在配置页复制过来。点 记住密码， 确定**

![](RackMultipart20230402-1-u1j1vg_html_900ac36bc7ef693b.png)

**一切顺利的话，就会登录进去了。**

**如果不能登录，或者登录连接很慢，说明**** ip ****受限了，请直接注销机器，重新注册（** [**跳转重新注册**](https://vw33bncyqrt.feishu.cn/docx/BHa0dG9fxoExg7xvgpScEL9Gnxb#DoKQdyUICo8smuxSIcxcJZzBnce) **成本很低）**

![](RackMultipart20230402-1-u1j1vg_html_d27012f8908bb324.png)

**2.2 Koishi**** 安装**

**Koishi**** ，是国内某大佬开发的开源工具，里面有很多一键部署插件，包括免费 ****AI**** 绘画、免费 ****Chat**** 、资讯监控、 ****QQ**** 转发、 ****Discord**** 转发、飞书转发等，很不错的一个平台。有能力的还可以自己开发插件。**

**当然这些需要花时间研究，目前我们用到的插件就**** 2 ****个，我会直接告诉你。怎么配置，怎么用。**

![](RackMultipart20230402-1-u1j1vg_html_2d5687a329211c5d.png)

**为了使用插件，我们要在服务器上安装**** Koishi ****（电脑本地也可以安装，但本地你连**** ChatGPT ****需要科学网络，你懂，而服务器已经具备连接**** ChatGPT ****的环境了）**

**PS**** ：先说一个小 ****tip**** ， ****XShell**** 的界面支持 粘贴，把我列的命令依次粘贴即可**

![](RackMultipart20230402-1-u1j1vg_html_67d8bb0947c631ff.png)

**好，接下来，准备进入安装了**

（点击链接 [Koishi安装命令可复制](https://vw33bncyqrt.feishu.cn/docx/Pq0ddFqAvoUhidxGuKUcmnIInVe)）

**复制命令，粘贴到服务器命令中，安装所需环境。等一句执行完，再贴下一句：**

| Plain Text
sudo apt-get update |
| --- |

| Plaintext
sudo apt-get install apt-transport-https |
| --- |

| Plaintext
sudo apt-get install ca-certificates |
| --- |

| Plaintext
sudo apt-get install curl |
| --- |

| Plaintext
sudo apt-get install gnupg |
| --- |

| Plaintext
curl -fsSL https://download.docker.com/linux/debian/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg |
| --- |

| Plaintext
echo "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/debian $(lsb\_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list \> /dev/null |
| --- |

| Plaintext
sudo apt-get update |
| --- |

| Plaintext
sudo apt-get install docker-ce docker-ce-cli containerd.io |
| --- |

**最后一句命令，会询问是否继续**** (y/n) ****。输入**** y ****，回车即可：**

![](RackMultipart20230402-1-u1j1vg_html_9de61ab09fdfc90d.png)

**最后一条命令，安装并启动**** koishi**

| Plaintext
sudo docker run -p 5140:5140 koishijs/koishi |
| --- |

**安装完成后，在浏览器输入**  **你服务器的**** ip+ ****端口**** 5140 ****，即可访问。例如**** : 1.1.1.1:5140**

![](RackMultipart20230402-1-u1j1vg_html_1f49fe26da897542.png)

**恭喜完成**** 2/3 ****的教程，马上就能用上了！**

**第三章：**** Koishi ****配置**

**欢迎进入**** Koishi ****，你看到的是一个界面控制面板，最左侧有一系列的功能**

![](RackMultipart20230402-1-u1j1vg_html_c406148655a4b79c.png)

**3.1**  **安装**** 2 ****个插件**

**我们需要点击左侧的市场，安装**  **davince**  **、**** adapter-onebot **** 这 ****2**** 个插件**

![](RackMultipart20230402-1-u1j1vg_html_cdbaa2d7fbcb6e34.png)

**搜索**  **chatgpt**** ，会看到第一个 **** davince-003 ****，点击添加，并安装**

![](RackMultipart20230402-1-u1j1vg_html_243cdf55edb1820c.png)

![](RackMultipart20230402-1-u1j1vg_html_4540da2223f00f85.png)

**搜索**** onebot ****，同样进行安装（有可能默认已经帮你安装好了）**

![](RackMultipart20230402-1-u1j1vg_html_86546e91789e0519.png)

**3.2**  **启动**** onebot ****插件**

**首先启动**** onebot ****，是**** qq ****的代理（原理是，用你的**** qq ****号转发消息）。**

**点击最侧的配置，列表里找到**  **adapter-onebot**

![](RackMultipart20230402-1-u1j1vg_html_a4c597354aa620cf.png)

**在配置页，机器人密码就是你的**** qq ****密码，机器人账号就是你的**** qq ****号。都填入进去**

![](RackMultipart20230402-1-u1j1vg_html_75ed9677c908bf3e.png)

**注意打开 自动创建**** go-cqhttp ****子进程**

![](RackMultipart20230402-1-u1j1vg_html_a8e4fd3a2d8b074e.png)

**点击右上角的 ▷ 进行启动**

![](RackMultipart20230402-1-u1j1vg_html_45dbb5f0ffb7001a.png)

**有需要的话， 也可以 √ 重启**

![](RackMultipart20230402-1-u1j1vg_html_cf4ba1ab994fd2c1.png)

**会弹出**** qq ****的验证方式，你选一个，然后验证**** qq ****安全（相当于把**** qq ****号登录了）**

![](RackMultipart20230402-1-u1j1vg_html_dfba68097da3889b.png)

**验证成功后，点击重新启动：**

![](RackMultipart20230402-1-u1j1vg_html_92985ed9aa31f000.png)

**顺利的话，会显示连接成功：**

![](RackMultipart20230402-1-u1j1vg_html_2675d7a5f61c2c56.png)

**3.3**  **启动**  **davince**  **插件**

**同样在配置页，找到**** davinci ****插件，输入你的**** chatgpt key ****，点 ▷ 启动**

![](RackMultipart20230402-1-u1j1vg_html_3fa9f8720dde41f.png)

**改配置后记得重启**

![](RackMultipart20230402-1-u1j1vg_html_f4415845d791a979.png)

**key**** 的获取地址：**[**platform.openai.com**](https://platform.openai.com/account/api-keys)**（这里需要自己解决，买，或者找朋友）**

![](RackMultipart20230402-1-u1j1vg_html_5961cf879ca3038f.png)

**别名，也就是暗号**** ，是在给 ****ChatGPT**** 发消息时的前缀。**

**例如截图中有**** 3 ****个别名，你可以发 "**** ai **** 请给我写一段小红书介绍我的产品"， 实际 ****ChatGPT**** 收到的是 "请给我写一段小红书介绍我的产品"**

![](RackMultipart20230402-1-u1j1vg_html_6fab8002a282e3b8.png)

**你也可以改成 "呼叫大刀"，后续就发 "呼叫大刀 给我来一段**** rap" **** ，"呼叫大刀 你的大刀有多少米"**

![](RackMultipart20230402-1-u1j1vg_html_599d827b829b14e7.png)

**另外，配置项可根据需求修改，**

**例如：这里有内容审核功能，可以去百度申请，价格也不贵**  **https://ai.baidu.com/solution/censoring**

![](RackMultipart20230402-1-u1j1vg_html_3d3a0d13db54ab1b.png)

**第四章： 欢迎来到**** QQ ****分身**** ChatGPT**

**现在，**** QQ ****环境的**** ChatGPT ****已经准备就绪！**

**再啰嗦一下原理，前面配置的**** qq ****号，被当做了一个机器人，转发你和**** ChatGPT ****之间的消息。**

**那怎么用呢？比如 我想自己跟**** ChatGPT ****聊，或者 我想拉朋友一起玩**

**有两种常用使用方式：**

**4.1**  **浏览器直接与**** ChatGPT ****聊（不需要科学网络）**

**在**** koishi ****左侧，找到沙盒功能，任意添加一个用户，然后直接聊天**

![](RackMultipart20230402-1-u1j1vg_html_249b839ac5ac0eab.png)

![](RackMultipart20230402-1-u1j1vg_html_800267f0cd57dccf.png)

**如果你想让朋友用，简单的方式是把你的**** Koishi ****首页链接转给朋友。**

![](RackMultipart20230402-1-u1j1vg_html_d6580f818babea22.png)

**如果怕被随意传播，可以额外配置一个账号登录功能，在插件市场搜索安装**** login**

![](RackMultipart20230402-1-u1j1vg_html_909484e99ddcb99a.png)

**然后配置一个登录账号**

![](RackMultipart20230402-1-u1j1vg_html_781af706c57efc41.png)

**4.2**  **在**** QQ ****中私聊、群聊（不需要科学网络）**

**你上面用来配置的**** qq ****号，现在承担了一个机器人的功能。当然，日常的其他功能还是正常用的。**

**那么，你的朋友可以直接发消息给它，**** 记得带上暗号**

![](RackMultipart20230402-1-u1j1vg_html_ed1f8f7e237c1c08.png)

**也可以**** 建一个群聊 ****，把你的机器人**** qq ****拉进去，任何人发的暗号它都会收到。**

**例如，我发了一段暗号"**** ai **** 请帮我介绍我的教程，鼓励大家来学习"，嗯，生成的文本在教程开头，你已经看到了**

![](RackMultipart20230402-1-u1j1vg_html_ed84be07e975deaf.png)

**第五章：其他说明**

**5.1**  **其他常用服务器**

DigitalOcean、Linode、[搬瓦工](https://c1n.cn/dh70p)等，可自行搜索

**5.1.1** [**Sugarhost**](https://c1n.cn/A28EL) **服务器** X

也是对国人操作非常友好的一个服务器品牌，中文界面，流程也很友好清晰（官网链接：[戳我直达官网入口](https://c1n.cn/A28EL)）

**打开主页，选**  **VPS**** 云服务器 **** -\> Linux ****云服务器**

![](RackMultipart20230402-1-u1j1vg_html_940d8955d59ae47.png)

**选择北美**** - ****月付，这样花钱少。如果想长期用也可选年付**

![](RackMultipart20230402-1-u1j1vg_html_8a4580c2313d4aeb.png)

**主机命名一下，后续登录要用**

![](RackMultipart20230402-1-u1j1vg_html_89e679e04db5834d.png)

**系统选**** Debian 11**

![](RackMultipart20230402-1-u1j1vg_html_5e5d5ffed8d7927a.png)

**点击 结账。后面付款不用教哇**

![](RackMultipart20230402-1-u1j1vg_html_14d1f703ef409ab0.png)

**购买后的服务器，在这里**

![](RackMultipart20230402-1-u1j1vg_html_5fd6c4fb5ffa4355.png)

**点击进入**

![](RackMultipart20230402-1-u1j1vg_html_49542280c678dc65.png)

**有可能正在创建，那就等一下。 账户名、密码也在这个位置了**

![](RackMultipart20230402-1-u1j1vg_html_a3bff0e145a24270.png)

**后续，跟前述的安装过程一样了 ，拿到 用户名、密码，用**** XShell ****登录进行配置**

![](RackMultipart20230402-1-u1j1vg_html_d8ce401c7c109714.png)

**啊对了，别忘了从检查**** ip ****速度开始** [**戳我直达**](https://vw33bncyqrt.feishu.cn/docx/BHa0dG9fxoExg7xvgpScEL9Gnxb#NCGsdMC0gowQUExMNY8cVGI5nJb)[**ping**** 检查 ****ip**** 教程位置**](https://vw33bncyqrt.feishu.cn/docx/BHa0dG9fxoExg7xvgpScEL9Gnxb#NCGsdMC0gowQUExMNY8cVGI5nJb)

**服务器配好后，记得**** 先打开端口防火墙 ****，否则后面会安装失败。这里以默认**** 5140 ****为例**

![](RackMultipart20230402-1-u1j1vg_html_f0ff1e9012ddaa99.png)

![](RackMultipart20230402-1-u1j1vg_html_4c13c58a83c3457f.png)

**配置 入 规则，记得启用**

![](RackMultipart20230402-1-u1j1vg_html_194eff9f6b844b9a.png)

**配置 出 规则，启用**

![](RackMultipart20230402-1-u1j1vg_html_7aec3e8009458215.png)

**然后就可以按照 之前的命令开始安装了** [**戳这里回到 安装命令步骤**](https://vw33bncyqrt.feishu.cn/docx/BHa0dG9fxoExg7xvgpScEL9Gnxb#JWSid4uksoI4E6xYTmfcqZ8qn6g)

**5.1.2**  **阿里云服务器**

**我试了几次，会遇到**** DNS ****解析的问题，新手还是别忙活了**

**5.1.3**  **腾讯云服务器**

**腾讯云，国内第二大云服务商，也是有提供一些 新加坡 东京等地区的服务器的，**** 找最便宜的：**[**戳这里直达服务器入口**](https://c1n.cn/qMUEm)

**国内服务器，登录、支付、找客服都比较方便，我们选** [**最便宜的轻量服务器**](https://c1n.cn/qMUEm)

![](RackMultipart20230402-1-u1j1vg_html_e1ad125885edd4d2.png)

**进入控制台，点击选购**

![](RackMultipart20230402-1-u1j1vg_html_688c146172b719e0.png)

**创建方式，选 容器镜像**

![](RackMultipart20230402-1-u1j1vg_html_ce40ed151ea287f8.png)

**镜像用默认的即可**

![](RackMultipart20230402-1-u1j1vg_html_817ff62991f0e3a7.png)

**地区选 亚太， 新加坡 东京 选一个吧**

![](RackMultipart20230402-1-u1j1vg_html_ad6d3810ccc7f003.png)

**套餐选最便宜的即可**

![](RackMultipart20230402-1-u1j1vg_html_7eeaa44a38851506.png)

**实例名称随便填，服务器多的时候方便区分的**

![](RackMultipart20230402-1-u1j1vg_html_486f0861dc2dcc8a.png)

**去掉自动续费， 选**** 1 ****个月， 购买**

![](RackMultipart20230402-1-u1j1vg_html_11cebb3ef62b6cfe.png)

**付费**

![](RackMultipart20230402-1-u1j1vg_html_3af35d28517be66c.png)

**找到服务器入口**

![](RackMultipart20230402-1-u1j1vg_html_9e5a0c3e16342844.png)

**查看详情**

![](RackMultipart20230402-1-u1j1vg_html_f40f2785861abc64.png)

**进入控制台后，还是先设置防火墙**

![](RackMultipart20230402-1-u1j1vg_html_5afccade207ae061.png)

**把配置填好，确认**

![](RackMultipart20230402-1-u1j1vg_html_10379f6503aaf358.png)

**设置服务器密码**

![](RackMultipart20230402-1-u1j1vg_html_4b3fc1c43afaef06.png)

**填写你的密码，确认**

![](RackMultipart20230402-1-u1j1vg_html_4607766d20b4eac3.png)

**买服务器的时候选了**** Docker ****，就免去了很多安装内容。直接安装**** koishi ****吧：**

| Plaintext
sudo docker run -p 5140:5140 koishijs/koishi |
| --- |

有服务器的使用问题，也可以看[腾讯帮助文档，或者找客服](https://c1n.cn/EsH2n)

**然后就可以** [**戳这里回到 服务器配置步骤**](https://vw33bncyqrt.feishu.cn/docx/BHa0dG9fxoExg7xvgpScEL9Gnxb#WkqQdoUsios2AexkzIQcjTQPn6f)

**5.2 Koishi**** 求助**

koishi官方整理了不少文档，可以参考查阅 ：[https://koishi.chat/](https://koishi.chat/)

另外，也可以搜索官方的QQ群 "Koishi 用户交流"， 群号：391463133

早苗插件官方帮助文档：yuque.com/km57bt/hlhnxg/

**5.3**  **白嫖**** GPT ****服务**

gpt服务目前有很多代理，也有很多免费服务。同样，在koishi中也有免费的插件服务，用来跟朋友玩、引流，也足够了。当然受限于免费，它可能不如你自己的plus账号那么好用

**在**** koishi ****插件市场，搜索 早苗 ，添加这个插件**

![](RackMultipart20230402-1-u1j1vg_html_ca4595223305de56.png)

**在配置中找到它**

![](RackMultipart20230402-1-u1j1vg_html_db5744ef6b0df72b.png)

**根据提示，选定一个角色，在范围内随便选一个编号填入**

![](RackMultipart20230402-1-u1j1vg_html_703dfae7cf88c703.png)

点击启动

![](RackMultipart20230402-1-u1j1vg_html_25c51922efbb8c8b.png)

**然后在**** qq ****中，发送暗号 "早苗**** on" ****，即可启动机器人服务**

![](RackMultipart20230402-1-u1j1vg_html_63dff023ee15f597.png)

**早苗官方帮助文档，**** yuque.com/km57bt/hlhnxg/**

**发送暗号**  **ai +**  **你想问的问题，即可。例如：**

![](RackMultipart20230402-1-u1j1vg_html_97155f739b713585.png)

**早苗是一款非常优秀且作者非常用心维护的免费插件。它的用处不仅限于**  **ai**** 聊天，还包括 ****ai**** 画画、游戏、互动、玩梗、查天气、报时等，好好利用它可以大大的活跃群气氛**

![](RackMultipart20230402-1-u1j1vg_html_766e14b155708e8d.png)

**5.4**  **其他**** Tip**

a、vultr如遇ip无法连接，或连接很慢，先申请新服务器，再释放旧的（否则很可能给一个相同的ip）

b、sugarhost如遇ip问题，可找到 服务单，发信息跟客服沟通

c、qq会不会被封？ 把控使用节奏，群里真人的聊天信息多，就不容易封。另外插件的功能也可以研究下，有改提示语、控制频率等

d、注意每种主机的权限控制可能稍有不同。 每条命令执行，如果遇到 Y/n 都记得输入 Y

e、http://198.211.33.209:5140/market 我搭的服务，随便玩，玩坏了重启。目前只买了1个月

f、有些服务器默认防火墙比较严格，看到后台上有配置的，都先开启5140端口，再进行安装

g、发暗号，记得加空格

h、[Koishi安装命令 可复制](https://vw33bncyqrt.feishu.cn/docx/Pq0ddFqAvoUhidxGuKUcmnIInVe) 安装命令可以看这里

i、插件尽量都更新到最新版，保证匹配

**六、如何搭微信的**** gpt ****？**

| 我写了另一篇详细的教程，同样的无敌实操帖，很多朋友点赞好评： |
| --- |

[**简单！小白**](https://vw33bncyqrt.feishu.cn/docx/PfymdoumHoaBYUxyLyycjTpznqc) **0**** 代码搭微信 ****chatgpt**** ，无敌图文教程！**X

有疑问评论一下，我看到回复，或者大家讨论~

欢迎一起来探索，有好玩的ai社群 求带~~~
