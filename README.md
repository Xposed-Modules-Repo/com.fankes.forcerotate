# 自由屏幕旋转

![Eclipse Marketplace](https://img.shields.io/badge/license-AGPL3.0-blue)
![Eclipse Marketplace](https://img.shields.io/badge/version-v1.1-green)
[![Telegram](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram)](https://t.me/XiaofangInternet)

解除 APP 对屏幕旋转的控制，针对所有 Android Pad 设计，拒绝强制竖屏从我做起。

## 作用域说明

- 只需勾选你需要生效的 APP 即可

- 建议不要勾选系统应用以免发生异常

- 模块已对关键系统应用设置了黑名单，勾选也不会生效

## 作用域贡献

- Fork 项目后 [前往这里](https://github.com/Xposed-Modules-Repo/com.fankes.forcerotate/blob/main/SCOPE) 贡献作用域。

- 部分 APP 旋转屏幕后会出现严重 BUG，此类 APP 不建议加入作用域，例如乐色 `*东`、`*宝`。

> 目前已添加

- QQ(标准版)
- TIM
- 微信
- 哔哩哔哩
- 哔哩哔哩 HD
- 酷安
- 网易云音乐
- 讯飞输入法
- 支付宝
- TapTap
- 百度输入法
- 抖音

## 适配说明

- 只支持 LSPosed，请不要在其它管理器上激活模块，否则会不生效

- 理论最低 Android 版本没有限制，但是 LSPosed 最低支持到 Android 8.0

- 模块只会对自带强制竖屏、强制横屏设置的 APP 生效，不会破坏自适应和跟随系统自动旋转屏幕的 APP

- 某些国产定制的 Pad 系统可与系统的 `全局横屏` 和 `平行视界` 配合使用更加

- 在手机上也可以使用，可以让横屏显示的 APP 强制竖屏，但是可能会破坏感应旋转，不建议使用

## 请勿用于非法用途

<h3>1.&nbsp本软件免费、由兴趣使然、仅供学习交流而开发，如果你是从其他不明来源的渠道付费得到本软件，则你已上当受骗，若发现欢迎向我们举报。</h3>

<h3>2.&nbsp未经本人许可，禁止转载、搬运本软件的安装包及源代码到 GitHub 以外的平台并提供下载链接。</h3>

## 项目推广

<!--suppress HtmlDeprecatedAttribute -->
<div align="center">
    <h2>嘿，还请君留步！👋</h2>
    <h3>这里有 Android 开发工具、UI 设计、Gradle 插件、Xposed 模块和实用软件等相关项目。</h3>
    <h3>如果下方的项目能为你提供帮助，不妨为我点个 star 吧！</h3>
    <h3>所有项目免费、开源，遵循对应开源许可协议。</h3>
    <h1><a href="https://github.com/fankes/fankes/blob/main/project-promote/README-zh-CN.md">→ 查看更多关于我的项目，请点击这里 ←</a></h1>
</div>

## 贡献

本模块使用 [YukiHookAPI](https://github.com/fankes/YukiHookAPI) 构建

YukiHookAPI 是一个使用 Kotlin 重构的高效 Hook API 构建工具，让你的 Xposed 模块开发变得更加简单。

版权所有 © 2019-2022 Fankes Studio(qzmmcn@163.com)
