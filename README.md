# Learn Action

## Events

```yaml
on: [push,workflow_dispatch]

```

activity types

```yaml
on:
    pull_request:
        types: [opened, reopened]

```

Filters:

```yaml
on:
    pull_request:
        types:
            - opened
        branches:
            - 'releases/**'
```
