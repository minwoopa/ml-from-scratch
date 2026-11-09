# ml-from-scratch

Modern ML, implemented from the ground up. Autograd → transformer → GPT-2 → post-training → agents → evaluation → first experiment.

Economist (PhD) with an engineering background. Each folder is one piece built from the paper, with a stated completion criterion.

| | Folder | Done when |
| --- | --- | --- |
| 1 | `01-autograd` | Gradients match PyTorch; MNIST ≥ 98% |
| 2 | `02-transformer` | GPT from the paper; samples read as text |
| 3 | `03-gpt2` | Logits match public GPT-2 weights; ≥ 3× throughput over baseline |
| 4 | `04-dpo` | Preference accuracy reproduces the paper's trend |
| 5 | `05-agents` | One table from an LLM-agent economics paper replicated |
| 6 | `06-evals` | Every score carries a clustered standard error |
| 7 | `07-experiment` | First experiment run; technical note written |

No reference code copied; where consulted, the folder README says so.
