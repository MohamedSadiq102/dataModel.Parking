[![Status badge](https://img.shields.io/badge/status-draft-red.svg)](RELEASE_NOTES)
[![Build badge](https://img.shields.io/travis/smart-data-models/dataModel.Parking.svg "Travis build status")](https://travis-ci.org/smart-data-models/dataModel.Parking/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
# Parking Harmonized Data Models

These data models are intended to model entities relevant for parking use cases
in smart cities scenarios. When feasible these models reuse types, properties
and enumerations from
[DATEX II version 2.3](http://www.datex2.eu/content/parking-publications-extension-v10a).
A data dictionary for DATEX II terms can be found at
[http://datexbrowser.tamtamresearch.com/](http://datexbrowser.tamtamresearch.com/).

Nonetheless, these data models are intended to NGSI-based systems and many
simplifications has been made with respect to DATEX II version 2.3.

The main entity types identified are:

-   [`OffStreetParking`](https://swagger.lab.fiware.org/?url=https://smart-data-models.github.io/dataModel.Parking/OffStreetParking/swagger.yaml). An offstreet parking
    site with explicit entries and exits.
-   [`ParkingAccess`](https://swagger.lab.fiware.org/?url=https://smart-data-models.github.io/dataModel.Parking/ParkingAccess/swagger.yaml). An access point to an off
    street parking site.
-   [`OnStreetParking`](https://swagger.lab.fiware.org/?url=https://smart-data-models.github.io/dataModel.Parking/OnStreetParking/swagger.yaml). An on street, free entry
    (but might be metered) parking zone which contains at least one ore more
    adjacent parking spots.
-   [`ParkingGroup`](https://swagger.lab.fiware.org/?url=https://smart-data-models.github.io/dataModel.Parking/ParkingGroup/swagger.yaml). A group of parking spots.
    Granularity level can vary. It can be an storey on a parking garage, an
    specific area belonging to a big parking lot etc or just a group of spots,
    differentiated for an specific purpose (usage, restrictions, etc.).
-   [`ParkingSpot`](https://swagger.lab.fiware.org/?url=https://smart-data-models.github.io/dataModel.Parking/ParkingSpot/swagger.yaml). An individual, usually monitored,
    parking spot.
