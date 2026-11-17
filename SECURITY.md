# Security

Please report a vulnerability privately rather than in a public issue: use **Report a vulnerability** on the repository's Security tab where it's offered.

## Verifying release tags

Release tags from the next release on are signed with this SSH key (ED25519, fingerprint `SHA256:Cmu68ap6cWakfmwSOfgVewO0/qAgYyJSAXKKGHEL3Gc`). Earlier tags are unsigned.

```
release@recursiveai.org namespaces="git" ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIBWeSlBxtshveYF/hQ94IoO9shp4K8gQSH+FuUtBTF99
```

To verify a tag, save that line as `allowed_signers` and run:

```
git -c gpg.ssh.allowedSignersFile=allowed_signers tag -v <tag>
```
