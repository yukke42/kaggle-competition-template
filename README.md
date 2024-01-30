# Kaggle: Competition Template

```bash
poetry init
poetry source add torch-cuda121 --priority=explicit https://download.pytorch.org/whl/cu121
poetry add torch torchvision --source torch-cuda121
poetry add transformers[torch]
...
```
