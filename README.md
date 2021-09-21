# onboarding

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get https://github.com/phanimarupaka/onboarding.git`

`cd onboarding`

### View package content
`kpt pkg tree`

### Move the customizations to the subpackages
// These are pre-processor steps which can be done by upsert-resource function using eval or render(WIP pre-processor functions)
`cp setters.yaml landing-zone/setters.yaml`
`cp hierarchy.yaml landing-zone/simple/hierarchy.yaml`

### Render the package
`kpt fn render`
