```
gpg -c --cipher-algo AES256 ./mastodon-twitter-sync.toml
```

```
gpg --batch --yes --decrypt --passphrase="$GPG_PASSPHRASE" --decrypt mastodon-twitter-sync.toml.gpg > mastodon-twitter-sync.toml
```
