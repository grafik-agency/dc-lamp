# LAMP Stack for Docker

Please select a branch for the desired version of PHP your project needs.

1. Debian GNU/Linux 9 (stretch)
2. Apache 2.4
3. MariaDB 10.3
4. PHP [7.3.x], [7.2.x], [7.1.x], [5.6.x]

## Getting Started

```text
git clone https://github.com/grafik-agency/dc-lamp.git my-project
cd my-project/
git fetch --all
git checkout 7.3
docker-compose build
docker-compose up -d
```

## SSH Access

```text
docker-compose exec www bash
```

## SQL Access

```text
docker-compose exec db mysql
```

[7.3.x]: https://github.com/grafik-agency/dc-lamp/tree/7.3
[7.2.x]: https://github.com/grafik-agency/dc-lamp/tree/7.2
[7.1.x]: https://github.com/grafik-agency/dc-lamp/tree/7.1
[5.6.x]: https://github.com/grafik-agency/dc-lamp/tree/5.6
