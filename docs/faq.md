---
id: faq
title: FAQ
---
以下整理社区中反馈常见问题和官方答复，在提问之前建议找找有没有类似的问题。
### 验证主机时我输入的密码安全吗？
安全，你输入的密码仅用于当次建立密钥登录使用，并不会存储在任何地方或用于他处。
### 我不需要监控中心的功能，可以不启动 runmonitor 服务吗？
可以，包括任务计划模块，如果你不需要这个功能，也不必启动 runscheduler 服务。
### 我必须要关注公众号才可以使用内置的报警服务吗？
是的，我们为了不便二次开发的用户提供了内置的报警服务，为了方便管理服务不会被恶意使用需要你配置调用凭证来使用内置的报警服务，在必要的情况下我们可以通过禁用某些凭证来确保服务免遭破坏。
### 内置的报警服务为什么不开源直接放在项目内呢？
因为不管是微信/邮件/短信都需要配置一些敏感信息才可以使用，例如微信的 `APP_ID` 邮件服务的账户密码等，所以暂无法开源。
另外我们也在系统设置的报警服务设置中提供了自定义邮件服务的相关配置，以便你使用自己的邮件服务。



