# 贴吧签到Github Action版

## 今日签到状态

![Baidu Tieba Auto Sign](https://github.com/gwtak/TieBaSign/workflows/Baidu%20Tieba%20Auto%20Sign/badge.svg)

## 使用说明

1. Fork 本仓库，然后点击你的仓库右上角的 Settings，找到 Secrets 这一项，添加一个库秘密变量。

- 1.1 `BDUSS` 存放你的 BDUSS。支持同时添加多个帐户，BDUSS 之间用 `#` 隔开即可
- 1.2 `MAIL_USERNAME` 存放163邮箱地址
- 1.3 `MAIL_PASSWORD` 存放163邮箱授权密码
- 1.4 `MAIL_TARGET` 存放收件邮箱
- 1.5 `ENC_KEY` 存放加密签到报告的密钥，用于保护一些隐私信息

![添加库秘密变量](/img/new_repository_secret.png)
![添加BDUSS](/img/add_BDUSS.png)

2. 设置好环境变量后点击你的仓库上方的 `Actions` 选项，第一次打开需要点击 `I understand...` 按钮，确认在 Fork 的仓库上启用 GitHub Actions 。

3. 手动触发一次GitHub Action以及时测试

4. 至此自动签到就搭建完毕了，可以再次点击`Actions`查看工作记录，如果有`Baidu Tieba Auto Sign`则说明workflow创建成功了。点击右侧记录可以查看详细签到情况。

![查看Action](/img/check.png)



