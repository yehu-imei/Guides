# Motrix Next 安装与浏览器下载接管教程（Windows 11）

本文只记录 Motrix Next 的基础安装，以及如何安装浏览器扩展、复制粘贴密钥，并让 Motrix Next 接管浏览器下载。

---

## 一、下载 Motrix Next

进入 Motrix Next 的 GitHub Releases 页面：

```text
https://github.com/AnInsomniacy/motrix-next/releases
```

Windows 11 普通电脑一般下载 x64 安装包：

```text
MotrixNext_x.x.x_x64-setup.exe
```

不要下载 ARM64 版本，除非你使用的是 Windows ARM 设备。

下载完成后，双击安装包进行安装。

---

## 二、打开 Motrix Next

安装完成后，打开 Motrix Next。

建议先确认 Motrix Next 正常运行，并保持它不要关闭。

如果你希望浏览器下载能够被 Motrix Next 接管，Motrix Next 需要处于运行状态，或者保持后台托盘运行。

---

## 三、安装浏览器扩展

如果你使用 Chrome 或 Edge，安装 Motrix Next Extension。

Chrome Web Store 地址：

```text
https://chromewebstore.google.com/detail/motrix-next-extension/ofeajdebdjajhkmcmamagokecnbephhl
```

安装完成后，浏览器右上角会出现 Motrix Next Extension 图标。

如果没有看到图标，可以点击浏览器右上角的扩展按钮，把 Motrix Next Extension 固定到工具栏。

---

## 四、复制 Motrix Next 密钥

回到 Motrix Next 软件中，进入设置页面。

找到和浏览器扩展相关的密钥，例如：

```text
扩展API密钥
```

复制这个密钥。

打开浏览器右上角的 Motrix Next Extension。

进入扩展设置页面，把刚才从 Motrix Next 里复制的密钥粘贴进去。

---

## 五、测试是否成功

打开浏览器，随便下载一个普通文件，例如 `.zip`、`.exe`、`.7z` 文件。

如果设置成功，下载任务会自动出现在 Motrix Next 中。

如果仍然是浏览器自己下载，检查下面几项：

- Motrix Next 是否正在运行
- 浏览器扩展是否已经启用
- 密钥是否复制正确
- 扩展里是否开启了下载接管
- 是否保存了扩展设置

---

## 六、启用代理

Motrix Next不会自动开启代理

如果遇到下载失败的链接，或者下载速度异常

在Motrix Next-偏好设置-网络里启用代理

如果你的系统已经开启代理，可以点击点击检测系统代理

保存并应用即可

---
## 七、推荐流程

```text
下载 MotrixNext_x.x.x_x64-setup.exe
→ 安装 Motrix Next
→ 打开 Motrix Next
→ 安装 Motrix Next Extension
→ 把密钥粘贴到浏览器扩展
→ 测试普通文件下载
→ 启用代理
```
