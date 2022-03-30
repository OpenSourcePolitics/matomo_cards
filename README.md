# Matomo
## Source description
Matomo is an open-source tool to do web traffic analytics.

See matomo repository [here](https://github.com/matomo-org/matomo) and the website [here](https://matomo.org/)

## How to use this project
This project gathers all data related to the [dashboard_automation](https://github.com/OpenSourcePolitics/dashboard_automation)

The project is organized followingly: each folder gives all possible cards you can create about a topic. As instance, if your data source is about employee managament, you can have a `employee` folder with this architecture.
```bash
...
├── employee
│   ├── info.yml
│   └── locales
│       └── en.yml
...
```

You have to complete the `info.yml` and locales following asked informations.
In order to understand how to create cards automatically through the Metabase API, please see [dashboard_automation documentation](https://github.com/OpenSourcePolitics/dashboard_automation/blob/master/README.md)