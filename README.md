# 青鹭美育智能体｜GitHub Pages 发布包

本文件夹可直接作为 GitHub Pages 仓库内容：

- `index.html`：网站首页
- `app.html`：青鹭美育智能体演示界面
- `assets/`：网页与智能体所需图片资源
- 演示视频：单独上传到 GitHub Release，不放入普通仓库

## 发布步骤

1. 在 GitHub 新建一个公开仓库，例如 `qinglu-aesthetic-agent`。
2. 把本文件夹中的全部内容上传到仓库默认分支的根目录。
3. 在仓库的 Releases 页面创建 `v1.0`，上传以下视频：

   `../assets/video/qinglu-aesthetic-education-agent-demo.mp4`

4. 本发布包已配置为 GitHub 用户 `zhangjian8911` 和仓库 `qinglu-aesthetic-agent`，无需再次修改视频地址。
5. 在仓库 `Settings → Pages` 中，将发布来源设为默认分支根目录，保存后等待部署完成。

发布网址通常为：

`https://zhangjian8911.github.io/qinglu-aesthetic-agent/`

## 说明

- 页面为静态演示站，无需注册即可浏览。
- 智能体中的演示数据保存在访问者自己的浏览器中，不会形成多人共享的在线数据库。
- 若需要真实账号、云端数据库或跨设备同步，需要后续接入服务器与数据库服务。
