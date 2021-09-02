Python Tutor -- http://pythontutor.com/ -- 帮助人们克服学习编程的基本障碍: 理解当计算机执行程序源代码的每一行时会发生什么。 使用这个工具，你可以在你的Web浏览器中写Python, Java,
JavaScript, TypeScript, Ruby, C, 和 C++ 程序。并可视化计算机在执行这些程序时逐步执行的操作。

该工具由 [Philip Guo](http://pgbovine.net/) 于 2010 年 1 月创建。 [查看项目历史](history.txt).

[不支持的功能和已知错误列表](./unsupported-features.md)

代码的最新开发版本在 [v5-unity](v5-unity/) , 尽管许多遗留文档仍然存在于 [v3](v3/) .

### 快速开始

```bash
pip install bottle # 确保 bottle webserver (http://bottlepy.org/) 已安装

cd OnlinePythonTutor/v5-unity/
# 启动服务
python bottle_server.py
```

你应该在以下位置看到可视化工具: http://localhost:8003/visualize.html

并且在线编程环境在: http://localhost:8003/live.html 

但是，很难在本地为非 Python 语言运行自己的可视化工具，因为 v4-cokapi 中存在复杂的依赖项，原作者还没有完全打包。
默认情况下，你运行的本地版本将调用原作者自己的服务器来运行非 Python 后端，因此请注意你的带宽使用情况。

更多说明请见原 [英文文档](README_en.md) 

