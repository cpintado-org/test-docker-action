# docker action in sub directory

This is an example of a public Docker container action defined in a sub directory of a repository. In order to use this action from another workflow, it has to be reference like this:

```
jobs:
  job1:
    runs-on: ubuntu-latest
    steps:
    - uses: cpintado-org/test-docker-action/subdir@2.0
```

