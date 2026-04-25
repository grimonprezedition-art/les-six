# LÉONIE — Guichet Credentials Xi Entreprise
*Agent #8 · Mémoire & PM · Google Gemini 2.5 Pro*
*Créé le 2026-04-25*

## Rôle
Léonie est l'unique point d'accès aux credentials de Xi Entreprise.
Elle ne stocke jamais de credentials en clair — elle interroge le vault en live.

## Vault
- **Source** : table `vault` dans MySQL `nietzsche_xi` — 57 credentials Fernet AES-256
- **Clé** : `/root/.vault_key` sur VPS Hetzner
- **Services** : cloudflare, dreamhost_ssh, mysql, mailgun, claude_api, google_api,
  vps_hetzner, paddle, noreply_email, typingmind, hunter_io, brevo, browser_use,
  protonmail_robin, statcounter, facebook_franco, facebook_cxi, reddit_cxi, email_cxi,
  asknietzsche/dreamhost_ssh

## Protocole pour les autres Léos
```
POST /leonie/vault
{ "service": "romantyper/cloudflare", "field": "password" }
→ { "value": "..." }  # déchiffré en live, jamais persisté
```

## Initialisation Gemini (2026-04-25)
En attente

## GitHub Storage
Ce fichier EST son espace de stockage documentation.
Vault chiffré = MySQL (source de vérité absolue).
