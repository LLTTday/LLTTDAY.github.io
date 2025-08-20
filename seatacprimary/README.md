# SeaTac Primary Election Results Map

Interactive Leaflet map showing results from the SeaTac area primary elections. Features choropleth visualization with slate blue color scheme showing vote percentages by candidate.

## Features

- **Default "Who Won" view**: Shows winners (top vote-getters) for King County Executive race
- **Candidate-specific choropleth**: Switch between races and candidates to see vote percentage distribution
- **Three races included**:
  - SeaTac Council Position 6
  - King County Executive  
  - Metropolitan King County Council District 5
- **Desaturated basemap**: CartoDB Positron (light theme)
- **Interactive**: Click precincts for detailed vote breakdowns

## Usage

Open `index.html` in a web browser. Use the control panel to:
1. Select race (or "Who Won" view)
2. Select specific candidate (when race is chosen)
3. View legend and click precincts for details

## Data

- `seatac25.geojson`: Precinct boundaries
- `seatac primary.csv`: Vote totals by precinct and candidate

## Color Scheme

- **Choropleth**: Cool slate blue with intensity based on vote percentage
- **Winners view**: Distinct colors for each candidate
- **Scale**: Adjusted for primary election dynamics (not 50% threshold)