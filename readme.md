# Demo Helm Semantic Versioning using GitHub Actions

This repository has a single Angular web application which is packaged into a Container that has defined [Helm Chart](content-web/charts).

Helm removed many commands with the release of Helm 3.7 and also now adheres more strictly to the semver 2 scheme, so this repository shows how you version both your Chart and Application when packaging and pushing a Helm Chart.

You can view the [GitHub Action workflow](.github/workflows/content-web.yml) that does the heavy lifting.