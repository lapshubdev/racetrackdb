## RacetrackDB

Welcome to RacetrackDB, an open-source database containing information about racetracks around the world! This repository is part of the LapsHub project, and its mission is to provide an up-to-date, community-maintained resource for motorsport enthusiasts, track-day organizers, and developers.

### Features
- JSON format for easy integration.
- Contributions welcome from anyone.
- Built with community support to keep track data current and accurate.

### Why Contribute?
Racetracks change over time—names, configurations, or even closures. With your help, RacetrackDB can stay relevant and accurate for all motorsport enthusiasts.

### Usage
The database is stored in a racetracks.json file in this repository. It contains the following fields for each racetrack:
- **ID**: Unique identifier for the racetrack.
- **Name**: The official name of the racetrack.
- **Avatar**: Path to an image representing the racetrack.
- **Avatar Panorama**: Path to a panoramic image of the racetrack.
- **Length**: Track length (in miles).
- **GPS Shape**: A series of latitude and longitude points outlining the track.
- **Configurations**: List of different layouts or configurations for the track.
- **Finish Line Polygon**: Coordinates defining the finish line area.
- **GPS Location**: Central latitude and longitude of the track.

Here is an example entry:

```json
{
  "id": "582f9560-cce5-4f73-b13f-2d1b5f1a0a17",
  "name": "Road America",
  "avatar": "ra.png",
  "avatarPanorama": "ra-panorama.png",
  "length": 4.048,
  "gpsShape": [
    [
      43.805061,
      -87.997781
    ],
    [
      43.804079,
      -87.989506
    ],
    [
      43.791934,
      -87.989167
    ],
    [
      43.793535,
      -88.003849
    ]
  ],
  "configurations": null,
  "finishLinePolygon": [
    {
      "latitude": 43.797910625122995,
      "longitude": -87.98975976076265
    },
    {
      "latitude": 43.797796402224044,
      "longitude": -87.98975841965814
    },
    {
      "latitude": 43.79779833820717,
      "longitude": -87.98944191899439
    },
    {
      "latitude": 43.79791352909216,
      "longitude": -87.9894446012034
    }
  ],
  "gpsLocation": {
    "latitude": 43.797868,
    "longitude": -87.989633
  }
}
```

Feel free to clone this repository and use the data in your projects. If you notice any errors or missing tracks, please contribute back to the project!

### How to Contribute
1. Check out the [Contributing Guidelines](CONTRIBUTING.md).
2. Open an issue or submit a pull request.
3. Join our community to discuss and improve the database.

### License
This project is licensed under the MIT License. See the LICENSE file for details.

### Get in Touch
Join our community on [Discord](https://discord.gg/R8nzCjyQ) or follow our updates on Reddit at [r/LapsHub](https://reddit.com/r/LapsHub).
[Visit us](https://www.lapshub.com)
