# 🛣️ GeoJSON Traffic Data Mockup

This repository provides sample **GeoJSON traffic-related data** for development, testing, prototyping, and demonstration purposes. These mock datasets simulate real-world road traffic information such as **road names**, **current speed**, **free-flow speed**, **congestion**, **road closures**, **travel time**, and more.

## 📁 Repository Structure

```
.
├── alam_sutera_traffic_3.geojson
├── incident.geojson
├── intersection.geojson
└── README.md
```

- `.geojson` files contain sample traffic scenarios.
- Each file is formatted to comply with the [GeoJSON specification](https://datatracker.ietf.org/doc/html/rfc7946).

## 📌 Features Included in Mock Data

Each `Feature` in the GeoJSON may contain:

| Property         | Description                                                 |
|------------------|-------------------------------------------------------------|
| `name`           | Name of the road or segment                                 |
| `speed`          | Current vehicle speed in km/h                               |
| `freeFlowSpeed`  | Expected speed under no congestion                          |
| `congested`      | Boolean indicating traffic congestion                       |
| `confidence`     | Confidence score in the data (0–1 scale)                    |
| `roadClass`      | Classification of the road (e.g., motorway, primary)        |
| `roadClosure`    | Boolean or status indicating if the road is closed          |
| `travelTime`     | Estimated travel time (in seconds)                          |
| `length`         | Length of the road segment (in meters)                      |

## 🧪 Use Cases

- Frontend prototyping (e.g., Mapbox, Leaflet, Kepler.gl)
- Backend API testing
- Visualization in dashboards (e.g., Grafana, Kibana)
- Development of traffic monitoring systems

## 🚧 Disclaimer

> This data is **mock** data. It does not represent real-time or real-world traffic conditions. Do not use it for navigation or critical applications.

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

## 🤝 Contributions

Feel free to submit pull requests with new mock data for other regions or traffic scenarios. All contributions should follow the [GeoJSON standard](https://geojson.org/) and include proper documentation.
