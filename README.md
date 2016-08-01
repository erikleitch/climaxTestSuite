# climaxTestSuite
A set of sample scripts for use with climax (see https://github.com/erikleitch/climax).

## Simple cluster fitting

An example of fitting a clust mass model to a single UVF dataset is given in ```scripts/cluster_arnaud_fit.cmx```.

```
cd scripts
climaxRunManager file=cluster_arnaud_fit.cmx logo=f
```

should eventually produce a plot that looks something like:

![ClusterFit](https://github.com/erikleitch/climaxTestSuite/blob/master/images/cluster_arnaud_fit.png)

displaying the data, model, residuals and parameter constraints.

## Handling mosaicked data

A simple example of loading a mosaic consisting of two pointings, removing a point-source model and displaying the residuals, is given in ```scripts/cluster_mosaic_disp.cmx```.

```
cd scripts
climaxRunManager file=cluster_mosaic_disp.cmx logo=f
```

should eventually produce a plot that looks something like:

![ClusterFit](https://github.com/erikleitch/climaxTestSuite/blob/master/images/cluster_mosaic_disp.png)

displaying the mosaicked data, model and residuals.


