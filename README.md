# 自动化的Github组织（和团队）邀请函

> 快速部署一个网页，让人们点击并接受邀请加入你的Github组织和一个（可选）默认团队。

<p align="center">
  <img src="auto-invites-example-ui.png"/>
</p>

### 特点

* 验证提交的Github用户名
* 在您的Github组织的头像/图像中的链接
* 轻量级
* 可选择自动邀请组织内的一个团队

### 现在就获取它

[![部署](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

你所要做的就是

1. 点击**上面的按钮部署到Heroku**。
2. 在提示时填写**环境变量**。

- 包含一个*[Github Access Token](https://github.com/blog/1509-personal-api-tokens)*（它应该启用组织权限）
- 以及一个*GitHub组织名称*，
- 可以选择*背景颜色*。可选项是 `{blue,green,grey,pink,red,white}` 。如果你留空，它默认为'白色'。最后，如果你想让你的用户自动加入一个默认的团队，还可以指定一个可选的*GitHub组织团队*。

#### 全部完成! 只要把Heroku应用程序的URL分享给别人，他们就能得到你的组织的邀请。
### Development

**Install:** 

```
bundle install
```

**Run Locally:**

```bash
ORGANIZATION_NAME="foo" GITHUB_TOKEN="bar"  bundle exec ruby web_app.rb
```

### Credit 

### 感谢

感谢*[Code, Applied To Life](https://medium.com/code-applied-to-life/automated-github-organization-invites-3e940aa27040#.sikfvzyaj)*的努力，他们的努力被用作本文的基础。

以及 [FernandaOchoa](https://github.com/FernandaOchoa/automated-github-organization-invites) 对本应用的修复工作。

通过www.DeepL.com/Translator（免费版）翻译
