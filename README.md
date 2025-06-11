# 🔥 **Streamvault**

**peer-to-peer backup mesh for distributed workflows**

---

### concept

Streamvault monitors directories, encrypts changes, and streams deltas to peers—completely serverless.

---

### install

```bash
curl -fsSL streamvault.ink/install.sh | bash
```

### config

```toml
[peer]
address = "10.0.0.15"
sync_interval = 30
encrypt = true
```

### status

`streamvault status --watch`

Built with Rust + QUIC protocol.
Apache-2.0 © [streamvault.ink](https://streamvault.ink)

# Touch update: 1760965250
