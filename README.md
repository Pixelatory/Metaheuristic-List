# Metaheuristics

This is simply a note that recognizes a bunch of metaheuristics that I’ve come across throughout my research. This may be of use when attempting to discover new variants or successors. 

If you want your algorithm posted here please email me! (link on github profile)

## Particle Swarm Optimization (PSO)

### Single-objective

- Original PSO: https://doi.org/10.1109/ICNN.1995.488968
- Original PSO w/ Inertia: https://doi.org/10.1109/ICEC.1998.699146

#### Cooperative

Known for working well for large-scale optimization problems. May need to consider variable dependencies when splitting dimensionality.

- CPSO-S, CPSO-Sk, CPSO-Hk: https://doi.org/10.1109/TEVC.2004.826069
- CCPSO: https://doi.org/10.1109/CEC.2009.4983126
- DCPSO, MCPSO: https://doi.org/10.1145/3206185.3206199
- RG-DCPSO, RG-MCPSO: submitted but in review.

### Multi-objective

- MGPSO: https://doi.org/10.1007/s11721-019-00171-0
- CMOPSO: https://doi.org/10.1016/j.ins.2017.10.037
- HTL-PSO: https://doi.org/10.1016/j.neucom.2016.10.001
- MOPSO_TA: https://doi.org/10.1016/j.asoc.2022.108532
- MMOPSO: https://doi.org/10.1016/j.ejor.2015.06.071
- MDEPSO: https://doi.org/10.1007/978-3-540-89694-4_26

#### Cooperative
- CCMGPSO: Madani, Amirali. "Multi-Guide Particle Swarm Optimization for Large-Scale Multi-Objective Optimization Problems." (2021).

### Many-objective

- VaPSO: https://doi.org/10.1016/j.asoc.2021.107299
- MaOPSO/2s-pccs: https://doi.org/10.1109/TCYB.2016.2548239
- MOPSO/GDR: https://doi.org/10.1016/j.asoc.2020.106661
- RMOPSO & DMOPSO: https://doi.org/10.1007/978-3-540-87700-4_75
- MOPSO/DD: https://doi.org/10.1109/TCYB.2019.2922287

## Genetic Algorithms (GA)

### Single-objective
- Original GA: http://datajobstest.com/data-science-repo/Genetic-Algorithm-Guide-[Tom-Mathew].pdf
  - note: explains the vanilla algorithm, but not the original author(s) of GA.

#### Cooperative

- CCGA, CCGA-1, CCGA-2: https://doi.org/10.1007/3-540-58484-6_269
  - note: this may be the first time cooperative coevolution was introduced

### Multi-objective

- NSGA-II: https://doi.org/10.1109/4235.996017

#### Cooperative

- NSCCGA: https://doi.org/10.1007/978-3-540-24854-5_56

## Differential Evolution (DE)

### Single-objective
- Original DE: https://doi.org/10.1109/NAFIPS.1996.534789

#### Cooperative

- CoDE-AG: https://doi.org/10.1177%2F1687814019834161
- DECC-RAG: https://doi.org/10.5220/0006903102610268

### Multi-objective

#### Cooperative
- CMODE: https://doi.org/10.1109/TCYB.2015.2490669
- CCMODE (constrained): https://doi.org/10.1109/TCYB.2018.2819208
- MLFS-CCDE (for feature selection): https://doi.org/10.1007/s12293-021-00328-7
- NSCCDE: https://doi.org/10.1109/ACCESS.2017.2716111

### Many-objective
- NSDE-R: https://doi.org/10.1007/s00158-019-02272-0
- MyO-DEMR: https://doi.org/10.1145/2463372.2463445
- DECOR: https://doi.org/10.1016/j.ins.2017.09.051
- LSMaODE: https://doi.org/10.1109/TCYB.2022.3178929
- MGDE: https://doi.org/10.1007/s10479-022-04641-3
- RODE: https://doi.org/10.1007/s13369-020-04536-0
- MOLG-DE: https://doi.org/10.1016/j.jocs.2022.101746
- GrDE: https://doi.org/10.1109/CEC.2016.7744139

## Water Wave Optimization (WWO)

### Single-objective
- Original WWO: https://doi.org/10.1016/j.cor.2014.10.008
- SimWWO: https://doi.org/10.1109/CEC.2015.7256974

## Invasive Weed Optimization (IWO)

### Single-objective
- Original IWO: https://doi.org/10.1016/j.ecoinf.2006.07.003

## Ant Colony Optimization (ACO)

## Artificial Bee Colony Optimization

## Genetic Programming

## Nondominated Neighbor Immune Algorithm (NNIA)

# Frameworks

## Multi-objective

## Many-objective
- CEF: https://doi.org/10.1109/TETCI.2018.2849380
