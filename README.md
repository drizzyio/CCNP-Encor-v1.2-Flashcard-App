# 📡 CCNP ENCOR 350-401 — Interactive Flashcard Study App

A fully self-contained, browser-based flashcard app covering all **6 official exam domains** of the Cisco CCNP Enterprise Core (ENCOR) exam. No internet connection required after download — just open the HTML file and study.

---

## 📋 Overview

| Detail | Info |
|--------|------|
| **Exam** | Cisco CCNP Enterprise Core (ENCOR 350-401) |
| **Total Cards** | 240 |
| **Format** | Single HTML file (no install, no dependencies) |
| **Works On** | Any modern browser (Chrome, Firefox, Safari, Edge) |

---

## 🗂️ Domains Covered

| Domain | Cards | Exam Weight |
|--------|-------|-------------|
| Architecture | 40 | ~15% |
| Virtualization | 35 | ~10% |
| Infrastructure | 55 | ~30% |
| Network Assurance | 30 | ~10% |
| Security | 50 | ~20% |
| Automation | 30 | ~15% |

Topics include: SD-Access, SD-WAN, OSPF, BGP, EIGRP, STP, HSRP/VRRP/GLBP, VXLAN, EVPN, QoS, MPLS, VRF, DMVPN, IPsec/IKEv2, 802.1X, TrustSec/SGT, Cisco ISE, DHCP Snooping/DAI, MACsec, NETCONF/RESTCONF, YANG, Ansible, Python/Netmiko/NAPALM, DNA Center API, NetFlow, Streaming Telemetry, and much more.

---

## 🚀 How to Use

1. **Download** `ccnp-encor-full.html`
2. **Open** it in any web browser (double-click or drag into browser)
3. **Study!** No server, no install, no internet needed

---

## 🎮 Features

### Filtering
- Filter cards by any single domain using the tabs at the top
- Filter to only cards you've flagged as **Needs Review** or **Know It**
- Shuffle the current deck at any time

### Flashcard Interaction
- Click a card (or press **Space**) to flip between question and answer
- Each card displays a color-coded domain badge for at-a-glance context

### Progress Tracking
- Mark cards as **✓ Know It** or **⚑ Needs Review** as you study
- Progress bar and stats (Know It count, Review count, Seen count, % complete) update in real time
- Stats reset when you refresh the page — this is intentional to encourage full-deck reviews

### Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `→` | Next card |
| `←` | Previous card |
| `Space` or `Enter` | Flip card |
| `K` | Mark as Know It + advance |
| `R` | Mark as Needs Review + advance |

---

## 💡 Suggested Study Strategy

1. **First pass** — go through all 240 cards, marking each as Know It or Needs Review
2. **Second pass** — filter to Needs Review and focus only on weaker areas
3. **Domain deep-dives** — use domain filters to focus on lower-confidence topics before the exam
4. **Shuffle mode** — use the shuffle button to simulate random exam question order
5. **Repeat** until your Know It count reaches 240 ✅

---

## 📁 File Structure

```
/
├── ccnp-encor-full.html   # The entire app — all 240 cards, styles, and logic in one file
└── README.md              # This file
```

Everything is contained in a single HTML file. There are no external dependencies, frameworks, or build steps.

---

## 🤝 Contributing

Contributions are welcome! If you spot an error, want to add cards, or improve the UI:

1. Fork the repo
2. Make your changes in `ccnp-encor-full.html`
3. Open a Pull Request with a brief description of what you changed

Please keep card answers accurate to Cisco's official ENCOR exam topics and documentation.

---

## ⚠️ Disclaimer

This flashcard app is an independent study aid and is **not affiliated with, endorsed by, or sponsored by Cisco Systems**. CCNP and ENCOR are trademarks of Cisco Systems, Inc. Always refer to Cisco's official exam blueprint and documentation as your primary study resource.

---

## 📚 Additional Study Resources

- [Cisco ENCOR 350-401 Exam Topics](https://learningnetwork.cisco.com/s/encor-exam-topics)
- [Cisco DevNet Learning Labs](https://developer.cisco.com/learning/)
- [Cisco dCloud Sandbox Labs](https://dcloud.cisco.com)
- [Cisco Learning Network](https://learningnetwork.cisco.com)

---

## ⭐ Support

If this helped you study, give the repo a star — it helps others find it!

Good luck on the exam. You've got this. 🎯
