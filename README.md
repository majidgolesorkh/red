# Menuz

Easy Installation
-----------------
**Requirements !!**
- Docker

**Installation Steps**
- Install Composer dependencies: `$ docker run --rm \
    -v $(pwd):/opt \
    -w /opt \
    laravelsail/php80-composer:latest \
    composer install`
- Build and run project: `$ vendor/bin/sail up -d`