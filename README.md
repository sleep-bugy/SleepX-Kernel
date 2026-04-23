# KernelSleepX for POCO F6 (peridot)

<p align="center">
  <img src="https://img.shields.io/badge/Kernel-6.1.166_LTS-blue?style=for-the-badge&logo=linux" />
  <img src="https://img.shields.io/badge/Compiler-XClang_22.1.2-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Stable-green?style=for-the-badge" />
</p>

---

## Changelogs
* **Upstream:** Google 6.1.166 LTS
* **Compiler:** XClang LLVM 22.1.2
* **Networking:** BBRplus, BBRv3, TCP Brutal, & TCP Fast Open
* **Feature:** NTSync, Wireguard, ADIOS I/O Scheduler
* **Memory:** Backport per-memcg reclaim & vmpressure optimization
* **Charging:** Implement `charging_enabled` node & fastcharge mode 1 detection
* **Hardware:** Dual fuel gauge support (SLAVE_CHIP guard)
* **Touch/Display:** New Xiaomi touch driver header, fold_status support, & FOD finger state node
* **Misc:** Added software_cid, screen_cctog, reverse_quick_charge, and cloud_dynamic_shutdown nodes

## Performance Version
* **Default Governor:** Performance
* **Optimization:** Sched Fair Equalize Asym Priority & Schedutil Amend Pending Freq

---

## Variants Information
FOR BASIC and SUSFS (SUKISU,RESUKI) VARIAN HAVE SUPPORT KPM
* **KSUN:** (v33133)
* **SUKISU:** (v40750)
* **RESUKISU:** (v34832)

### Selection Guide
| Variant | Recommendation |
| :--- | :--- |
| **Normal** | Balanced for daily usage |
| **Perf** | Maximum performance (High Temp! ❄️ Use Cooler) |
| **SUSFS** | Best for Banking apps & Root hiding |

---

## ⚠️ Notes
* **Flash at your own risk.** Always backup your `boot.img`.
* **Compatibility:** Not support CLO base (YAAP/Neoteric).
* Support HyperOS 3.0.X (Trinuca). Not support 2.0.X (Trinuca).
* **Bug Report:** No logs = No fix.

---
<p align="center">Developed with ❤️ by <b>ProjectSleep</b></p>
