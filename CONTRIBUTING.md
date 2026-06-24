# Contributing to Crypto-Pulse

Thank you for helping secure the post-quantum software supply chain. We welcome contributions from the community, whether you are fixing a bug, expanding language support in our AST parsers, or updating cryptographic rule sets.

To ensure a seamless verification process and maintain clear software pedigree for our enterprise and foundation users, all contributors must follow the guidelines outlined below.

---

## Developer Certificate of Origin (DCO)

To maintain tracking of intellectual property ownership, Crypto-Pulse enforces the **Developer Certificate of Origin (DCO)** standard. 

By signing your commits, you certify that you wrote the code or have the right to pass it on as open-source under the Apache-2.0 License.

### How to Sign Your Commits
Every single commit message must contain a `Signed-off-by:` line with your real name and email address. You can automate this completely by adding the `-s` flag when committing code:

```bash
git commit -s -m "feat: add support for SHA-256 legacy primitives detection"
