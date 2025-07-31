# KQL Detections for Microsoft Security

This repository contains detection rules written in Kusto Query Language (KQL) for Microsoft Sentinel, Microsoft Defender, and Microsoft Entra ID.

These rules help security teams detect suspicious activity, possible attacks, and risky behavior across different parts of the Microsoft security stack.

## 🔗 About detections.ai

This repo is part of [detections.ai](https://detections.ai), a platform for creating, sharing, and managing KQL-based detection rules. You can connect this repo to detections.ai using their GitHub App.

## 📁 Repo Structure

detections/
├── EntraID/
│   ├── sign-in-risk.kql
│   └── impossible-travel.kql
│
├── Defender/
│   ├── MDE/
│   │   └── suspicious-process.kql
│   ├── MDI/
│   │   └── unusual-logon.kql
│   └── MCAS/
│       └── data-exfiltration.kql
│
├── Sentinel/
│   ├── ScheduledRules/
│   │   └── multiple-failed-logins.kql
│   └── HuntingQueries/
│       └── beaconing-traffic.kql
│
├── Workbooks/
│   └── risky-users-visualization.workbook.json
│
└── _templates/
    └── detection-template.md

## ✍️ Naming Rules

- File names use lowercase and dashes: `suspicious-process.kql`
- One detection per file
- Keep queries readable and include comments if needed

## 💡 How to Contribute

1. Fork this repo and create a new branch
2. Add your `.kql` file in the correct folder
3. Use the template in `_templates/detection-template.md`
4. Open a pull request

## 📄 License

This project uses the MIT License. See [LICENSE](./LICENSE) for details.

---

🌐 Part of the [detections.ai](https://detections.ai) community. 
