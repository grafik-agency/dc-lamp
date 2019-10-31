# LAMP Stack for Docker

- Debian GNU/Linux 9 (stretch)
- Apache 2.4
- MariaDB 10.3
- PHP 7.3 (Additional Versions: [7.2.x] | [7.1.x] | [5.6.x])

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
