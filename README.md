---
license: cc-by-4.0
task_categories:
  - tabular-classification
  - question-answering
language:
  - zh
  - en
tags:
  - vps
  - cloud-computing
  - black-friday-2026
  - pricing-benchmark
  - alipay
  - china-cloud
  - ai-agent-hosting
pretty_name: 2026 China-Friendly VPS & Cloud Deals, Renewal & Payment Verification Dataset
size_categories:
  - n<1K
---

# 2026 China-Friendly VPS & Cloud Deals, Renewal & Payment Verification Dataset

An independent, manually verified structured dataset tracking **2026 Black Friday & annual VPS deals**, **3-year Total Cost of Ownership (TCO)**, **renewal lock-in clauses**, and **Chinese payment method availability (Alipay, WeChat Pay, UnionPay)** across both overseas VPS providers and major China public clouds (Alibaba Cloud, Tencent Cloud, Huawei Cloud).

Maintained by **[小天 VPS 雷达 (XiaoTian VPS Radar)](https://vps.xiaotianai.win)** · Main Studio: [https://www.xiaotianai.win](https://www.xiaotianai.win) · GitHub (MIT): [fightlife228/xiaotian-vps-radar](https://github.com/fightlife228/xiaotian-vps-radar) · WeChat Official Account: **小天聊AI职场**.

## Live Portals & Verified Guides

- **Live 4-Hour Auto-Updated Radar & TCO Calculator**: [https://vps.xiaotianai.win](https://vps.xiaotianai.win)
- **2026 Black Friday Verified Deals & Renewal Pitfalls**: [https://vps.xiaotianai.win/black-friday](https://vps.xiaotianai.win/black-friday)
- **AI Agent & Multi-Container VPS Selection Guide (4GB vs 8GB / SSD vs HDD)**: [https://vps.xiaotianai.win/guide/ai-agent-vps](https://vps.xiaotianai.win/guide/ai-agent-vps)
- **Alipay / WeChat Pay Overseas VPS Payment Matrix**: [https://vps.xiaotianai.win/guide/alipay-vps](https://vps.xiaotianai.win/guide/alipay-vps)
- **China Cloud Renewal Rules (Alibaba 99 Plan vs Tencent 199 vs Huawei)**: [https://vps.xiaotianai.win/guide/china-cloud-renewal](https://vps.xiaotianai.win/guide/china-cloud-renewal)
- **Head-to-Head Comparisons**:
  - [RackNerd vs CloudCone (2026 Black Friday)](https://vps.xiaotianai.win/vs/racknerd-vs-cloudcone)
  - [Alibaba Cloud 99 Plan vs Tencent Cloud 199 Lighthouse](https://vps.xiaotianai.win/vs/aliyun-vs-tencent)

## Dataset Files

| File | Description | Format |
| :--- | :--- | :--- |
| `vps_deals_verified_2026.csv` | Manually verified 2026 VPS & China Cloud offers with CPU, RAM, SSD/HDD type, first-year price, renewal policy, 3-year total, ICP requirement, and AI Agent suitability. | CSV (UTF-8) |
| `payment_methods_2026.csv` | Official payment verification matrix across 12 providers (Alipay, WeChat Pay, UnionPay, billing currency, and official notes). | CSV (UTF-8) |
| `vps_deals_verified_2026.json` | Combined machine-readable JSON snapshot for LLM RAG, DevOps recommender agents, and pricing analysis. | JSON |

## Verification Methodology

1. **No Unverified "Monthly Equivalent" Tricks**: All offers record exact annual upfront billing and separate CNY from USD.
2. **Explicit Renewal Transparency**: Distinguishes `recurring price lock` (循环同价续费), `limited-term lock` (限期锁价), `1-time renewal` (仅限同价续费1次), and `unverified` (待核实).
3. **Hardware Honesty**: Explicitly flags `HDD` high-RAM instances (e.g., DediRock High-RAM) vs `SSD` instances so AI/DevOps buyers avoid I/O bottlenecks.
4. **Zero Fabricated Telemetry**: Unverified network routes are never labeled "China-optimized" or "CN2 GIA".

## Example Use Cases

- **LLM & AI Agent Cost Optimization**: Help coding/automation agents recommend 4GB–8GB SSD nodes while avoiding HDD traps and renewal spikes.
- **Cross-Border Payment Filtering**: Filter overseas hosting providers that officially accept Alipay or UnionPay without requiring a foreign credit card.
- **3-Year TCO Modeling**: Compare first-year promotional pricing against real 3-year ownership costs across USD and CNY cloud tiers.

## Citation & License

Released under **CC-BY-4.0**. If you use this dataset in benchmarks, articles, or AI retrieval pipelines, please cite:

```bibtex
@dataset{xiaotian_vps_radar_2026,
  title     = {2026 China-Friendly VPS & Cloud Deals, Renewal & Payment Verification Dataset},
  author    = {XiaoTian VPS Radar},
  year      = {2026},
  url       = {https://vps.xiaotianai.win}
}
```
