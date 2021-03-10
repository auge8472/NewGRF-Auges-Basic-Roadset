# AB-Roads

An attempt to build a simple road-GRF, satisfying my own requirements to have paths and streets for rural and urban areas, interurban streets and tram tracks for urban areas and interurban connections. AB-Roads means literally Auge's Basic Roads.

This set is licenced under the terms of GPL2. You can find a copy of the license in the file LICENSE.md.

## Roads

These are the planned road types.

| Name                        | Speed Limit | Vehicles | Houses | Rail Crossing | Tram | Trolley | Introduction Date |
| --------------------------- | ----------- | -------- | ------ | ------------- | ---- | ------- | -----------------:|
| foot path                   | 0 km/h      | No       | Yes    | Yes           | No   | No      | 0                 |
| precinct/pedestrian zone    | 0 km/h      | No       | Yes    | Yes           | No   | No      | 1960              |
| dirt road                   | 30km/h      | Yes      | No     | Yes           | No   | No      | 0                 |
| concrete accommodation road | 50km/h      | Yes      | No     | Yes           | No   | No      | 1955              |
| set paved town road         | 40km/h      | Yes      | Yes    | Yes           | Yes  | Yes     | 0                 |
| asphalt town road           | 50km/h      | Yes      | Yes    | Yes           | Yes  | Yes     | 1960              |
| set paved country road      | 70km/h      | Yes      | No     | Yes           | No   | No      | 0                 |
| asphalt country road        | 90km/h      | Yes      | No     | Yes           | No   | No      | 1970              |
| highway (1st generation)    | 90km/h      | Yes      | No     | No            | No   | No      | 1930              |
| highway (2nd generation)    | 120km/h     | Yes      | No     | No            | No   | No      | 1975              |

## Trams

These are the planned tram types.

| Name                         | Speed Limit | Overhead Wires | Rail Crossing | Introduction Date |
| ---------------------------- | ----------- | -------------- | ------------- | -----------------:|
| old town road tram tracks    | 45km/h      | No             | Yes           | 0                 |
| old town road tram tracks    | 45km/h      | Yes            | Yes           | 0                 |
| new town road tram tracks    | 55km/h      | Yes            | Yes           | 1960              |
| old country site tram tracks | 60km/h      | No             | Yes           | 0                 |
| old country site tram tracks | 60km/h      | Yes            | Yes           | 0                 |
| new country site tram tracks | 85km/h      | Yes            | Yes           | 1960              |
