# Hi, I'm Reinhard

I build cryptographic tools in C# and Python — from custom stream ciphers to AES implementations and statistical test suites. Everything is open source (MIT), documented with honest threat models, and validated against the original NIST SP 800-22 specification.

## Projects

| Project | Language | What it does |
|---------|----------|-------------|
| [Turbine V5.2](https://github.com/ReinhardJesolowitz24/Turbine) | C# / WPF | File encryption with self-developed stream cipher (1280-bit state, custom S-Box, PBKDF2-SHA512). 17/17 NIST tests. |
| [AES-256-Pure](https://github.com/ReinhardJesolowitz24/AES-256-Pure) | Python | Textbook AES-256-CTR with zero dependencies. 17/17 NIST tests. For learning and comparison. |
| [py-nist-sp800-22](https://github.com/ReinhardJesolowitz24/py-nist-sp800-22) | Python | Complete NIST SP 800-22 statistical randomness test suite. Corrected against the original document. |
| [encryption-tools](https://github.com/ReinhardJesolowitz24/encryption-tools) | Python | S-Box generator (all 30 GF(2^8) polynomials), bias analysis, and cipher testing tools. |

These four projects form a toolkit: build a cipher, test it against AES, and validate both with the same NIST suite.
