# keycloak-k8s

### 1. Seal secrets
```bash
kubeseal --cert pub-sealed-secrets.pem --format yaml < keycloak-db-secret.secret.yaml > sealed-keycloak-db-secret.yaml
```