# github-actions-practice

开源软件设计与分析课程实验二 · 实践项目 1：使用 GitHub Actions 实现自动化测试。

- `calculator.py`：被测试的计算器实现（add / multiply）
- `test_calculator.py`：pytest 单元测试（4 个断言）
- `.github/workflows/ci.yml`：Python 单元测试工作流，push / pull_request 触发

工作流在 Ubuntu 最新版 runner 上检出代码、配置 Python 3.11、安装 pytest 并执行 `pytest -v`。
