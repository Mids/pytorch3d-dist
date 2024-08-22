# Usage

## Rye
```
dependencies = [
    "pytorch3d==0.7.7",
]

[[tool.rye.sources]]
name = "pytorch3d"
url = "https://mids.github.io/pytorch3d-dist/"
type = "find-links"
```

## pip
```
pip install --find-links "https://mids.github.io/pytorch3d-dist/" pytorch3d
```
