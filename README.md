<div align="center">
  <img src=_static/mkite-logo.svg width="500"><br>
</div>

# Welcome to the mkite suite

mkite is a suite of tools for running high-throughput materials simulations in distributed computing platforms.
The mkite suite decouples the production database from client workers, facilitating scaling of simulations across heterogeneous computing environments.
The infrastructure enables exploration of combinatorial materials spaces using workflows, recipes, data visualizations, and more.

Some advantages of mkite:

- It stores and organizes complex materials workflows on databases. For example, mkite allows creating workflows with more than one parent input branch (say, interfaces between solids and molecules).
- The server is agnostic to the computing environments where the tasks are performed, and the clients are unaware of the production database. This facilitates distributing the tasks across heterogeneous computing systems.
- It provides textual descriptions for workflows, and enables adapting them on-the-fly. This helps as a "lab notebook" for computational materials scientists.
- It is adaptable to many software packages and inputs. The recipe system also interacts well with other libraries, such as ASE, pymatgen, cclib, and more.

## Documentation

General tutorial for `mkite` and its plugins are available in the [main documentation](https://mkite.org).

## Contributions

Contributions to the entire mkite suite are welcomed.
You can send a pull request or open an issue for this plugin or either of the packages in mkite.
When doing so, please adhere to the [Code of Conduct](CODE_OF_CONDUCT.md) in the mkite suite.

The mkite package was created by Daniel Schwalbe-Koda <dskoda@llnl.gov>.

## License

The mkite suite is distributed under the following license: Apache 2.0 WITH LLVM exception.

All new contributions must be made under this license.

SPDX: Apache-2.0, LLVM-exception

LLNL-CODE-848161
