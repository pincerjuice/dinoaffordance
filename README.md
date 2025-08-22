# dinoaffordance

Task-conditioned affordance segmentation from RGB using frozen DINOv2 (vision) + MiniLM (text) with a lightweight FiLM fusion and decoder.

## Quick start
```bash
python -m venv .venv && source .venv/bin/activate
pip install --upgrade pip
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
pip install transformers timm einops albumentations opencv-python matplotlib tqdm
```

## Repo layout (initial)
- src/          models/, data/, utils
- tools/        sanity_forward.py (demo)
- out/          generated outputs (gitignored)
