# Heroku Buildpack pdf2json

This is a Heroku buildpack for using `pdf2json` in your project.

The sources for this pack are fetched from [pdf2json repository](https://github.com/flexpaper/pdf2json/releases).

## Usage

Add the buildpack to your application.

```bash
heroku buildpacks:add https://github.com/calculojuridico/heroku-buildpack-pdf2json.git -a my_app
```

You can verify installation by running the following.

```bash
heroku run "pdf2json -v" -a my_app
```
