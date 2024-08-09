# ACBot

ACBot 是一个为洛谷平台设计的全自动刷题工具。通过模拟浏览器操作，ACBot 可以自动登录洛谷、从题解中提取代码、提交代码，并自动处理反作弊措施。它还具备验证功能，确保数据的安全性与完整性。

## 功能

- **自动登录洛谷**: 使用现有的登录信息自动登录洛谷，并在需要时自动重新登录。
- **自动提取代码**: 从洛谷题解页面中提取代码，并进行去除注释、格式化等处理，确保代码的干净和可用。
- **自动提交代码**: 自动将提取到的代码提交到洛谷平台，并检测提交结果。
- **反调试保护**: 检测是否有调试工具或逆向工程工具在运行，保护 ACBot 不被逆向或调试。
- **数据验证**: 验证从网页提取的加密数据，确保数据的真实性。

API : [https://acbot-dev.github.io/api/](https://acbot-dev.github.io/api/)

项目主页: [https://acbot-dev.github.io/](https://acbot-dev.github.io/)

使用文档: [https://bgithub.xyz/ACBot-dev/ACBot-for-Luogu/blob/main/README.md]
