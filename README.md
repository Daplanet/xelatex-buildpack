![banner](https://banner.dapla.net/?utm_campaign=community-buildpacks&utm_source=github.com/daplanet/xelatex-buildpack&utm_medium=markdown)

# xelatex-buildpack

Adds dependancies for nbconvert, jupyter, and pandoc. Will autodetect based on 
`requirements.txt` if one is installing jupyter and/or nbconvert.

## Status
![Status](https://img.shields.io/badge/Life%20Cycle%20Stage-End%20of%20Life-lightgray.svg?style=flat)

## Usage

The following jsonpath should give a solid example to update ones' `app.json` file.

```
.buildpack[] += { url : "https://github.com/Daplanet/xelatex-buildpack" }
```
