# xelatex-buildpack

Adds dependancies for nbconvert, jupyter, and pandoc. Will autodetect based on 
`requirements.txt` if one is installing jupyter and/or nbconvert.

## Usage

Append  '{ "url": "https://github.com/Daplanet/xelatex-buildpack"}' to  
`buildpack[]` in ones `app.json` file.
