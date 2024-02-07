# stepzen-install

This action installs the specified `version` of the StepZen CLI (defaults to latest version).

The `stepzen` CLI supports:
 * IBM API Connect Essentials Software
   * https://www.ibm.com/docs/en/api-connect/ace/1.x?topic=getting-started-api-connect-essentials
 * IBM StepZen Graph Server (SaaS)
   * https://www.ibm.com/docs/en/stepzen
 * StepZen original SaaS
   * https://www.stepzen.com

# What's new

First delivery of this action.

## Pre-requisites

Node must be installed.

## Inputs

- `version` - Version of the CLI to install

## Example

### Latest version

<!-- start usage -->

```yaml
- uses: stepzen-dev/stepzen-install@v1
```

<!-- end usage -->

### Specific version
<!-- start usage -->

```yaml
- uses: stepzen-dev/stepzen-install@v1
  with: 
    version: 0.33.0
```
<!-- end usage -->
