# Website mergewayhq.github.io

The website can be found at [https://mergewayhq.github.io](https://mergewayhq.github.io).

The release pipeline is defined in [`.github/workflows/hugo.yaml`](https://github.com/mergewayhq/mergewayhq.github.io/blob/main/.github/workflows/hugo.yaml). 

GitHub Actions checks out [`mergewayhq/mergeway-cli`](https://github.com/mergewayhq/mergeway-cli), builds its website with Nix/devenv using `make website-build`, and deploys the generated `website/public` directory to GitHub Pages.
