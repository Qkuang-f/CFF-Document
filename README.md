# CFF-Document

ChenFengFramework Document。

GitHub自动部署page步骤

1. `cd`到`src`目录
2. cmd执行命令`docfx docfx.json`
3. 把生成的`_site`文件夹内容，copy到`[root]/docs/`下。
   1. 注`[root]/docs`为GitHub自动部署pages文件夹。
4. git推送到GitHub。
