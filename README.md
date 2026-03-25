# KQL Detections for Microsoft Security

This repository contains custom detection rules and hunting queries written in Kusto Query Language (KQL) for Microsoft Sentinel and Microsoft Defender.

## 🔗 About detections.ai

This repo is part of [detections.ai](https://detections.ai), a platform for creating, sharing, and managing KQL-based detection rules. You can connect this repo to detections.ai using their GitHub App.

## 📁 Repo Structure

detections/
├── EntraID/
│
├── Defender/
│   ├── MDE/
│   ├── MDI/
│   ├── MDO/
│   └── MCAS/
│
├── Sentinel/
│   ├── ScheduledRules/
│   └── HuntingQueries/

## ✍️ Naming Rules

- File names use lowercase and dashes: `suspicious-process.kql`
- One detection per file
- Use `let lookback = <timespan>;` for time range parameters
- Keep queries readable and include comments if needed

## 💡 How to Contribute

1. Fork this repo and create a new branch
2. Add your `.kql` file in the correct folder
3. Open a pull request — the PR template will guide you

## 📄 License

This project uses the MIT License. See [LICENSE](./LICENSE) for details.

---

🌐 Part of the [detections.ai](https://detections.ai) community. 
