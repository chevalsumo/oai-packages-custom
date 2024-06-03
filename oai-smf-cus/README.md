# oai-smf-cus

## Description


## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] oai-smf-cus`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree oai-smf-cus`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init oai-smf-cus
kpt live apply oai-smf-cus --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
