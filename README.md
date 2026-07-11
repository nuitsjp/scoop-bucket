# scoop-bucket

[Scoop](https://scoop.sh/) bucket for [nuitsjp](https://github.com/nuitsjp)'s tools.

## Usage

```powershell
scoop bucket add nuitsjp https://github.com/nuitsjp/scoop-bucket
scoop install nuitsjp/commit-spark
```

Manifests in `bucket/` are generated and pushed automatically by GoReleaser
on each release of the corresponding tool. Do not edit them by hand.
