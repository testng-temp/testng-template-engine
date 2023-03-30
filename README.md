# 简介
本工具可以快速生成接口自动化代码框架，降低编写测试用例重复代码的工作量，提高接口自动化的实现效率，使 QA更关注传参和断言部分。

# 目标对象
适合从 0~1 的开始构建接口自动化用例的用户

# 使用说明
- 使用前先在根目录下创建 output 文件夹，用于生成的代码存放
- 代码模版文件放置于 resources 文件夹 （一般不需要更改）
- 使用前请先：
  - 对 src/main/resources/config.properties 文件进行定制配置。
  - 在 枚举BossUser中新增对应领域测试账号，以供接口 Api进行使用。
  - 