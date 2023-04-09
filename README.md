# Relevant Info

## Commit
https://github.com/RahulGautamSingh/renovate/tree/feat/npm-workspaces dcab282

## Logs

The logs are for the PR: https://github.com/RahulGautamSingh-testing/example-test/pull/10

### New Log
```log
DEBUG: Generating package-lock.json for . (repository=RahulGautamSingh-testing/example-test, branch=renovate/workspace-test)
DEBUG: Spawning npm install to create ./package-lock.json (repository=RahulGautamSingh-testing/example-test, branch=..)
...
DEBUG: Performing lockfileUpdate (npm-workspaces) (repository=RahulGautamSingh-testing/example-test, branch=renovate/work..)
DEBUG: Performing lockfileUpdate (npm) (repository=RahulGautamSingh-testing/example-test, branch=renovate/workspace-test)
...
DEBUG: Executing command (repository=RahulGautamSingh-testing/example-test, branch=renovate/workspace-test)
       "command": "npm install --package-lock-only --no-audit --ignore-scripts --workspace=b @types/react-dom@18.0.11 abbrev@1.1.1"
...
DEBUG: Executing command (repository=RahulGautamSingh-testing/example-test, branch=renovate/workspace-test)
       "command": "npm install --package-lock-only --no-audit --ignore-scripts --workspace=a @types/react-dom@18.0.11 nodemon@1.19.4"
...
DEBUG: Executing command (repository=RahulGautamSingh-testing/example-test, branch=renovate/workspace-test)
       "command": "npm install --package-lock-only --no-audit --ignore-scripts chalk@1.1.3 xmldoc@1.3.0"
```

### Old Log

```log
DEBUG: Generating package-lock.json for . (repository=RahulGautamSingh-testing/example-test, branch=renovate/something-groupy)
DEBUG: Spawning npm install to create ./package-lock.json (repository=RahulGautamSingh-testing/example-test, branch=renovate/...)
...
DEBUG: Performing lockfileUpdate (npm) (repository=RahulGautamSingh-testing/example-test, branch=renovate/something-groupy)
...
DEBUG: Executing command (repository=RahulGautamSingh-testing/example-test, branch=renovate/something-groupy)
       "command": "npm install --package-lock-only --no-audit --ignore-scripts @types/react-dom@18.0.11 @types/react-dom@18.0.11 abbrev@1.1.1 
       chalk@1.1.3 nodemon@1.19.4 xmldoc@1.3.0 xmldoc@1.3.0 xmldoc@1.3.0"
```
