# demo2024.2
# №1
Сначала я рассчитываю  IP-адреса
# Таблица
|Имя устройства  |Интерфейс           |IPv4            |Маска/Префикс   |Шлюз            |
|  ------------- | -------------      | -------------  |  ------------- |  -------------       |
|ISP             |ens33              |10.12.29.10     |/24             |10.12.29.10         |
|                |ens35             |192.168.0.162   |/30             |                      |

|                |ens36             |192.168.0.163  |/30             |                      |
|HQ-R            |ens192              |192.168.0.161   |/30             |192.168.0.162       |
|                |ens224              |192.168.0.1     |/25             |                      |
|BR-R            |ens192              |192.168.0.164   |/30             |192.168.0.163       |
|                |ens224              |192.168.0.129  |/27             |                      |
|HQ-SRV          |ens192              |192.168.0.2   |/25             |192.168.0.1           |
|BR-SRV          |ens192              |192.168.0.156   |/27             |192.168.0.129       |

# Топология
