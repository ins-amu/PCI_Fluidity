# This repository contains the code to replicate some of the results from:

[Breyton, M.et al. Spatiotemporal brain complexity quantifies consciousness outside of perturbation paradigms. eLife13 , (2024).](https://doi.org/10.7554/eLife.98920.1)


To generate the resting-state simulations run:

```
snakemake -s snakefiles/resting-state-simulations.snake
```

To generate the PCI simulations run:

```
snakemake -s snakefiles/pcis.snake
```


Note:

The script to run the PCI simulations is very long to run (around 45k simulations). A file containing the precomputed metrics can be found in the `data` folder.
