<p align="center">
  <a href="https://vaulted.fyi">
    <img src="https://raw.githubusercontent.com/vaulted-fyi/.github/main/profile/banner.svg" alt="Vaulted" />
  </a>
</p>

<p align="center">
  Share secrets that self-destruct. End-to-end encrypted, zero-knowledge.
</p>

<p align="center">
  <a href="https://vaulted.fyi"><strong>Website</strong></a> ·
  <a href="https://github.com/vaulted-fyi/vaulted">Web App</a> ·
  <a href="https://github.com/marketplace/actions/vaulted-share-secret">GitHub Action</a> ·
  <a href="https://www.npmjs.com/package/vaulted-cli">CLI</a>
</p>

---

### How It Works

Encrypt text, set view limits and expiration, share via a secure link. The recipient opens the link, sees the secret, and the link self-destructs.

The encryption key lives in the URL fragment (`#`), which browsers never send to servers. **The server never sees your plaintext or keys.**

### Repos

| Repo | Description |
|------|-------------|
| [vaulted](https://github.com/vaulted-fyi/vaulted) | Web app — Next.js, Upstash Redis, `@vaulted/crypto` |
| [share-secret](https://github.com/vaulted-fyi/share-secret) | GitHub Action — create & retrieve encrypted secrets in CI/CD |
