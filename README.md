About mypackage
===============

Home: 

Package license: 

Feedstock license: BSD-3-Clause

Summary: 



Current build status
====================


<table><tr>
    <td>CircleCI</td>
    <td>
      <a href="https://circleci.com/gh/mehdizadehm/mypackage-feedstock">
        <img alt="Linux" src="https://img.shields.io/circleci/project/github/mehdizadehm/mypackage-feedstock/master.svg?label=Linux">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-mypackage-green.svg)](https://anaconda.org/meissam/mypackage) | [![Conda Downloads](https://img.shields.io/conda/dn/meissam/mypackage.svg)](https://anaconda.org/meissam/mypackage) | [![Conda Version](https://img.shields.io/conda/vn/meissam/mypackage.svg)](https://anaconda.org/meissam/mypackage) | [![Conda Platforms](https://img.shields.io/conda/pn/meissam/mypackage.svg)](https://anaconda.org/meissam/mypackage) |

Installing mypackage
====================

Installing `mypackage` from the `meissam` channel can be achieved by adding `meissam` to your channels with:

```
conda config --add channels meissam
```

Once the `meissam` channel has been enabled, `mypackage` can be installed with:

```
conda install mypackage
```

It is possible to list all of the versions of `mypackage` available on your platform with:

```
conda search mypackage --channel meissam
```




Updating mypackage-feedstock
============================

If you would like to improve the mypackage recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`meissam` channel, whereupon the built conda packages will be available for
everybody to install and use from the `meissam` channel.
Note that all branches in the mehdizadehm/mypackage-feedstock are
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


