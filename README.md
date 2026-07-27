# Markeep 的 Scoop Bucket

用命令行安装 [Markeep](https://markeep.pages.dev) —— 不改你文件的 Markdown 编辑器。

```powershell
scoop bucket add markeep https://github.com/plum-221/scoop-markeep
scoop install markeep
```

更新：

```powershell
scoop update markeep
```

## 为什么用这个装

Markeep 的安装包**没有做代码签名**，从浏览器下载时 Chrome / Edge 会弹
「通常不会下载 xxx.exe」——那是「不常下载」提示，说的是下载量少，不是文件有毒。

从 Scoop 装**不经过浏览器**，没有这个提示，而且 Scoop 会核对 SHA256。

## 这里有什么

只有一个 manifest，指向 [markeep-releases](https://github.com/plum-221/markeep-releases)
上的官方安装包。不含任何源代码，也不重新打包——装到的和官网下载的是同一个文件。

## 许可

Markeep 是**免费软件，但不是开源软件**。Copyright © 2026 plum-221，保留所有权利。
详见安装程序中的许可协议。
