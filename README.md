# stepzen-install

This action installs the specified `version` of the StepZen CLI (defaults to latest version).

# What's new

First delivery of this action.

## Pre-requisites

Node must be installed.

## Inputs

- `version` - Version of the CLI to install

## Example

<!-- start usage -->

```yaml
- uses: stepzen-dev/stepzen-install@v1.0
  with: 
    version: 0.33.0
```

<!-- end usage -->