# LAMP Stack for Docker

- Debian GNU/Linux 9 (stretch)
- Apache 2.4
- MySQL 5.7
- PHP 7.2 (Additional Versions: [7.3] | [7.1] | [5.6])

## Getting Started

```text
git clone https://github.com/grafik-agency/dc-lamp.git my-project
cd my-project/
git fetch --all
git checkout 7.2
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

[7.3]: https://github.com/grafik-agency/dc-lamp/tree/7.3
[7.2]: https://github.com/grafik-agency/dc-lamp/tree/7.2
[7.1]: https://github.com/grafik-agency/dc-lamp/tree/7.1
[5.6]: https://github.com/grafik-agency/dc-lamp/tree/5.6
