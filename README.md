# Emergency kit

This repo does not require frequent changes. In order to **aviod commiting any changes without encrypting the content first** do not clone the repo, just copy the encrypted content to a local file. Use:

- `ansible-vault view emergency_kit.md --vault-password-file ~/.vault_key` --- to view
- `ansible-vault decrypt emergency_kit.md --vault-password-file ~/.vault_key` --- to decrypt
- `ansible-vault encrypt --vault-pass-file ~/.vault_key emergency_kit.md` --- to encrypt

For more information about Ansible vault, watch [encrypting Files with Ansible Vault](https://www.youtube.com/watch?v=xeBnAbmt3Wk).
