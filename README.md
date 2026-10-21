# github-actions-practice

实验三：GitHub Actions 自动化测试与 GitHub Pages 自动部署。

## 内容

- Python 单元测试示例：`calculator.py` 和 `test_calculator.py`
- 自动化测试工作流：`.github/workflows/ci.yml`
- MkDocs 文档站点：`docs/` 和 `mkdocs.yml`
- GitHub Pages 部署工作流：`.github/workflows/deploy.yml`

## 本地验证

```bash
pip install -r requirements.txt
pytest -v
mkdocs build
```
