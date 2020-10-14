About r-pmcmrplus
=================

Home: https://CRAN.R-project.org/package=PMCMRplus

Package license: GPL (>= 3)

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/r-pmcmrplus-feedstock/blob/master/LICENSE.txt)

Summary: For one-way layout experiments the one-way ANOVA can be performed as an omnibus test. All-pairs multiple comparisons  tests (Tukey-Kramer test, Scheffe test, LSD-test)  and many-to-one tests (Dunnett test) for normally distributed  residuals and equal within variance are available. Furthermore, all-pairs tests (Games-Howell test, Tamhane's T2 test,  Dunnett T3 test, Ury-Wiggins-Hochberg test) and many-to-one (Tamhane-Dunnett Test) for normally distributed residuals  and heterogeneous variances are provided. Van der Waerden's normal scores test for omnibus, all-pairs and many-to-one tests is provided for non-normally distributed residuals and homogeneous variances. The Kruskal-Wallis, BWS and Anderson-Darling omnibus test and all-pairs tests (Nemenyi test, Dunn test, Conover test, Dwass-Steele-Critchlow- Fligner test) as well as many-to-one (Nemenyi test, Dunn test, U-test) are given for the analysis of variance by ranks.  Non-parametric trend tests (Jonckheere test, Cuzick test, Johnson-Mehrotra test, Spearman test) are included.  In addition, a Friedman-test for one-way ANOVA with repeated  measures on ranks (CRBD) and Skillings-Mack test for unbalanced  CRBD is provided with consequent all-pairs tests (Nemenyi test,  Siegel test, Miller test, Conover test, Exact test) and many-to-one tests (Nemenyi test, Demsar test, Exact test).  A trend can be tested with Pages's test. Durbin's test  for a two-way balanced incomplete block design (BIBD) is given  in this package as well as Gore's test for CRBD with multiple observations per cell is given.  Outlier tests, Mandel's k- and h statistic as well as functions for Type I error and Power  analysis as well as generic summary, print and plot methods  are provided.

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=2420&branchName=master">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-pmcmrplus-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_r_base3.6target_platformlinux-64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=2420&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-pmcmrplus-feedstock?branchName=master&jobName=linux&configuration=linux_64_r_base3.6target_platformlinux-64" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_r_base4.0target_platformlinux-64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=2420&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-pmcmrplus-feedstock?branchName=master&jobName=linux&configuration=linux_64_r_base4.0target_platformlinux-64" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base3.6target_platformosx-64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=2420&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-pmcmrplus-feedstock?branchName=master&jobName=osx&configuration=osx_64_r_base3.6target_platformosx-64" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.0target_platformosx-64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=2420&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-pmcmrplus-feedstock?branchName=master&jobName=osx&configuration=osx_64_r_base4.0target_platformosx-64" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--pmcmrplus-green.svg)](https://anaconda.org/conda-forge/r-pmcmrplus) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-pmcmrplus.svg)](https://anaconda.org/conda-forge/r-pmcmrplus) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-pmcmrplus.svg)](https://anaconda.org/conda-forge/r-pmcmrplus) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-pmcmrplus.svg)](https://anaconda.org/conda-forge/r-pmcmrplus) |

Installing r-pmcmrplus
======================

Installing `r-pmcmrplus` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `r-pmcmrplus` can be installed with:

```
conda install r-pmcmrplus
```

It is possible to list all of the versions of `r-pmcmrplus` available on your platform with:

```
conda search r-pmcmrplus --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating r-pmcmrplus-feedstock
==============================

If you would like to improve the r-pmcmrplus recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-pmcmrplus-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@conda-forge/r](https://github.com/conda-forge/r/)

