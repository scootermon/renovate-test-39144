# Test for https://github.com/renovatebot/renovate/pull/39144

```bash
export RENOVATE_TOKEN=$(gh auth token)
export RENOVATE_CONFIG_FILE_NAMES='["my-cool-renovate.json5"]'
export RENOVATE_ONBOARDING_CONFIG_FILE_NAME='my-cool-renovate.json5'

npm run start -- scootermon/renovate-test-39144
```
