# mydemo

## Description
demo

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] mydemo`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree mydemo`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init mydemo
kpt live apply mydemo --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
