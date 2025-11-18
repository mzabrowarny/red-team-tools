# red-team-tools

A personal collection of offensive security tools, scripts, proofs-of-concept, and study projects created for developing practical Red Team and penetration testing skills.  
This repository includes custom-built utilities for reconnaissance, enumeration, exploitation, post-exploitation, and tooling automation.

The goal of this project is to:
- build real offensive security engineering experience  
- practice tool development in Python, Bash, and other languages 
- document offensive workflows and techniques  
- establish a practical portfolio for Red Team / Pentester / Offensive Security roles  

---

## Planned Repository Structure

```
red-team-tools/
├── recon/              # scanners, enumerators, fingerprinting utilities
├── exploitation/       # exploit helpers, payload creators, PoCs
├── postex/             # lateral movement, privesc, post-exploitation tools
├── web/                # web pentest tools, fuzzers, analysis scripts
├── crypto/             # cryptography utilities (educational)
├── misc/               # miscellaneous scripts and experiments
└── docs/               # documentation, notes, cheat sheets, research
```

---

## Example Tools (placeholders)

Each tool should ideally include:
- a dedicated folder  
- a README with usage examples  
- installation notes  
- screenshots (if relevant)  
- a short technical explanation 

---

## Installation & Usage

Clone the repository:

```bash
git clone https://github.com/mzabrowarny/red-team-tools.git
cd red-team-tools
```

Run any tool depending on its type:

```bash
python3 toolname.py
# or
chmod +x tool.sh && ./tool.sh
```

---

## Roadmap

### ✔ Short-term goals
- Implement at least 5 recon & enumeration tools  
- Build a small CLI for generating payloads (reverse shells, encoding, obfuscation)  
- Add first detection-oriented scripts from a blue-team perspective  

### ✔ Mid-term goals
- Develop a modular offensive framework (Python-based)  
- Add dedicated tools for web exploitation (SSRF tester, IDOR finder, param miner)  
- Expand the documentation with full offensive workflow examples  

### ✔ Long-term goals
- Create a complete Red Team toolkit framework  
- Integrate APIs (Shodan, VirusTotal, security search engines)  
- Add detection & correlation tooling for purple-team analysis  

---

## Skills Demonstrated

This repository is intended to showcase skills and competencies relevant to Pentesting, Red Team operations, SOC analysis, and Offensive Security engineering:
- Offensive Python scripting (threading, sockets, networking)
- Bash & Zsh scripting for automation
- Reconnaissance and enumeration techniques
- HTTP/HTTPS analysis and web pentesting fundamentals
- Payload creation and reverse-shell generation
- Fingerprinting services and technologies
- Post-exploitation methodology and privilege escalation research
- Documentation of offensive workflows
- Designing extensible cybersecurity tools

---

## Legal & Ethical Notice

All tools in this repository are created **strictly for educational and research purposes**.

You may only use them in:
- your own lab environments  
- systems where you have full permission from the owner  
- training platforms that explicitly allow this type of testing  

**Unauthorized security testing is illegal.  
The author is not responsible for any misuse of these tools.**

---

## Contact

For collaboration, contributions, or discussion:  
**(michal.zabrowarny@proton.me)**

---

### © 2025 – red-team-tools  
Educational offensive security toolkit.
