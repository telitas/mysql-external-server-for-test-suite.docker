# mysql-external-server-for-test-suite.docker

A docker container for testing MySQL.

## Description

Compose [MySQL container](https://hub.docker.com/_/mysql) as a external server for [MySQL Test Suite](https://dev.mysql.com/doc/extending-mysql/8.0/en/mysql-test-suite.html).

## Usage

Up

```sh
docker compose up -d
```

and run tests.

```sh
mtr --user=root --extern password=root-secret-pw --extern host=127.0.0.1
```

## License

CC0 1.0 Universal (CC0 1.0) Public Domain Dedication

See the LICENSE.txt file or https://creativecommons.org/publicdomain/zero/1.0/ for details.
