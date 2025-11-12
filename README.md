# Download & Update

All releases are stored in the official GitHub repository. The binaries are self-contained — no additional installation is required.

To download, find the appropriate executable for your OS (linux / macOs / windows) and architecture (x64 / arm64) in the "Assets" section and download it.

<figure><img src="https://372979249-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FRH6gjCknEib3ehMtYkt1%2Fuploads%2FfttADEXG78hGNcUKoZze%2F77e17fde-856c-4292-9828-74b129ed0b08.png?alt=media&#x26;token=a81c5486-5db7-440a-b9fc-04cf1d38196d" alt=""><figcaption></figcaption></figure>

## Auto-updates

On startup the system automatically checks for new versions and downloads the binary for the same OS and architecture.

To disable auto-updates, open `system.toml` and set `AUTO_UPDATER` false

```toml
# Enable automatic updates check and download on startup.
AUTO_UPDATER = false
```

## Security

Download only from the official repository.

The label `sha:...` to the right of each file — is the **SHA256 hash** of the file.

* SHA256 is a unique checksum (hash) that is generated from the contents of a file.
* It is used for **verifying the integrity and authenticity** of the downloaded binary.
* That is, after downloading you can generate the SHA256 on your computer and compare it with this value. If they match — the file is not corrupted and is original.
