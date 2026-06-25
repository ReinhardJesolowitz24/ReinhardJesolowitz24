# Hi, I'm Reinhard

I build open-source tools with a focus on transparency and honest documentation —
cryptography in C# and Python, and embedded / IoT projects on Arduino. Everything is
MIT-licensed, with documented threat models and verification against the original
specifications (e.g. NIST SP 800-22).

## Cryptography

| Project | Language | What it does |
|---------|----------|-------------|
| [Turbine V5.2](https://github.com/ReinhardJesolowitz24/Turbine) | C# / WPF | File encryption with self-developed stream cipher (1280-bit state, custom S-Box, PBKDF2-SHA512). 17/17 NIST tests. |
| [AES-256-Pure](https://github.com/ReinhardJesolowitz24/AES-256-Pure) | Python | Textbook AES-256-CTR with zero dependencies. 17/17 NIST tests. For learning and comparison. |
| [py-nist-sp800-22](https://github.com/ReinhardJesolowitz24/py-nist-sp800-22) | Python | Complete NIST SP 800-22 statistical randomness test suite. Corrected against the original document. |
| [encryption-tools](https://github.com/ReinhardJesolowitz24/encryption-tools) | Python | S-Box generator (all 30 GF(2^8) polynomials), bias analysis, and cipher testing tools. |

These four form a toolkit: build a cipher, test it against AES, and validate both with the same NIST suite.

## Hardware / Energy

| Project | Language | What it does |
|---------|----------|-------------|
| [gigar1-shelly-zendure-monitor](https://github.com/ReinhardJesolowitz24/gigar1-shelly-zendure-monitor) | C++ / Arduino | Independent Arduino GIGA R1 monitor & watchdog for a Shelly Pro 3EM + Zendure SolarFlow home battery — live grid/phase data, daily kWh balance, and red/yellow alarms (grid-dumping, deep discharge, BMS) with self-supervision. |
| [esp32-shelly-zendure-monitor](https://github.com/ReinhardJesolowitz24/esp32-shelly-zendure-monitor) | C++ / Arduino | Budget ESP32-S3 port of the GIGA monitor — same Shelly Pro 3EM + Zendure SolarFlow watchdog (live grid/phase data, daily kWh balance, red/yellow alarms) on a ~1/3-cost ELECROW 7″ display (LovyanGFX RGB panel). |

A cheap, independent board cross-checking a more complex device — the *checker* kept separate from the *doer*.
