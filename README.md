# Robust-Rocket-Recovery
Rocket landing control benchmark using f-Shrink operator and V-space dynamics. V-space controllers achieve 100% success under extreme conditions.
🚀 f-shrink-rocket-benchmark

Rocket landing control benchmark using f-Shrink operator and V-space dynamics. V-space controllers achieve 100% success under extreme conditions including wind disturbances, engine failures, and combined stress scenarios.

📊 Key Results

· V-space controllers achieve 100% landing success across all test phases
· Optimal β range: 0.030–0.050 (β = 0.035 recommended)
· Outperforms PID and Z/U-space variants by 9–10%

🏆 Top Performers

Rank Controller Success Rate
🥇 V_fast_β0.030 100%
🥈 V_fast_β0.040 100%
🥉 V_fast_β0.050 100%

🚀 Quick Start

```bash
pip install numpy matplotlib tqdm
python rocket_benchmark.py
```

📖 Citation

If you use this code, please cite:

Xie, M. (2026). High-Robustness Rocket Landing Control Based on f-Shrink and V-Space. Zenodo.
https://doi.org/10.5281/zenodo.18795975

📄 License

MIT    
