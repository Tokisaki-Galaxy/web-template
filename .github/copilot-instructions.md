## Copilot Agent 运行环境说明
 - **预装工具**：
    - `jq` (JSON 处理)
    - `xvfb` (虚拟显示)
    - `tree` (查看目录结构)
    - `ripgrep` (高性能文本搜索)
    - **Playwright (Chromium)**：优先用于验证渲染、执行 E2E 测试或查看动态内容。
 - **代码校验与格式化**：
    - 环境已通过 `tsc` 类型检查和 `eslint` 代码检查。
    - **Prettier**：在提交或运行测试前，可以使用 `npx prettier --write .` 修复格式。
 - **构建与测试验证**：
    - 在完成功能开发后，运行 `npx tsc -b` 和 `npm run lint`。
    - **Vitest**：若需要单元测试请使用 `npx vitest` 或 `npm test`。

## 示例Live2D模型
如果测试Live2D模型，请使用`https://cdn.jsdelivr.net/gh/guansss/pixi-live2d-display/test/assets/haru/haru_greeter_t03.model3.json`
