# IT Support Home Lab 🧪

A hands-on learning repository focused on **desktop support, operating systems, networking, and systematic troubleshooting**. This lab documents practical activities and will grow into a collection of reproducible support scenarios.

## Overview

This project is intended to demonstrate the types of tasks commonly encountered in IT support and end-user computing environments. It is a personal learning environment, **not** a production enterprise network.

## Activities Documented So Far

Based on the original lab notes:

- Installed Windows and Ubuntu in virtual machines.
- Practiced operating-system installation.
- Configured IP settings.
- Practiced basic network and system troubleshooting.

## Skills Practiced

| Area | Topics |
|---|---|
| Operating systems | Windows, Ubuntu, OS installation |
| Virtualization | Virtual-machine setup and use |
| Networking | IP configuration and networking fundamentals |
| Troubleshooting | System and network diagnostics |
| Remote support | Remote-access fundamentals |

## Planned Troubleshooting Case Studies

The following are **planned exercises**, not completed lab results. Each case study will document the problem, environment, diagnosis, commands, resolution, and evidence.

- [ ] **Windows deployment:** Install Windows in a VM, document drivers, updates, and verification.
- [ ] **IP configuration:** Diagnose incorrect static IP, gateway, or subnet settings using `ipconfig` and `ping`.
- [ ] **DNS troubleshooting:** Test name resolution with `nslookup`, distinguish DNS failures from general connectivity issues.
- [ ] **DHCP troubleshooting:** Inspect lease details and practice renew/release in an isolated lab.
- [ ] **Linux diagnostics:** Use `ip addr`, `ip route`, `ping`, and `journalctl` to investigate issues.
- [ ] **Remote access:** Configure and test remote connectivity in a controlled VM environment.
- [ ] **PowerShell health checks:** Build a read-only script to report basic system health.

## Case Study Template

Use this structure when adding a real lab exercise:

```markdown
# Scenario: <short title>

## Goal
What are you trying to test or fix?

## Environment
OS/version, VM software, network mode, and relevant settings.

## Symptoms
What failed? Include exact errors where useful.

## Diagnostic Steps
Commands used and what the results showed.

## Resolution
Changes made and why they worked.

## Verification
How you confirmed the issue was resolved.

## Lessons Learned
Key takeaways and next improvements.
```

## Evidence & Safety

- Include screenshots or command output **only after** completing each exercise.
- Remove usernames, internal domains, public IPs, credentials, device identifiers, and other sensitive data before publishing.
- Use test VMs and isolated environments for experiments that change network or security settings.
- Do not publish employer-owned scripts, confidential configuration, or production asset records.

## Next Steps

1. Complete one Windows networking case study with diagnostic commands and verified results.
2. Add screenshots and a short explanation of the lab setup.
3. Create separate Markdown files for each completed scenario.
4. Add a PowerShell or Python diagnostic project after testing it.

---

**Maintainer:** [Mahesh Kumar](https://github.com/maheshkrcs-dev) · [Portfolio](https://maheshkrcs-dev.github.io/)
