Fork of https://github.com/namse/aws-cloudformation-outputs-action, updated to use Node.js 20.

# aws cloudformation outputs action

This action set AWS Cloudformation stack outputs as github action outputs.

## Inputs

### `stack-name`

**Required** The name of the AWS Cloudformation stack.

## Outputs

### `{key}`

Every key of stack outputs will be filled as github action outputs.

## Example usage

uses: namse/aws-cloudformation-outputs-action@v1.0
with:
  stack-name: 'MyCfnStackName'
