# 使用代理软件加速鹅鸭杀

经过测试，游戏对局内的服务器IP是可以直连的，并且延迟很低。而无法登陆的原因是部分steam API和账号认证相关的IP被墙。
因此只需要代理这部分的IP即可。

# 使用方法

## Win
### Netch
使用[netchx/netch](https://github.com/netchx/netch)，导入规则文件*ggd.json*到安装目录下的`mode\Custom`。

### CFW TUN 模式
将`cfw.yaml`粘贴到`Setting->Profiles->Parsers`里面然后更新订阅。之后打开TUN Mode。

## MAC
### Clash For Windows TUN 模式
同 Windows 配置

### Quantumult X
在分流里面引用规则。

