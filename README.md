# MLModels

Repository to temporary store ML models for inference in O2 and O2Physics. The repository will be deleted when a better solution is available.

## How it works

Create a folder for your project in `models` and add the desired models. Then open a PR.
Some time after the PR is merged (a tag of this repository and an update of the relative alidist recipe is needed), you can access your models from O2 and O2Physics using the environment variable `MLMODELS_ROOT` (e.g. with `std::getenv("MLMODELS_ROOT")`), which contains the path to the repository root directory for the current installation.
