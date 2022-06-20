# Clio-NatCommData

## Guide
+ *ECDMCEMC_optimization...* : CSV with live optimization data (i.e. in-the-loop experimentation by Clio) from experiment run in paper.
  + conductivity - measured ionic conductivity (mS/cm)
  + GUID - unique identifier for each experiment
  + run_order - ordinal number for which run after a rinse each experiment was (i.e. 2 is the second experiment after a rinse)
  + Temp (C) 2 - temperature (C) of sample at testing of conductivity
  + output_cid - electrolyte being tested in CompositionID format (see [here](https://github.com/BattModels/Clio-PythonAPI))
  + LiPF6_molality - molality of LiPF6 (moles salt / kg solvent) in electrolyte being tested
  + EC_mass_fraction - fraction (by mass) of ethylene carbonate (EC) in electrolyte being tested
  + DMC_cosolvent_ratio - how much of non-EC mass in electrolyte being tested is dimethyl carbonate (DMC) instead of ethylmethyl carbonate (EMC)
  + sampling - random vs bayesian optimizer led experiment (RAND or BO)
  + expt_time - length of experiment run-time
