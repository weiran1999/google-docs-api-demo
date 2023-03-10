# Introduce
- 关于`google docs api`的实践。mvc架构里主要调试的是关于`google docs`，也有一个关于`google sheets`的demo。
- resource目录下的service_account_key.json 和 credentials.json 文件都需要在自己的google云账户里获取。具体网址：[创建和管理服务账号密钥](https://cloud.google.com/iam/docs/creating-managing-service-account-keys?hl=zh-cn)
- 目前demo关于`sheets`的功能，需要先运行 `SheetsQuickStart`后，在`/tokens`之下生成`StoredCredential`文件之后，才能使用对应的Web功能。

# Reference
- [使用 Android 登录功能](https://developers.google.com/identity/sign-in/android/start?hl=zh-cn)
- [Web 授权](https://developers.google.com/identity/oauth2/web/guides/overview?hl=zh-cn)
- [JavaScript quickstart](https://developers.google.com/sheets/api/quickstart/js#api-key)
- [google docs get接口](https://developers.google.com/sheets/api/reference/rest/v4/spreadsheets.values/batchGet)
- [使用 OAuth 2.0 访问 Google API ](https://developers.google.com/identity/protocols/oauth2?hl=zh-cn)
