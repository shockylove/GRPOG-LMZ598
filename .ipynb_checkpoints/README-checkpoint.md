# LMZ598
code generation research on inference scaling
---

## 🚀 Improvements Made

| Component          | Description |
|:-------------------|:------------|
| **Advantage**       | Improved estimation method for more stable policy gradients. |
| **Reward**          | Reward function reshaping to enhance learning signals. |
| **Objective Function** | Modified loss function to better align with final task rewards. |

---

## 🧪 Experiments and Ablation Study

We conduct the following experiments:

| Experiment Branch      | Description |
|:------------------------|:------------|
| `original_grpo`         | Original GRPO algorithm (baseline). |
| `improved_advantage`    | Only the advantage estimation improved. |
| `improved_reward`       | Only the reward function improved. |
| `improved_objective`    | Only the objective function improved. |
| `full_improvement`      | All improvements applied together. |

Results are saved under the `results/` directory, categorized by experiment.

---

## 📜 How to Run

1. **Install dependencies**:

```bash
pip install -r requirements.txt