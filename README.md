# action-os-info

get OS info for GitHub Actions

## How to use

```yaml
steps:
  - id: os-info
    uses: openameba/action-os-info@v1
  - run: echo '${{ steps.os-info.outputs.version }}'
```
