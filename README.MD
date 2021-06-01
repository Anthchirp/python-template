# Repository template for Python projects

## Azure setup

* Point Azure to `/.azure-pipelines/azure-pipelines.yml`

## Code coverage

* In the Azure pipeline you need to store the codecov token in variable `CODECOV_TOKEN`
  The codecov documentation says this is not necessary. That is a lie.

* You may want to increase `after_n_builds: 2` in `/.codecov.yml`
