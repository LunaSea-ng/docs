# :fontawesome-solid-globe: Web

!!! warning
	This section is outdated.

LunaSea-ng can be hosted as a web application for usage within any modern browser!

!!! info
	If you want a stable experience, stick with stable releases. Want to test new builds of LunaSea-ng? Read about the [build channels](../getting-started/build-channels.md) to make the right choice!

## Hosted Builds

_Channel(s)_: `Stable`, `Develop`

All web releases of LunaSea-ng are available on hosted instances by the LunaSea-ng team! All communication and data stored is client-side, but there are some limitations of the platform which can be [viewed here](../getting-started/platform-restrictions.md).

=== "Stable"
	Access the stable release [here](https://web.lunasea.app/)!

=== "Develop"
	Access the develop release [here](https://dev.web.lunasea.app/)!

## Docker

_Channel(s)_: `Stable`, `Develop`

All web releases of LunaSea-ng are also available in officially hosted Docker images! There is currently only one value that needs to be configured which is the port mapping. LunaSea-ng functions as a frontend application with all data being stored client-side.

=== "Stable"
	```
	docker run -p 80:80 ghcr.io/lunasea-ng/lunasea:stable
	```

=== "Develop"
	```
	docker run -p 80:80 ghcr.io/lunasea-ng/lunasea-ng:dev
	```

You can also build this image yourself, if you prefer that. See [Dockerfile](https://github.com/LunaSea-ng/LunaSea-ng/blob/master/Dockerfile). This assumes that you have [Docker](https://www.docker.com/) installed and setup.

1. **Clone the repository**
    ```bash
    git clone https://github.com/LunaSea-ng/LunaSea-ng
    cd LunaSea-ng
    ```

2. **Build**
    ```bash
    docker build --tag lunasea-ng .
    ```

3. **Run**
    ```bash
    docker run -p 80:80 lunasea-ng
    ```

!!! warning
	Building this way will result in using the development channel.

## GitHub Releases

_Channel(s)_: `Stable`, `Develop`

_Format(s)_: `.zip`

All releases are available on GitHub via the [Releases](https://github.com/LunaSea-ng/LunaSea-ng/releases) page!
