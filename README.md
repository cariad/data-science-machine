# data-science-machine

A setup script for a data science development machine.

Includes:

- Anaconda 3 2021.11
- AWS CLI (always installs the latest release)
- Curl
- Git
- Unzip
- [wev](https://github.com/cariad/wev) and [wev-awscodeartifact](https://github.com/cariad/wev-awscodeartifact)

## Requirements

This script has been tested only in Debian 10, as the default operating system for Google Cloud virtual machines.

## Deploying

1. Create a clean Debian 10 machine.
1. Run:

    ```console
    sudo apt update -y && sudo apt install curl -y && curl -fsSL https://raw.githubusercontent.com/cariad/data-science-machine/main/bootstrap | bash -
    ```

## How do I…

### …start Jupyter?

```console
start-jupyter
```

## Licence

**data-science-machine** is released at [github.com/cariad/data-science-machine](https://github.com/cariad/data-science-machine) under the MIT Licence.

See [LICENSE](https://github.com/cariad/data-science-machine/blob/main/LICENSE) for more information.

## Author

Hello! 👋 I'm **Cariad Eccleston** and I'm a freelance DevOps and backend engineer. My contact details are available on my personal wiki at [cariad.earth](https://cariad.earth).

Please consider supporting my open source projects by [sponsoring me on GitHub](https://github.com/sponsors/cariad/).
