About vtk-feedstock
===================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/vtk-feedstock/blob/main/LICENSE.txt)

Home: http://www.vtk.org/

Package license: BSD-3-Clause

Summary: The Visualization Toolkit (VTK) is an open-source, freely available software system for 3D computer graphics, modeling, image processing, volume rendering, scientific visualization, and information visualization.


Development: https://gitlab.kitware.com/vtk/vtk

Documentation: https://vtk.org/documentation

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-vtk--base-green.svg)](https://anaconda.org/freecad/vtk-base) | [![Conda Downloads](https://img.shields.io/conda/dn/freecad/vtk-base.svg)](https://anaconda.org/freecad/vtk-base) | [![Conda Version](https://img.shields.io/conda/vn/freecad/vtk-base.svg)](https://anaconda.org/freecad/vtk-base) | [![Conda Platforms](https://img.shields.io/conda/pn/freecad/vtk-base.svg)](https://anaconda.org/freecad/vtk-base) |

Installing vtk
==============

Installing `vtk` from the `freecad/label/dev` channel can be achieved by adding `freecad/label/dev` to your channels with:

```
conda config --add channels freecad/label/dev
conda config --set channel_priority strict
```

Once the `freecad/label/dev` channel has been enabled, `vtk-base` can be installed with `conda`:

```
conda install vtk-base
```

or with `mamba`:

```
mamba install vtk-base
```

It is possible to list all of the versions of `vtk-base` available on your platform with `conda`:

```
conda search vtk-base --channel freecad/label/dev
```

or with `mamba`:

```
mamba search vtk-base --channel freecad/label/dev
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search vtk-base --channel freecad/label/dev

# List packages depending on `vtk-base`:
mamba repoquery whoneeds vtk-base --channel freecad/label/dev

# List dependencies of `vtk-base`:
mamba repoquery depends vtk-base --channel freecad/label/dev
```




Updating vtk-feedstock
======================

If you would like to improve the vtk recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`freecad` channel, whereupon the built conda packages will be available for
everybody to install and use from the `freecad` channel.
Note that all branches in the conda-forge/vtk-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@Maxyme](https://github.com/Maxyme/)
* [@Tobias-Fischer](https://github.com/Tobias-Fischer/)
* [@basnijholt](https://github.com/basnijholt/)
* [@ccordoba12](https://github.com/ccordoba12/)
* [@dfroger](https://github.com/dfroger/)
* [@downiec](https://github.com/downiec/)
* [@grlee77](https://github.com/grlee77/)
* [@jasonb5](https://github.com/jasonb5/)
* [@marcelotrevisani](https://github.com/marcelotrevisani/)
* [@matthiasdiener](https://github.com/matthiasdiener/)
* [@msarahan](https://github.com/msarahan/)
* [@patricksnape](https://github.com/patricksnape/)
* [@tadeu](https://github.com/tadeu/)

