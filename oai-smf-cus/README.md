<<<<<<< HEAD
# oai-smf package

## Description

## Usage

### Fetch the package
`kpt pkg get https://gitlab.eurecom.fr/nephio/oai-packages/nf-deploy-packages/oai-smf@main`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree oai-smf`
=======
# oai-smf-cus

## Description


## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] oai-smf-cus`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree oai-smf-cus`
>>>>>>> 8e8a6885c67bf631b644135b1480189ad9a2c303
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
<<<<<<< HEAD
kpt live init oai-smf
kpt live apply oai-smf --reconcile-timeout=2m --output=table
=======
kpt live init oai-smf-cus
kpt live apply oai-smf-cus --reconcile-timeout=2m --output=table
>>>>>>> 8e8a6885c67bf631b644135b1480189ad9a2c303
```
Details: https://kpt.dev/reference/cli/live/
