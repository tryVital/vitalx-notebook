## Authentication

### Running notebooks locally

For notebooks that run locally on an edge device, you can sign in as your [Vital Dashboard](https://app.tryvital.io) user with the `vitalx-cli` command line tool.

```python
poetry run vitalx-cli auth login
```

Once you have logged in, a permanent sign-in session is stored at `~/.vitalx/`.


### Running notebooks in deployed services

For notebooks or deployed services, you can either:

1. Pass the API Key when instantiating the Query Executor; or
2. Set the API Key as `VITAL_API_KEY` in the environment.
