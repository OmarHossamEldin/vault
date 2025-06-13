# Vault
>  Self-Hosted & At Your Fingertips

- Vault — deployed securely on your infrastructure, - behind your own domain, and accessible only to you.
## Quick Start

Once running:


```
export VAULT_ADDR=http://127.0.0.1:8200

vault operator init
vault operator unseal <key1>
vault operator unseal <key2>
vault operator unseal <key3>
vault login <root-token>
```