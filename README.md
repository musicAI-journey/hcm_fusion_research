# HCM-Western Fusion Research Project

**Melody-Conditioned Cross-Cultural Music Fusion: A Systematic Study of Architectural Approaches and Fine-Tuning Strategies for Hindustani Classical-Western Integration**

## Overview

This project systematically explores melody-conditioned generation for cross-cultural music fusion, comparing autoregressive (MusicGen Melody) and flow-matching (ACE-STEP) architectures for Hindustani Classical Music + Western genre integration.

**Timeline:** 3 weeks (21 days + buffer)  
**Target:** Research demonstration for Rafael Valle (Meta AI, Fugatto author)

## Project Structure

```
hcm_fusion_research/
├── data/                    # All audio data and metadata
├── outputs/                 # Generated audio samples
├── results/                 # Analysis, metrics, visualizations
├── models/                  # Model checkpoints and adapters
├── src/                     # Source code
├── notebooks/               # Jupyter notebooks for exploration
├── configs/                 # Configuration files
├── scripts/                 # Utility scripts
└── docs/                    # Documentation
```

## Setup

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Configure Weights & Biases (optional but recommended):**
   ```bash
   wandb login
   ```

3. **Place your YouTube downloads in:**
   ```
   data/raw/youtube_downloads/
   ```

4. **Run initial setup:**
   ```bash
   python scripts/verify_setup.py
   ```

## Research Timeline

- **Week 1 (Days 1-7):** Dataset preparation, model comparison, baseline matrix
- **Week 2 (Days 8-14):** Fine-tuning data curation, LoRA training, extended generation
- **Week 3 (Days 15-21):** Analysis, visualization, dashboard, documentation

## Key Contributions

1. First systematic comparison of autoregressive vs flow-matching for cross-cultural melody conditioning
2. Curated HCM+Western fusion dataset with evaluation protocol
3. Fine-tuning methodology on limited corpus demonstrating measurable improvement
4. Characterization of failure modes in cross-cultural fusion
5. Analysis of conditioning mechanisms and architectural insights

## Usage

See `docs/` folder for detailed usage instructions for each phase of the project.

## Citation

If you use this work, please cite:
```
[To be added after completion]
```

## License

MIT License - See LICENSE file for details

## Contact

[Your Name] - [Your Email]

Project Link: [GitHub URL]
