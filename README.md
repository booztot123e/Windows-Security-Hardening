# Windows-Security-Hardening
**สมาชิก**
- นาย พัสกร บทศรี — Task 1–3
- นาย ธนพล ผายาว — Task 4–5

- ## Task 1 — UAC & Users
ตั้ง UAC (Always notify), สร้าง DevUser1/TestUser1/AdminUser1 และแยกกลุ่ม

## Task 2 — Group Policy
Password min=12, max=90, min age=7, history=5, complexity=ON; Lockout 3/30/30; User Rights (Allow log on locally, Log on as a service: SvcUser1, Backup privilege); ปิด Guest, Rename Administrator → SystemAdmin, Legal Notice

## Task 3 — Defender & Firewall Profiles
เปิดการป้องกันหลักทั้งหมด, ตั้งสแกน 02:00 ทุกวัน, Quick scan, เปิดไฟร์วอลล์ทุกโปรไฟล์ + logging, Exploit Protection

## Task 4 — Firewall Rules
Allow RDP from LAN, (optional) Block RDP from Internet, Block outbound ICMPv4, allow program เจาะจง, เปิด logging

## Task 5 — Event Monitoring
ขยายขนาด log, export Security baseline, เปิด auditpol, สคริปต์ MonitorSecurity.ps1 + Scheduled Task ทุก 5 นาที, เก็บ Performance baseline
