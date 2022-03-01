# GiHhub Demos

Collection of my GitHub demos

## GitHub Actions

[Example workflows](https://github.com/JanneMattila/github-actions-demos/tree/main/.github/workflows)

- artifacts
- azure-api-management
- environments
- external
- federated-identity
- issues-opened
- manual
- numbers
- outputs
- release
- secrets

## GitHub Advanced Security

### Code scanning

[javascript](https://github.com/JanneMattila/code-scanning-javascript-demo/security/code-scanning)

[java](https://github.com/jannemattilaorgdemo/advanced-security-java-webgoat/security/code-scanning)

### Dependabot

Alerts

[java](https://github.com/jannemattilaorgdemo/advanced-security-java-webgoat/security/dependabot)

Pull request

[java](https://github.com/jannemattilaorgdemo/advanced-security-java-webgoat/pulls)

### Secrets scanning

`Janne Token`: 

- Pattern: `janne_token_[0-9]{5}`
- Before: `"`
- After: `"`

Test strings:

```
"janne_token_12345"
janne_token_22
janne_token_aaaabbbbxxx
```

First one matches: `"janne_token_12345"`.

Organization view:

[Security](https://github.com/orgs/jannemattilaorgdemo/security)

Secret scanning:

[Google API Key](https://github.com/jannemattilaorgdemo/openhack-devops-nov-2021/security/secret-scanning/1)

