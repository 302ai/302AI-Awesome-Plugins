# NextChat-Awesome-Plugins

这个项目存储了302AI的插件

## Design
1. config plugin, like GPTs  action (openapi schema + authentication).
2. wrap API to `javascript` function,  then using [function-calling](https://platform.openai.com/docs/guides/function-calling)`
![image](https://github.com/user-attachments/assets/b7cfc13b-e9e8-46c0-bee5-4fa71e51bfff)


## Plugins

| 插件名 | 认证 | 描述 |
| ---- | --- | ----------------------------- |
| [ArxivSearch](./plugins/arxivsearch) | 自动验证 | 运行 Arxiv 搜索并获取文章信息 |
| [Calculator](./plugins/calculator) | 自动验证 | 获取数学表达式的结果 |
| [CodeInterpreter](./plugins/code-interpreter) | 自动验证 | 一个执行代码的工具。支持 Python 和 NodeJS 代码执行。 |
| [Dalle3](./plugins/dalle3) | 自动验证 | 调用Dalle3生成图片 |
| [ImageRecognition](./plugins/image-recognition) | 自动验证 | 分析并理解图像内容 |
| [Search](./plugins/search) | 自动验证 | 使用各种搜索引擎搜索信息并返回格式化结果 |
| [WikipediaQuery](./plugins/wikipedia-query) | 自动验证 | 使用各种搜索引擎搜索信息并返回格式化结果 |
