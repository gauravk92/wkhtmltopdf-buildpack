# wkhtmltopdf Buildpack

This is a [Heroku buildpack][0] for bundling a compatible [wkhtmltopdf][1] binary with your environment.

## Versions

* Buildpack:   `1.0`
* wkhtmltopdf: `0.12.4`

## Usage

This buildpack only installs wkhtmltopdf, it isn't very useful by itself. 

```bash
$ heroku buildpacks:add 'https://github.com/gauravk92/wkhtmltopdf-buildpack.git'
```
