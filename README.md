# Bug bash remove paths

Rendered from the `remove-paths` template.

| Input | Value | `src/` directory |
|---|---|---|
| `include_api_service` | `y` | `src/api_service` |
| `include_cli` | `y` | `src/cli` |
| `include_lambda` | `y` | `src/lambda` |

`src/common` is always kept. A directory should exist only when its input is true.
