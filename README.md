# micro-wake-word-models

Custom wake word models for [ESPHome microWakeWord](https://esphome.io/components/micro_wake_word.html).

Trained using [microWakeWord-Trainer-AppleSilicon](https://github.com/skrashevich/microWakeWord-Trainer-AppleSilicon) — a one-shot training pipeline for Apple Silicon Macs.

## Models

| Wake Word | Language | File |
|-----------|----------|------|
| Нова | Russian | [models/v2/nova.json](models/v2/nova.json) |

## Usage in ESPHome

```yaml
micro_wake_word:
  model: https://raw.githubusercontent.com/zengarden-space/micro-wake-word-models/main/models/v2/nova.json
```
