
</div>

<div align="center">

![:name](https://count.getloli.com/@InitiativeDialogue?name=InitiativeDialogue&theme=minecraft&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto)

</div>

# 伪造转发消息插件

一个用于AstrBot的插件，可以创建包含多个用户发言的伪造转发消息，支持自动获取QQ昵称。

## 功能特点

- 创建多用户的转发消息
- 自动获取QQ用户的真实昵称
- 简单的命令格式，易于使用
- 高度自定义的消息内容

## 使用方法

### 基本格式

```
伪造消息 QQ号 内容 | QQ号 内容 | ...
```

每个消息节点格式为：`QQ号 内容`，节点之间用 `|` 符号分隔。

### 示例

```
伪造消息 123456789 你好，这是第一条消息 | 987654321 这是第二条消息回复 | 123456789 谢谢你的回复！ |
```

这将创建一个包含3个消息节点的转发消息，自动获取QQ号对应的昵称。

## 工作原理

1. 插件监听所有包含"伪造消息"的消息
2. 解析消息格式，提取QQ号和内容
3. 通过API获取真实昵称
4. 创建转发消息节点
5. 发送合并后的转发消息

## 作者

- Jason.Joestar

## 免责声明

本插件仅供学习和技术研究使用。使用者应当遵守相关法律法规，不得用于非法用途。使用本插件进行的任何行为及其后果，包括但不限于冒充他人、传播虚假信息等，均与插件作者无关。作者不对因使用本插件而产生的任何直接或间接损失负责。

使用本插件即表示您已阅读并同意此免责声明。

## 许可证

MIT
