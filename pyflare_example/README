### Case study: binding poses of tubulin α-1β with Epothilone A

This blog post demonstrates the powerful capability of the combined use of Flare and OpenBPMD in assessing the stability of protein-ligand binding poses, using two binding poses of tubulin α-1β with Epothilone A (EpoA) - PDB 1TVK (controversial) and PDB 4I50 (an updated model) - as examples.

Case study: http://blog.molcalx.com.cn/2025/05/06/exploring-pose-stability-using-bpmd.html
Files used in the case study
.
├── 1TVK_Dynamics.inpcrd.gz
├── 1TVK_Dynamics.prmtop.gz
├── 1TVK_prep.pdb
├── 4I50_Dynamics.inpcrd.gz
├── 4I50_Dynamics.prmtop.gz
└── 4I50_prep.pdb 

### Run BPMD
1. BPMD for PDB 1TVK
```
pyflare openbpmd.py \
-s 1TVK_Dynamics.inpcrd \
-p 1TVK_Dynamics.prmtop \
-o 1TVK \
-lig_resname EP \
-nreps 10
-hill_height 0.300
```
2. BPMD for PDB 4I50
```
pyflare openbpmd.py \
-s 4I50_Dynamics.inpcrd \
-p 4I50_Dynamics.prmtop \
-o 4I50 \
-lig_resname EP \
-nreps 10
-hill_height 0.300
```
