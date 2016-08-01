# climaxTestSuite
A set of sample scripts for use with climax (see https://github.com/erikleitch/climax).

# Index

* <a href=#cluster_fit>Simple cluster fitting</a>
* <a href=#mosaic_disp>Displaying mosaicked data</a>
* <a href=#stacked_fit>Simple stacked data</a>
* <a href=#stacked_mosaic_disp>Mosaicked stacked data</a>
  
# <a name=cluster_fit>Simple cluster fitting</a>

An example of fitting a cluster mass model to a single UVF dataset is given in ```scripts/cluster_arnaud_fit.cmx```.

```
cd scripts
climaxRunManager file=cluster_arnaud_fit.cmx logo=f
```
should eventually produce a plot that looks something like:

![ClusterFit](https://github.com/erikleitch/climaxTestSuite/blob/master/images/cluster_arnaud_fit.png)

displaying the data, model, residuals and parameter constraints.

# <a name=mosaic_disp>Displaying mosaicked data</a>

A simple example of loading a mosaic consisting of two pointings, removing a point-source model and displaying the residuals, is given in ```scripts/cluster_mosaic_disp.cmx```.

```
cd scripts
climaxRunManager file=cluster_mosaic_disp.cmx logo=f
```
should eventually produce a plot that looks something like:

![ClusterFit](https://github.com/erikleitch/climaxTestSuite/blob/master/images/cluster_mosaic_disp.png)

displaying the mosaicked data, model and residuals.

# <a name=stack_fit>Simple stacked data</a>

A simple example of stacking multiple observations in a UVF dataset and fitting to the result is given in ```scripts/cluster_stack_arnaud_fit.cmx```.

```
cd scripts
climaxRunManager file=cluster_stack_arnaud_fit.cmx logo=f
```
should eventually produce a plot that looks something like:

![ClusterFit](https://github.com/erikleitch/climaxTestSuite/blob/master/images/cluster_stack_arnaud_fit.png)

displaying the mosaicked data, model and residuals.

# <a name=stacked_mosaic_disp>Mosaicked stacked data</a>

A simple example of stacking multiple observations into pointings of a mosaic and displaying the result is given in ```scripts/mosaic_stack.cmx```.

A simple example of stacking multiple observations with position shifts into pointings of a mosaic and displaying the result is given in ```scripts/mosaic_stack_with_shifts.cmx```.

A simple example of stacking multiple observations into pointings of a mosaic, removing independent models from each pointing, and displaying the result is given in ```scripts/mosaic_stack_with_models.cmx```.
