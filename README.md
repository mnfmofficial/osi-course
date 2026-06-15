# OSI — Practical Security Course

An offline-capable PWA covering all seven OSI layers from a security perspective.

**Live:** https://mnfmofficial.github.io/osi-course/

---

## Contents

| Layer | Name | Key Protocols |
|---|---|---|
| 1 | Physical | Cables, Hubs, NICs, Signals |
| 2 | Data Link | Ethernet, ARP, MAC, Switches |
| 3 | Network | IP, ICMP, Routing, nmap |
| 4 | Transport | TCP, UDP, Ports, Handshake |
| 5 | Session | NetBIOS, RPC, Cookies |
| 6 | Presentation | TLS/SSL, Encoding, Encryption |
| 7 | Application | HTTP, DNS, FTP, SMTP, SSH |

Each layer includes four sections: theory, real-world analogy, attack surface, and terminal exercises.

---

## Quiz System

- 9 questions per layer (63 total)
- 20-question combined final exam
- Progress saved locally via localStorage

---

## Install on Android

Open the live link in Chrome → three-dot menu → Add to Home Screen.
Works fully offline after first load.

---

## Run Locally

```bash
git clone https://github.com/mnfmofficial/osi-course.git
cd osi-course
python3 -m http.server 8080
```

Visit `http://localhost:8080`

---

## Structure

```
osi-course/
├── index.html        # Full course — all content and logic
├── manifest.json     # PWA manifest
├── sw.js             # Service worker for offline use
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

---

## License

MIT
