# 🛰️ Reconic – Advanced Recon Framework for Bug Bounty Hunters 🕵️‍♂️

**Reconic** is a powerful, modular Bash-based reconnaissance toolkit built for ethical hackers and bug bounty hunters. It automates and integrates best-in-class tools like `subfinder`, `httpx`, `nuclei`, `assetfinder`, and more all in one script. Designed to give hackers a fast and structured way to collect attack surface data with minimal resources.

---

## ⚙️ Tools Integrated

   `subfinder` – Subdomain enumeration
    assetfinder` – Asset discovery
   `httpx` – Probes live domains
   `nuclei` – Vulnerability scanning with customizable templates
   `dnsx` – DNS resolution
    `waybackurls` – Collect archived endpoints
    `gf` – Pattern matching on fuzzable parameters
    And many more...

---

##  Features

    One-click recon pipeline
    Modular design – add or remove tools
    Works fast even on low-spec systems (like 4GB RAM)
    Creates clean and categorized output files
    Optimized for HackerOne/BBP methodologies
    Bash-native — portable, no heavy setup required

---

##  How to Use

1. Make it executable:
   ```bash
   chmod +x reconic.sh

    Run the tool:

./reconic.sh

Enter your target domain when prompted:

    example.com

    Reconic will:

        Enumerate subdomains

        Check for alive domains

        Run nuclei vulnerability scans

        Extract URLs from Wayback Machine

        Resolve DNS

        Identify possible parameters for fuzzing

📁 Output Example

output/
├── alive.txt
├── subdomains.txt
├── nuclei-results.txt
├── wayback-urls.txt
└── params.txt

📌 Use Cases

      Bug bounty recon automation

      Pentest prep for web targets

     Learning recon workflows

      Quick recon on new programs

👤 Author

Inayat Hussain (Inayat Raj Chohan)
  Cybersecurity Researcher | Bash Developer | Bug Bounty Hunter
  LinkedIn – Inayat Hussain Chohan
 Facebook: Inayat Raj Chohan
⚠️ Legal Disclaimer

This tool is for authorized testing and educational purposes only. Do not use Reconic on systems you don’t own or have explicit permission to test.
  Support My Work

    ⭐ Star this repo

    🔁 Share it with fellow hunters

    🗣️ Send feedback and feature requests

Let’s build the ultimate recon tool together 


---
