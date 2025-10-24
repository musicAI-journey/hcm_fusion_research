# Day 1: L0 Stable Audio Baseline - Complete Analysis

**Date:** October 23, 2025
**Model:** Stable Audio Open (Text-Only Conditioning)  
**Status:** ✓ 240/240 generations completed (100%)

## Executive Summary

Pitch contour correlation = -0.003 (confirms H1: audio conditioning necessary)
Chroma cosine = 0.783 (novel discovery: semantic learning from raag names)

## Key Findings

### Primary Metrics (N=240)
- Pitch Contour: μ=-0.003, σ=0.165, range=[-0.567, 0.458]
- Chroma Cosine: μ=0.783, σ=0.099, range=[0.512, 0.973]  
- Chroma Pearson: μ=-0.044, σ=0.278, range=[-0.577, 0.744]
- Tempo Adapt: μ=0.422, σ=0.440, range=[0.0, 1.0]

### Research Implications
1. H1 confirmed: Audio conditioning necessary for melody preservation
2. Semantic learning discovered: Text provides pitch vocabulary, not structure
3. 59 paradox cases (24.6%): High chroma + zero contour
4. Genre-agnostic effect: Consistent across Rock/Jazz/Funk/Blues
5. Top case: Abhogi raag 97.3% pitch overlap, zero melody preservation

### Next Steps
Begin L1 MusicGen Melody generations (chromagram conditioning)
