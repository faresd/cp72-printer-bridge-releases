# Optional Cheaply Auth migration

`https://auth.cheaply.fr` is the target central OAuth/OIDC issuer for Cheaply applications.

This repository appears to publish release artifacts only. Do not add runtime OAuth code here unless an application/runtime surface is introduced. Any companion app that consumes these releases should keep Cheaply Auth optional until the new Auth service, PostgreSQL storage, Kubernetes rollout, DNS ownership, and canary checks are complete.

Do not commit secrets or log tokens, authorization codes, cookies, client secrets, kubeconfig, or provider artifacts.
