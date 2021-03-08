# Assignment 4, Information Achritecture
> Duncan Grubbs, DMS 290, 3/4/21

## Ontology
* City has a name
* City has an internal geography
* City has a skyline photo
* City has a map
* City has a transportation system
* City has major attractions
* City has a cuisine
* City has a history
* City has an economy
* City has a population
* City has a cuisine photo
* City has a major attractions photo
* City has a street life photo
* Country has a city

## Taxonomy
* City Name
    *   Skyline of City (Photo)
    *   General Information
        * Basic Introduction
        * Population
        * Location
            * Country the City is in
            * Where is it in that Country?
            * Is it a Capital?
    *   Cuisine
        *   Cuisine (Photo)
        *   Popular/Famous Cuisine
    *   Economy
        *  Major Exports
        *  GDP Ranking Within Country
    *   Geography
        * Map (Photo)
        * Internal Geography (Neighborhoods)
        * Transportation
            * Transportation System
            * Statistic about Transportation
    *   History
        *   Street Life (Photo)
        *   Founding Date
        *   Notable Events
    *   Major Attractions
        *   Major Attractions (Photo)
        *   Description of Major Attractions

## Choreography
### Ordering of City Content
In terms of the content of each city, I am using a hierarchy of information length. For example summary information such as the location and size of the city is quite short, but detailed information about the economy is longer. I decided to put shorter information first and then longer information. After the ordering from the heirarchy, I thought it was most natural to order alphabetically by heading. In terms of photos, I opted to always put them directly after their parent heading.

### Ordering of Cities
Cities are geographic locations, so I think that location should play an important role in ordering them. Population can also serve as an intuitive hierarchy for cities. In this way, we can group cities first by geographic location, for example country, and then group them by population size. The order would be alphabetical by geographic location, and then biggest to smallest in population size.
