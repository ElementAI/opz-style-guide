# opz-style-guide

Styles to be configured with [nitpick](https://nitpick.readthedocs.io/).

## Configure `nitpick` to use this repository style guide

Install `nitpick` in your project.

```sh
poetry add nitpick
```

Specify the style file in `pyproject.toml`

```toml
style = "https://raw.githubusercontent.com/ElementAI/opz-style-guide/main/styles/nitpick-style.toml"
```

Now when you will run flake8 your configuration will be also linted. And by
`linted` we mean that it will check that all required keys and values are in
place in the correct files.
