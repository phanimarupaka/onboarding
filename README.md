# onboarding

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] onboarding`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree onboarding`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init onboarding
kpt live apply onboarding --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
