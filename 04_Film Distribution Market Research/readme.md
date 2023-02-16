# Film Distribution Market Research

## Project description

**Aim** - to study the Russian film distribution market and identify current trends

## Data

The **mkrf_movies** table contains information from the rental license registry. One film can have several distribution certificates.
- title - the title of the movie;
- puNumber — rental certificate number;
- show_start_date — movie premiere date;
- type - movie type;
- film_studio - production studio;
- production_country - country of origin;
- director - director;
- producer - producer;
- age_restriction - age category;
- refundable_support — amount of state support refundable funds;
- nonrefundable_support - the amount of non-refundable state support funds;
- financing_source - source of government funding;
- budget - the total budget of the movie;
- ratings — movie rating on KinoPoisk;
- genres - the genre of the movie.

The **mkrf_shows** table contains information about movie screenings in Russian cinemas.
- puNumber — rental certificate number;
- box_office - fees in rubles.

## Resume

- Track the dynamics of fees by years
- Analyze what affects film box office
- Select films with state support and evaluate their fees and ratings
- Find patterns by which grants are allocated

## Skills and tools 

- Data preprocessing
- Hypothesis testing
- python
- pandas
- numpy
- matplotlib
- seaborn
