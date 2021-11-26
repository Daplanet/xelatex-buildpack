![banner](https://gateway.pinata.cloud/ipfs/QmddZMebu32w5Bz3P6VvCwYv6fFAmXWJJwrKY67b3ZvTKN)

# xelatex-buildpack

Adds dependancies for nbconvert, jupyter, and pandoc. Will autodetect based on 
`requirements.txt` if one is installing jupyter and/or nbconvert.

## Usage

The following jsonpath should give a solid example to update ones' `app.json` file.

```
.buildpack[] += { url : "https://github.com/Daplanet/xelatex-buildpack" }
```
