# 自由屏幕旋转

![Eclipse Marketplace](https://img.shields.io/badge/license-AGPL3.0-blue)
![Eclipse Marketplace](https://img.shields.io/badge/version-v1.0-green)
[![Telegram](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram)](https://t.me/XiaofangInternet)

解除 APP 对屏幕旋转的控制，针对所有 Android Pad 设计，拒绝强制竖屏从我做起。

## Developer

[酷安 @星夜不荟](http://www.coolapk.com/u/876977)

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

## 捐赠支持

- 工作不易，无意外情况此项目将继续维护下去，提供更多可能，欢迎打赏。<br/><br/>
  <img src="https://github.com/fankes/YuKiHookAPI/blob/master/img-src/wechat_code.jpg" width = "200" height = "200"/>

## 贡献

本模块使用 [YukiHookAPI](https://github.com/fankes/YukiHookAPI) 构建

YukiHookAPI 是一个使用 Kotlin 重构的高效 Hook API 构建工具，让你的 Xposed 模块开发变得更加简单。

版权所有 © 2019-2022 Fankes Studio(qzmmcn@163.com)
