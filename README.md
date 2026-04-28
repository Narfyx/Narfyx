# 👋 Bonjour ! 🇫🇷

> System / Network / Security  
> _"segmentation fault !"_  
> _powered by Linux, tolerating other things._

<img src="header.svg" width=100% height="8">

## 🎓 Education

- Systems, Network and Data Security Expert (in progress at school 2600)
- System Administrator & DevOps
- Python Development

---

## 💼 Experience

**System Administrator & Security**  
- managing systems, infrastructure and security posture  
- ensuring reliability, performance and controlled access  
- implementing hardening and defensive measures  
- developing automation to reduce manual workload and support other IT teams

**Network Support Manager**  
- operating and maintaining telecom core network infrastructure (operator side, not customer LAN)  
- monitoring network performance, capacity and traffic flow  
- handling incident escalation on critical network services  
- managing VoIP infrastructure and telephony fleet (provisioning, changes, maintenance)  

**Network Technician**  
- deploying and integrating network infrastructures  
- working alongside engineering teams (non-support role)  
- ensuring proper implementation and configuration  

**Helpdesk Technician**  
- handling user incidents and technical support  
- troubleshooting systems, network and access issues  
- building strong diagnostic and problem-solving skills  

---

## 📊 Mindset

| Domain        | Focus |
|--------------|------|
| Infrastructure     | ██████████ |
| Security (Blue)    | ██████░░░░ |
| Security (Red)     | ███░░░░░░░ |
| DevOps             | █████░░░░░ |

---

## 🧭 Overview

Infrastructure-focused profile.

I design systems that are:
- segmented by default  
- observable in depth  
- controlled in exposure  
- resilient by design  

Most of my work is defensive (blue team),  
with selective offensive testing to validate assumptions.

---

## 🏗️ Current Work

- building production-like homelab environments  
    > some services behave differently depending on where they are observed 👀  

- designing segmented network architectures  
    > packets don’t always take the path you expect… unless you force them  

- reducing attack surface & service exposure  
    > if it’s not visible, it probably shouldn’t be reachable  

- implementing observability (logs, metrics, flows)  
    > everything leaves traces — the question is: do you collect them  

- simulating incidents & validating containment  
    > assume breach → measure spread → verify boundaries  

- crafting automated Windows deployments (custom ISO pipelines, unattended logic, controlled setup stages)  
    > hint: some folders magically replicate themselves at install time  
    > others execute things where they shouldn't be executed 👀  

---

## 🏠 Lab Architecture

- strict network segmentation  
- minimal trust between zones  
- controlled service exposure  

---

## 🔬 Research

Working on low-level system analysis and reconstruction:

- legacy system behavior understanding  
- hardware interaction logic  
- integration into modern Linux environments  

---

## 🧰 Stack (abstracted)

- virtualization / containerization  
- network segmentation  
- system hardening  
- monitoring & logging  
- infrastructure automation  

---

## ☕ Runtime

```bash
root@infra:~# uname -a
Linux stable, predictable, documented

root@infra:~# connect windows-client
loading...
installing updates (1/∞)

root@infra:~# ./analyze_issue.sh
root cause: windows
confidence: 99%

root@infra:~# ./apply_fix.sh
installing workaround...
waiting for next issue

root@infra:~# echo "have you tried rebooting?"
>> always yes

root@infra:~# uptime
still running
(unlike some systems)
```
