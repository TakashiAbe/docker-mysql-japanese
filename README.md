## 概要

### MySQL 日本最適化

- ロケールを"ja_JP.UTF-8"に
- タイムゾーンを"ASIA/Tokyo"に
- MySQLのデフォルトの文字コードを"utf8mb4"に
- MySQLのデフォルトの照合順序を"utf8mb4_bin"に

## 使い方

```
docker run --name mysql-japanese -e MYSQL_ROOT_PASSWORD=mysql -d -p 3306:3306 takashiabe/mysql-japanese
```

## License

MIT