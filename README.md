# open_locale
自动进行Apple  Store Connect 国际化处理的 Python 脚本

# .env 文件配置

```
OPENAI_API_KEY = "这是你的 openai 的 api key"
KEY_ID = "用管理员账号在 apple connect 里面申请的"
ISSUER_ID = "用管理员账号在 apple connect 里面申请的"
KEY_FILE = "用管理员账号在 apple connect 里面申请的p8文件的本地路径"
BUNDLE_ID = "你 App 的 bundle id ，在 connect 里面可以查看"
```
要想执行，还是需要点 Python 最基础的知识，放在 notebook 里面执行。

# 实现功能

1. 连接 openai 自动翻译你 App 支持的商店语言
2. 翻译结果自动上传到特定 locale 的项目下面
