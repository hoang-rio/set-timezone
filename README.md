# Set Action Timezone Action

This action sets timezone in your runner's locale based on its OS.

## Inputs

| Input name      | Description                                                   | Required ? | Default value |
| --------------- | ------------------------------------------------------------- | ---------- | ------------- |
| timezoneLinux   | Timezone you want to set if your runner is running on Linux   | false      | `UTC`         |
| timezoneWindows | Timezone you want to set if your runner is running on Windows | false      | `UTC`         |
| timezoneMacos   | Timezone you want to set if your runner is running on MacOS   | false      | `GMT`         |

## Example usage

```yaml
uses: hoang-rio/set-timezone@v1.4
with:
  timezoneLinux: "Asia/Singapore"
  timezoneMacos: "Asia/Singapore"
  timezoneWindows: "Singapore Standard Time"
```
