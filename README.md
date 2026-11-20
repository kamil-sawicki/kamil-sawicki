![Kamil Sawicki — profile banner](https://raw.githubusercontent.com/kamil-sawicki/kamil-sawicki/refs/heads/main/bg.jpg)

# Kamil Sawicki

**Independent Security Researcher**

I find and report vulnerabilities in open-source software, Windows, and virtualization platforms including KVM, Hyper-V, and VMware. My work focuses on authentication and authorization bypasses, as well as memory corruption. I share technical write-ups of my findings on my blog.

[kamil-sawicki.github.io](https://kamil-sawicki.github.io) · [kamil.sawicki@tutamail.com](mailto:kamil.sawicki@tutamail.com)

## Security research

Reported vulnerabilities, with severity scores and links to my write-ups:

| Project | Finding | Score | Read more |
| --- | --- | ---: | --- |
| Microsoft Windows | Denial of service in the VHD Miniport Driver | 7.1/10 | [CVE-2026-69384](https://kamil-sawicki.github.io/posts/cve-2026-69384/) |
| ProxySQL | Heap buffer overflow reachable before authentication | 9.8/10 | [CVE-2026-48773](https://kamil-sawicki.github.io/posts/cve-2026-48773/) |
| rclone | Missing authentication in remote control file serving | 9.8/10 | [CVE-2026-49980](https://kamil-sawicki.github.io/posts/cve-2026-49980/) |
| Gitea | Authorization bypass allowing access to Actions artifacts across repositories | 9.6/10 | [CVE-2026-58426](https://kamil-sawicki.github.io/posts/cve-2026-58426/) |
| Traefik | HTTP/3 bypass of client certificate authentication (mTLS) | 7.8/10 | [CVE-2026-53622](https://kamil-sawicki.github.io/posts/cve-2026-53622/) |
| Traefik | Domain-fronting mTLS bypass in wildcard TLS options | 7.8/10 | [CVE-2026-48491](https://kamil-sawicki.github.io/posts/cve-2026-48491/) |
| Gitea | Authorization bypass in public-only access tokens and OAuth grants | 8.1/10 | [CVE-2026-24791](https://kamil-sawicki.github.io/posts/cve-2026-24791/) |
| Mattermost Boards | Privilege escalation to board administrator | 8.3/10 | [CVE-2026-9816](https://kamil-sawicki.github.io/posts/cve-2026-9816/) |
| SimpleSAMLphp SAML2 | TLS validator confusion in HTTP-Artifact validation | 8.7/10 | [CVE-2026-49283](https://kamil-sawicki.github.io/posts/cve-2026-49283/) |
| SimpleSAMLphp CAS server | Path traversal in the file-based ticket store | 8.6/10 | [CVE-2026-46491](https://kamil-sawicki.github.io/posts/cve-2026-46491/) |
| ProxySQL | MCP run_sql_readonly policy bypass using multiple SQL statements | 7.5/10 | [CVE-2026-48774](https://kamil-sawicki.github.io/posts/cve-2026-48774/) |
| SimpleSAMLphp | Bypass of expected issuer and request-response binding checks | 7.1/10 | [CVE-2026-49284](https://kamil-sawicki.github.io/posts/cve-2026-49284/) |
| Directus | Code execution through extension uploads in non-default configurations | 6.6/10 | [GHSA-95f8-mvw7-gpj9](https://kamil-sawicki.github.io/posts/ghsa-95f8-mvw7-gpj9/) |
| Appsmith | Path traversal in Git widget serialization | 7.1/10 | [GHSA-r553-q33m-v7pf](https://kamil-sawicki.github.io/posts/ghsa-r553-q33m-v7pf/) |
| Directus | Settings information disclosure | 6.5/10 | [GHSA-r9xq-xp38-j4j3](https://kamil-sawicki.github.io/posts/ghsa-r9xq-xp38-j4j3/) |
| Mattermost Microsoft Calendar plugin | Unauthenticated webhook request causing plugin denial of service | 5.3/10 | [CVE-2026-10556](https://kamil-sawicki.github.io/posts/cve-2026-10556/) |
| Argo CD | Command injection through SSH repository proxy URLs | 8.8/10 | [CVE-2026-55797](https://kamil-sawicki.github.io/posts/cve-2026-55797/) |
| cert-manager | ACME Challenge solver policy bypass and DNS credential misuse | 7.3/10 | [CVE-2026-62290](https://kamil-sawicki.github.io/posts/cve-2026-62290/) |
| authentik | Missing authorization checks in Shared Signals Framework | 5.4/10 | [GHSA-hmrg-vpp4-gj88](https://kamil-sawicki.github.io/posts/ghsa-hmrg-vpp4-gj88/) |
| nanomq | Heap Underflow in basic_authorize via Short Base64 Token |  7.5/10 | [GHSA-cgxg-fqq7-hqf9](https://github.com/nanomq/nanomq/security/advisories/GHSA-cgxg-fqq7-hqf9#event-1413812) |
