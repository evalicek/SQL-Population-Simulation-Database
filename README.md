This is the exported SQL databased from an in progress Python Population Simulation.
The data can be used to explore basic visualizations of how a population might develop by chance alone.

Database Details:

The main table is "People" which houses demographic information and ancestry information. The date format is in weeks where applicable.

The auxiliary tables include "Attributes" and "Personality"; the components of each table is heritable to some degree, but does currently impact fitness.

The simulation starts with 30 individuals with randomized ages.
5000 weeks are passed, with an entry added to the database whenever a new individual is born.
After an individual reaches the week that is their birth_date plus their lifespan, they die and can no longer reproduce.
