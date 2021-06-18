# SSCG - Simple Signed Certificate Generator

x509 Certificates are complicated to get right. SSCG makes it easy to generate usable, signed certificates quickly without needing to understand complex `openssl`, `certtool` or `certutil` commands.

## How it works

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/sscg).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/sscg) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
