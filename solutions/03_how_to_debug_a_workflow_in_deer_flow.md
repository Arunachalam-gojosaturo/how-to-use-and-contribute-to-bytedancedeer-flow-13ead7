# How to debug a workflow in deer-flow

_Use logging and the deer-flow debugger to identify issues_

## Steps

1. Enable debug logging using `deer-flow start --log-level=DEBUG`
2. Run the workflow using `deer-flow run <workflow_name>`
3. Use the deer-flow debugger to step through the workflow using `deer-flow debug <workflow_name>`
4. Inspect the workflow execution log using `deer-flow logs <workflow_name>`
5. Use a Python debugger like pdb to step through the code

## Pitfalls

- ⚠️ Not checking the workflow configuration for typos or incorrect settings