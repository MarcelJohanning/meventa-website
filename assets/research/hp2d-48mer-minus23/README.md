# HP2D 48-mer -23 folding result

Technical evidence package for a MEVENTA Creative Runtime v10 run.

## Result

MEVENTA Creative Runtime v10 found a valid 2D HP folding for the classic Istrail HP2D 48-mer benchmark sequence:

PPHPPHHPPHHPPPPPHHHHHHHHHHPPPPPPHHPPHHPPHPPHHHHH

Validated result:

- Energy: -23
- H-H contacts: 23
- Valid fold: true
- Violations: 0
- Sequence length: 48
- Coordinates: 48

The fold was exported as JSON coordinates and independently revalidated from the exported artifact.

## Run reference

Batch:

logs/batch-10x1000-v10-fold-artifact-autokill-20260625-081905

Run:

run-02-1000-v10-fold-artifact-20260625-084926

Candidate:

cand_1782371765506_5eolwv

First -23 in this run:

cycle 899 / point 11274

## What is claimed

This package claims that MEVENTA Creative Runtime v10 produced a valid coordinate artifact for the Istrail HP2D 48-mer sequence with energy -23, corresponding to 23 non-consecutive H-H contacts.

This matches the best-known reported energy level for this benchmark sequence.

## What is not claimed

This is not a claim of AGI.

This is not a general protein-folding claim.

This is not a compute-normalized benchmark comparison.

This is not a claim that HP2D is equivalent to real biological protein folding.

This is not a claim that MEVENTA outperforms every published method.

## Literature context

Yang et al. report the same -23 energy level for the Istrail 48mer using an LSTM-DQN deep reinforcement learning approach. Their paper compares against earlier RL work such as FoldingZero and reports -23 for the 48mer in their method, while FoldingZero is listed at -18 for the same sequence.

The comparison here is energy-level parity on the same benchmark sequence, not a compute-normalized equivalence claim.

## Run setup note

This artifact was produced by a local MEVENTA Creative Runtime v10 run on a MacBook. No benchmark-specific pretraining dataset or model checkpoint was used for this run.

## Files

artifact/original-fold.json  
Original exported coordinate artifact.

artifact/original-fold.svg  
Original exported fold rendering.

figures/hp2d-48mer-minus23-hero.*  
Publication / LinkedIn / website figure.

figures/hp2d-48mer-minus23-evidence.*  
Technical evidence figure with candidate / hash / validation metadata.

validation/*.validation.json  
Independent coordinate validation output.

run/run-02-minus-23.log  
Run log for the -23 artifact run.

source-used/  
Code files used in the artifact-producing run/export/rendering path.

## References

- Yang et al., Applying Deep Reinforcement Learning to the HP Model for Protein Structure Prediction, Physica A / arXiv:2211.14939.
- Liang and Wong, Evolutionary Monte Carlo for protein folding simulations, Journal of Chemical Physics, 2001.
