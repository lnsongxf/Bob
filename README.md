<p align="center">
  <img src="https://raw.githubusercontent.com/ripperhe/oss/master/2019/1222/bob-logo.png" width=240 />
</p>
<p align="center">
	<a href="https://github.com/ripperhe/Bob/releases/latest"><img src="https://img.shields.io/github/v/release/ripperhe/Bob?logo=github" alt="GitHub release" /></a>
	<a href="https://github.com/ripperhe/Bob/releases/latest"><img src="https://img.shields.io/github/downloads/ripperhe/Bob/total" alt="Downloads" /></a>
	<a href="https://github.com/ripperhe/Bob/releases/latest"><img src="https://img.shields.io/github/downloads/ripperhe/Bob/latest/total" alt="Downloads latest" /></a>
</p>

# Bob

Bob 是一款  Mac 端翻译软件，支持**划词翻译**和**截图翻译**，当然，手动输入进行翻译也是可以的。

## 如何安装

### 系统要求

macOS 10.12+

### 下载安装

#### Homebrew Cask 安装

```sh
brew cask install bob
```

#### 手动安装

从 [GitHub release](https://github.com/ripperhe/Bob/releases) 中下载最新的 `Bob.app.zip` 安装包，然后解压拖拽到**应用程序**文件夹即可

⚠️ 目前只在 GitHub 分发安装包，其它地址分发的都有可能存在风险，请仔细辨别

### 权限设置

<details>
<summary><strong>开启辅助功能权限</strong></summary><br>
<p>
<p>第一次使用<strong>划词翻译</strong>的时候会弹出以下提示，点击 <code>打开系统偏好设置</code>，勾选上 Bob</p>
<p><img src="https://raw.githubusercontent.com/ripperhe/oss/master/2020/0117/辅助功能弹窗.png" alt="辅助功能弹窗" width=500 /></p>
<p>如果不小心拒绝了，打开 <code>系统偏好设置-安全性与隐私-隐私-辅助功能</code>，确保勾选上了 Bob</p>
<p>如果没有弹出请求权限的弹框，则在该页面点击 <code>+</code> 号，进入应用程序文件夹选中 Bob，点击 <code>打开</code>，然后勾选上 Bob</p>
<p><img src="https://raw.githubusercontent.com/ripperhe/oss/master/2020/0117/辅助功能设置.png" alt="辅助功能设置" width=600 /></p>
</p>
</details>

<details>
<summary><strong>开启屏幕录制权限</strong>（macOS 10.15 以上才需要）</summary><br>
<p>
<p>第一次使用<strong>截图翻译</strong>的时候会弹出以下提示，点击 <code>打开系统偏好设置</code>，勾选上 Bob</p>
<p><img src="https://raw.githubusercontent.com/ripperhe/oss/master/2020/0117/屏幕录制弹窗.png" alt="屏幕录制弹窗" width=500 /></p>
<p>如果不小心拒绝了，打开 <code>系统偏好设置-安全性与隐私-隐私-屏幕录制</code>，确保勾选上了 Bob</p>
<p>如果没有弹出请求权限的弹框，则在该页面点击 <code>+</code> 号，进入应用程序文件夹选中 Bob，点击 <code>打开</code>，然后勾选上 Bob</p>
<p><img src="https://raw.githubusercontent.com/ripperhe/oss/master/2020/0117/屏幕录制设置.png" alt="屏幕录制设置" width=600 /></p>
</p>
</details>

## 使用方法

| 功能 | 描述 | 预览 |
| :---: | :---: | :---: |
| 划词翻译 | 选中需要翻译的文本之后，按下划词翻译快捷键即可（默认 `⌥ + D`） | ![划词翻译-句子](https://raw.githubusercontent.com/ripperhe/oss/master/2020/0117/划词翻译-句子.gif) |
| 截图翻译 | 按下截图翻译快捷键（默认 `⌥ + S`），截取需要翻译的区域 | ![截图翻译-句子](https://raw.githubusercontent.com/ripperhe/oss/master/2020/0117/截图翻译-句子.gif) |
| 输入翻译| 按下输入翻译快捷键（默认 `⌥ + A`），输入需要翻译的文本，`Enter` 键翻译 | ![输入翻译-单词](https://raw.githubusercontent.com/ripperhe/oss/master/2020/0117/输入翻译-单词.gif) |
| 插件翻译 | `0.3.0` 版本开始支持，选中需要翻译的文本之后，点击 [PopClip](https://pilotmoon.com/popclip/) 插件图标即可，详情见 [Bob-PopClip](https://github.com/ripperhe/Bob-PopClip) | ![插件翻译-句子](https://raw.githubusercontent.com/ripperhe/oss/master/2020/0117/插件翻译-句子.gif) |

* 划词翻译在**可以选中文本，并且可以复制**的情况下使用
* 截图翻译建议在无法选中或复制的情况下使用
* 输入翻译通常在以上方法获取的文本不准的情况下使用

## 支持的翻译源

目前 Bob 支持有道翻译、百度翻译和谷歌翻译，以下对比比较粗糙，主要根据个人的使用体验评判的，具体细节可以自行感受

| 功能 | 有道翻译 | 百度翻译 | 谷歌翻译（国内） | 谷歌翻译 |
| :---: | :---: | :---: | :---: |  :---: |
| 支持的语种数量 |  114 | 28 | 104 | 104 |
| 速度 | 快 | 一般 | 较慢 | 较慢 |
| 是否需要科学上网| 不需要 | 不需要 | 不需要 | 需要 |
| 英语音标 | ❌ | ✅ | ❌ | ❌ |
| 句子翻译 | ✅ | ✅ | ✅ | ✅ |
| 是否有 OCR 接口 | ✅ | ✅ | ❌ | ❌ |

百度翻译和谷歌翻译可以识别驼峰形式的句子，形如 "WhatAreYouDoing"。

由于谷歌翻译没有找到合适的 OCR 接口，所以在截图翻译的时候，使用有道的 OCR 接口进行识图，然后再调用谷歌的翻译接口进行翻译。

国内谷歌翻译和谷歌翻译结果完全一样，只是谷歌翻译需科学上网使用，但国内谷歌翻译不需要。

注意：如果你已经科学上网，那么国内谷歌翻译可能会无法使用。**另外，如果你的科学上网配置不当，那会导致其他翻译接口如百度、有道翻译速度明显下降，请使用 PAC 模式而不是全局模式。**

## 常见问题

<h6>划词翻译获取不到文本</h6>
<details>
<summary>划词翻译获取不到文本？</summary>
<p>
<p>首先检查一下是否开启了辅助功能权限（文章前面有开启方法），如果已开启，再检查一下所选中的文本是否可复制。划词翻译本质上就是发出 <code>⌘ + C</code> 这个组合键复制选中的文本，然后从剪切板获取文本进行翻译，所以如果文本本身没法复制，则没法获取到，此时建议使用截图翻译。</p>
<p>有些软件或者网站复制文本之后还会在文本后面追加一些信息，所以有时候翻译的文本和选中的可能有些出入。</p>
</p>
</details>

<details>
<summary>菜单栏的<strong>划词翻译</strong>选项为什么是灰色？</summary><br>
<p>因为划词翻译需要获取选中的文本，点击菜单栏图标会导致上一个软件失焦，此时就没法获取到选中的文本，所以设置为不可点击（灰色），划词翻译选项不能点击但还把它放在菜单中是为了方便查看划词翻译快捷键</p>
</details>

<details>
<summary>朗读按钮点击了没反应？</summary><br>
<p>朗读按钮点击之后，会进行网络请求获取音频播放，没有反应可能是句子太长，加载较慢，当然也有可能是 BUG，后期会考虑点击之后进行一些 UI 提示</p>
</details>

<details>
<summary>翻译报错？</summary><br>
<p>
<table>
<thead>
<tr>
<th style="text-align: center">报错描述</th>
<th style="text-align: center">可能原因</th>
<th style="text-align: center">建议方案</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center">首次使用显示「翻译中」</td>
<td style="text-align: center">开启软件后第一次使用，可能是正在获取 token，相对会更慢一些</td>
<td style="text-align: center">建议等待或重启软件</td>
</tr>
<tr>
<td style="text-align: center">总是显示「翻译中」或「请求异常」</td>
<td style="text-align: center">可能就是网络问题，或是科学上网软件导致的</td>
<td style="text-align: center">建议检查网络和科学上网软件设置</td>
</tr>
<tr>
<td style="text-align: center">「接口异常」</td>
<td style="text-align: center">可能是请求过于频繁，或者查询的文本当前翻译源不支持</td>
<td style="text-align: center">建议等下再试或者切换翻译源</td>
</tr>
<tr>
<td style="text-align: center">「数据解析异常」</td>
<td style="text-align: center">可能是相应翻译源的 API 变动或者翻译结果的极端情况软件没有覆盖到</td>
<td style="text-align: center">建议切换翻译源，上报 BUG 并等待软件更新</td>
</tr>
</tbody>
</table>
<p>当然，所有问题都可以尝试<strong>切换翻译源</strong>和<strong>重启 Bob</strong>。</p>
</p>
</details>

<details>
<summary>如何导出日志？</summary><br>
<p>点击菜单栏图标，选中 <code>帮助-导出日志</code></p>
</details>

## 开发者

<a href="https://github.com/ripperhe/Bob/graphs/contributors"><img src="https://opencollective.com/bob_/contributors.svg?width=890&button=false" /></a>

## 感谢

本仓库的灵感和部分代码来源于以下仓库

* [Selection-Translator/crx-selection-translate](https://github.com/Selection-Translator/crx-selection-translate)
* [isee15/Capture-Screen-For-Multi-Screens-On-Mac](https://github.com/isee15/Capture-Screen-For-Multi-Screens-On-Mac)

## 最后

> 由于一些原因，`0.3.0` 以后的代码暂不开源，不过依旧会持续更新，免费使用

Bob 还很年轻，可能会有各种大大小小的问题，有任何问题或者建议可以直接提 issue，或者加入 QQ 群 **971584165** 反馈~

如果想请我喝咖啡，可以微信扫描下方赞赏码哦~ 😘

[赞赏列表](RewardList.md)

<p align="center">
	<img src="https://raw.githubusercontent.com/ripperhe/oss/master/2020/0105/ripper_wechat.JPG" width=250 />
</p>