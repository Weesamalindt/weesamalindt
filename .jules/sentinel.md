## 2025-02-27 - [Sentinel initialized .gitignore]
**Vulnerability:** Missing `.gitignore` configuration in repository root, which increases the risk of accidentally committing sensitive files such as secrets, keys, and environment variables.
**Learning:** Found an empty project structure initialized without baseline safety mechanisms to prevent secret exposure. This pattern highlights the need for default-deny file tracking on sensitive extensions (`.env`, `.key`, `id_rsa`, etc.).
**Prevention:** Implementing a baseline `.gitignore` provides defense-in-depth against secret leakage from developer workstations right at the repository inception.
