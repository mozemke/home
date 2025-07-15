# cert-manager - mzemke.net

secret needs to be applied manually on bootstrapping!

```yaml=
---
apiVersion: v1
kind: Secret
metadata:
  name: cloudflare-api-token-secret
type: Opaque
stringData:
  api-token: xxxxxx
```