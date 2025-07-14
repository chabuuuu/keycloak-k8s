# keycloak-k8s

### 1. Seal secrets
```bash
kubeseal --cert pub-sealed-secrets.pem --format yaml < keycloak-secret.hide.yaml > sealed-keycloak-secret.yaml
```