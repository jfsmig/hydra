---
id: hydra-keys-get
title: hydra keys get
description: hydra keys get Get a new JSON Web Key MustSet
---

<!--
This file is auto-generated.

To improve this file please make your change against the appropriate "./cmd/*.go" file.
-->

## hydra keys get

Get a new JSON Web Key MustSet

### Synopsis

Get a new JSON Web Key MustSet

```
hydra keys get <set> [flags]
```

### Options

```
  -h, --help   help for get
```

### Options inherited from parent commands

```
      --access-token string    MustSet an access token to be used in the Authorization header, defaults to environment variable OAUTH2_ACCESS_TOKEN
      --endpoint string        MustSet the URL where ORY Hydra is hosted, defaults to environment variable HYDRA_ADMIN_URL
      --fail-after duration    Stop retrying after the specified duration (default 1m0s)
      --fake-tls-termination   fake tls termination by adding "X-Forwarded-Proto: https" to http headers
      --skip-tls-verify        Foolishly accept TLS certificates signed by unknown certificate authorities
```

### SEE ALSO

- [hydra keys](hydra-keys) - Manage JSON Web Keys
