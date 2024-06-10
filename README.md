# Hyvor Point - Open-source IP Geolocation Database & Libraries

Hyvor Point is an open-source IP geolocation database published under the **Open Data Commons Open Database License (ODbL)**. The data is built from ground up using many public sources (WHOIS data, etc.). Data is updated monthly. The database is available in CSV, JSON, and MMDB formats. Our goal is to provide a highly accurate free and open-source IP geolocation database for developers.

Visit [**point.hyvor.com**](https://point.hyvor.com) for more information.

## Client Libraries

We provide client libraries for popular programming languages to make it easy to use the database in your applications. All of these libraries handle the database files and provide easy-to-use functions to get the location of an IP address.

-   [Python](TODO)
-   [Node.js](TODO)
-   [PHP](TODO)
-   [Java](TODO)
-   [Ruby](TODO)

### Example in Python

```python
from hyvor_point import IP

point = IP('34.49.208.18')

location = point.location()

print(location.country)
print(location.state)
print(location.city)
print(location.latitude)
print(location.longitude)
print(location.continent)
print(location.timezone)
```

## License

The database is licensed under the **Open Data Commons Open Database License (ODbL) 1.0**.

-   [LICENSE](LICENSE)
-   [Easy-to-read summary](https://opendatacommons.org/licenses/odbl/summary/) of the license

All client libraries are licensed under the **MIT License**.
