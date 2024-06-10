## Hyvor Point - Open-source IP Geolocation Database & Libraries

[WORK IN PROGRESS]

Hyvor Point is an open-source IP geolocation database. The data is built from ground up using many public sources (WHOIS data, etc.) and our own methods, and is updated monthly. The database is available in CSV, JSON, and MMDB formats. Our goal is to provide a highly accurate free and open-source IP geolocation database for developers.

Visit [**point.hyvor.com**](https://point.hyvor.com) for more information.

### Client Libraries 📚

We provide client libraries for popular programming languages to make it easy to use the database in your applications. All of these libraries handle the database files and provide easy-to-use functions to get the location of an IP address.

-   [Python](TODO)
-   [Node.js](TODO)
-   [PHP](TODO)
-   [Java](TODO)
-   [Ruby](TODO)

#### Example in Python

```python
from hyvor_point import IP

ip = IP('34.49.208.18')
location = ip.location()

print(location.country)
print(location.state)
print(location.city)
print(location.latitude)
print(location.longitude)
print(location.continent)
print(location.timezone)
```

### License 📜

The database is licensed under the **Open Data Commons Open Database License (ODbL)** (version 1.0).

-   [ODbL LICENSE](LICENSE)
-   [Easy-to-read summary of ODbL](https://opendatacommons.org/licenses/odbl/summary/)

These are the key points of the license (not a substitute for the full license):

-   **Free to Use** - You are free to use the database in any way you want.
-   **Attribution** - You must attribute any public use of the database, or works produced from the database, by giving credit to Hyvor Point.
-   **Share Alike** - If you make any changes to the database, you must share the changes under the same license.

All client libraries are licensed under the **MIT License**.

### Sustainability 🌱

The database will **forever be free and open-source**. We are committed to keeping it up-to-date and accurate. We will not publish paid version of the database. Whatever the accuracy we achieve, it will be available for everyone for free.

Here are some ways you can support us and help us keep the project sustainable:

-   Use our paid SaaS
    -   [Hyvor Talk](https://talk.hyvor.com) - commenting platform
    -   [Hyvor Blogs](https://blogs.hyvor.com) - blogging platform
    -   [Fortguard](https://fortguard.io) - spam detection
-   Support us on [GitHub Sponsors](https://github.com/sponsors/hyvor)

### Links 🔗

-   [Website & Documentation](https://point.hyvor.com)
-   [GitHub Repository](https://github.com/hyvor/point)
-   [Github Sponsors](https://github.com/sponsors/hyvor)
