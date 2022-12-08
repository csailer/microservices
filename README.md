# Micoroservices


## HCI Vault

Install Vault

Start Vault in dev mode:
```
 > vault server -dev

 > You may need to set the following environment variables:

   $ export VAULT_ADDR='http://127.0.0.1:8200'

The unseal key and root token are displayed below in case you want to
seal/unseal the Vault or re-authenticate.

Unseal Key: PLV0OXO9VmF5VB8qAnq4pQIGzWkzzYypRNcDtrhSSgU=
Root Token: hvs.6j4cuewowBGit65rheNoceI7

Development mode should NOT be used in production installations!
```

Set these envs:

```
export VAULT_ADDR='<server:port> SEE ABOVE OUTPUT'
export VAULT_DEV_ROOT_TOKEN_ID=<root token issued by Vault when installed using -dev>
```