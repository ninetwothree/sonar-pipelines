### Workflow Input Parameters

| Parameter Name       | Type    | Required | Default Value | Description                                           |
|----------------------|---------|----------|---------------|-------------------------------------------------------|
| `SONAR_TOKEN`  | secret  | Yes      | —             | Sonar token should be passed from caller repo                  |
| `SONAR_DOMAIN_NAME`  | string  | Yes      | —             | Domain name of the SonarQube server.                  |
| `FETCH_DEPTH`        | number  | No       | 0             | Depth of the commit history to fetch.                 |
| `RUN_ESLINT`         | boolean | No       | true          | Flag to determine if ESLint should run.               |
| `RUN_PRECOMMIT`      | boolean | No       | true          | Flag to determine if pre-commit checks should run.    |
| `RUN_CFN_LINT`       | boolean | No       | true          | Flag to determine if cfn-lint should run.             |
| `RUN_TF_LINT`        | boolean | No       | true          | Flag to determine if tflint should run.               |
| `PYTHON_VERSION`     | string  | No       | '3.11'        | Python version to be used in report generation.       |
| `RUN_FLAKE8`         | boolean | No       | false         | Flag to determine if flake8 report is needed.         |
| `ENABLE_COREPACK`    | boolean | No       | false         | Flag to determine if corepack should be enabled.      |
| `NODE_VERSION`       | string  | No       | '20.12.2'     | Node.js version to run (e.g., 20.12.2).               |
