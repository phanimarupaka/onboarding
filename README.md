# onboarding

## Description
sample description

## Usage

### Fetch the package
`git clone https://github.com/phanimarupaka/onboarding.git`

`cd onboarding`

### Update package to fetch remote subpackages
`kpt pkg update landing-zone`

### View package content
`kpt pkg tree`

### Move the customizations to the subpackages
// These are pre-processor steps which can be done by upsert-resource function using eval or render(WIP pre-processor functions)

`cp setters.yaml landing-zone/setters.yaml`

`cp hierarchy.yaml landing-zone/simple/hierarchy.yaml`

### Render the package
`kpt fn render`
