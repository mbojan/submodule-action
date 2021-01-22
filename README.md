# GH actions as a submodule

This repository contains two branches: `master` (the main one) and `actions` which contain a sample GH workflow file. The `actions` branch is then included as a submodule at `.github/workflows` folder. This setup mocks-up sharing the action workflows across several repos.

https://github.com/mbojan/subtree-action tries similar approach, but through subtree-merging.

