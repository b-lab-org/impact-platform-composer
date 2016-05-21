# Impact Platform: Composer
[Docker](https://www.docker.com/) container for [Composer](https://getcomposer.org/)

## Overview
Use with the [data container](https://github.com/b-lab-org/impact-platform-data).

Run a composer command from the `/data/www` directory.

## Docker-Compose Usage
```
composer:
    image: impactbot/impact-platform-composer
    volumes_from:
        - data
```
