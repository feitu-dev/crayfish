
<h1 align="center">
  <br>
  Crayfish
  <br>
</h1>

<h4 align="center">一款力图实现更优美、更快速、更全面的渗透测试信息收集工具。</h4>

<p align="center">
<img alt="GitHub all releases" src="https://img.shields.io/github/downloads/feitu-dev/crayfish/total?style=for-the-badge">
<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/feitu-dev/crayfish?style=for-the-badge">
</p>

<p align="center">
  <a href="#开始">开始</a> •
  <a href="#特色">特色</a> •
  <a href="#使用">使用</a> •
  <a href="#声明">声明</a> •
  <a href="#反馈">反馈</a> •
  <a href="#协议">协议</a>
</p>

---

### 开始

`Crayfish`简单易用，你可以通过下载[Releases版本]("https://github.com/feitu-dev/crayfish/releases")中对应的操作系统执行文件来运行它。

**Notes:**
- 通常情况下你使用它不需要任何的命令行参数。
- 在如`Linux`、`Mac OS`等操作系统上，它可能需要赋予执行权限。
- 我们正在逐渐构建与测试不同的操作系统支持。


### 特色

> 随Releases版本发布更新已实现功能。


* 子域名收集
    - 子域名枚举
    - 第三方接口收集
      * Bing
    - WebServer识别
    - 端口探活
    - 标题提取
    - DNS解析
    - CDN识别
    - 中间件识别



### 使用

1. 配置文件
   1. `Crayfish`依赖的配置是存放在同目录下的`config.toml`文件。它的主要作用是存放第三方接口(选填)。默认的配置文件格式如下:
    ```toml
   Bing = ''
    Chinaz = ''
    Zoomeye = ''
    Github = ''
    Threatbook = ''
    Shodan = ''
    Censys = ''
   ```
   2. 如果你想要使用第三方接口，你可以在配置文件中添加相应的配置项。对已经支持的第三方服务列表会在下方更新:
      1. `Bing`
   3. 也可以点击`Crayfish`底部右侧的`配置`按钮，会在当前执行目录下生成`config-example.toml`文件，并且提示你配置文件的路径(要使用这个文件还需重命名为`config.toml`才可生效)，如图:
      ![生成默认配置文件](https://github.com/feitu-dev/crayfish/blob/main/images/generate.png "生成默认配置文件")


### 声明

* 使用`Crayfish`的前提是用于安全测试及学习目的，严禁未授权的、非法的对目标进行攻击。
* `Crayfish`不允许针对任何国家的政府、教育机构、研究机构等受保护的组织进行使用。

### 反馈

#### 提交Issues

* 提交Issues可以帮助我们改进`Crayfish`。

#### 微信

* `feitu-dev`

#### 邮箱

* 如果有对`Crayfish`功能上的改进建议，请邮件联系`feitu-dev#outlook.com`


#### 鸣谢
> 没有这些优秀的项目，`Crayfish`就无法诞生。

- [httpx](https://github.com/projectdiscovery/httpx)
- [naabu](https://github.com/projectdiscovery/naabu)
- [protobuf](https://github.com/golang/protobuf)
- ...


## 协议

以免损害他人的利益，我们将不会提供任何的软件许可协议。但需注意如下几点:

- 你可以自由复制、分发本软件，但不能以任何理由、任何形式对它进行任何修改。
- 你必须保证在使用本软件时遵守所有的法律法规。
