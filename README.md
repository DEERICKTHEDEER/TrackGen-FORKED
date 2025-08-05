# [TrackGen FORKED](https://deerickthedeer.github.io/TrackGen-FORKED/)

The simplest tropical cyclone track map generator. This is an enhanced fork of [TrackGen](https://trackgen.codingcactus.repl.co/) by [CodingCactus](https://github.com/Coding-Cactus) — among the changes made here are:

- Support for multiple Blue Marble maps
- Ability to import and export your tracks for usage on other projects, in JSON and HURDAT format
- Support for raw URLs, such as those hosted on Github Gists and Pastebin
- (Technically) more optimized code
- Dark theme!
- Support for STORMS database files
- Full PWA support, letting you use this offline and without having to download a ~250MB map file
- (BY DERECK RODRIGUEZ) Added F13 Color Scheme, Modern HURDAT scheme is still the alternate colorway

## Usage

- Each line is a point to be plotted on the map
- Each field gives information about the point to be plotted

| Field      | Description | Example | Required? |
|:----------:|:------------|:-------:|:---------:|
| Name       | Name of the cyclone, used to join points together | Iota | <ul><li> [ ] No </li></ul> |
| Latitude   | Latitude coordinate, choose either °N or °S instead of using negative numbers | 52 °N | <ul><li> [x] Yes </li></ul> |
| Longitude  | Longitude coordinate, choose either °E or °W instead of using negative numbers | 1°W | <ul><li> [x] Yes </li></ul> |
| Wind Speed | Wind speed at that point, leave blank for unknown speeds | 25 kt | <ul><li> [ ] No </li></ul> |
| Stage      | Stage of tropical cyclone (determines shape used for point) | Tropical Cyclone | <ul><li> [x] Yes </li></ul> |
