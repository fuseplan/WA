# Weather App

Live Weather App made using Open Weather Map Api to fetch current temperature,wind speed and humidity

## https://openweathermap.org/current

#### API Call

```http
  https://api.openweathermap.org/data/2.5/weather?lat={lat}&lon={lon}&appid={API key}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

| Parameter | Description                                                                                                                                                               |
| :-------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `lat`     | **Required**. Latitude. If you need the geocoder to automatic convert city names and zip-codes to geo coordinates and the other way around, please use our Geocoding API  |
| `lon`     | **Required**. Longitude. If you need the geocoder to automatic convert city names and zip-codes to geo coordinates and the other way around, please use our Geocoding API |
| `appid`   | **Required**. Your unique API key (you can always find it on your account page under the "API key" tab)                                                                   |
| `mode`    | **Optional**. Response format. Possible values are xml and html. If you don't use the mode parameter format is JSON by default.                                           |
| `unit`    | **Optional**. Units of measurement. standard, metric and imperial units are available. If you do not use the units parameter, standard units will be applied by default.  |
|           |
| `lang`    | **Optional**.You can use this parameter to get the output in your language. Learn more                                                                                    |

## 🛠 Skills

Javascript, HTML, CSS...

## Run Locally

Clone the project

```bash
  git clone https://github.com/fuseplan/WA.git
```

Go to the project directory

```bash
  cd WA
```

Start the server

```bash
  npm run start
```
![fuselogo](https://github.com/fuseplan/WA/assets/40660678/e5c385dd-cb05-44e6-8b26-d35fa13e7421)



## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)
