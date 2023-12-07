# EDA
Assignment_3a
## Description 

The provided dataset "on_the_move_clean" in CSV format contains historical information about advertisements for runaway slaves in the United States. The dataset includes details from various newspaper publications and contains informations and characteristics of enslaved individuals and their enslavers.

## Tabes of Variables

| Header                      | Description                          | Datatype                         |
|-----------------------------| ------------------------------------ | ---------------------------------|
|adv_publication_date         | date of advertisment's publication   | string/object (converted to date)|
|newspaper.name               | the name of the Newspaper            | string/object                    |
|runaway.racial_description   | racial description of the runaway    | string/object                    |
|runaway.approximate_height   | approximate height of the runaway    | string/object                    |
|runaway.physical_description | physical description                 | string/object                    |
|enslaved_person.gender       | gender                               | string/object                    |
|enslaved_person.skills       | occupation, skills                   | string/object                    |
|enslaved_person_name         | name of the runaway                  | string/object                    |
|runaway_location_name        | the location from which they ran away| string/object                    |
|runaway_location_city        | the city from which they ran awway   | string/object                    |
|runaway_location_state       | the state from which they ran away   | string/object                    |
|enslaver.gender              | gender of the enslaver               | string/object                    |
|enslaver.type                | some characteristics of the slavery  | string/object                    |
|enslaver_location.name       | the of the location of the enslaver  | string/object                    |
|enslaver_location.city       | the city of the enslaver             | string/object                    |
|enslaver_location.state      | the state of the enslaver            | string/object                    |
|runaway_reward.amount        | reward amount                        | integer                          |
|runaway_reward.criteria      | criteria for collecting the reward   | string/object                    |

## Source
The source of this dataset is an open access database.
https://app.freedomonthemove.org/search#content

The project "Freedom on the Move is a joint effort from various Institutes and Universities.
https://freedomonthemove.org/#about

## Experimental Data Analysis (EDA)
The jupyter notebook file contains an Experimental Data Analysis on this dataset.

With a first overview of the dataset we can see that many questions arise about the gender distribution and the related skills mentioned in the advertisements. What were the most common skills mentioned by the enslavers for female and male runaways?
Another important question is, what states were most of the fugitives from? The data-based answer can be answered with the help of relevant literature on slavery conditions in the various Northern states.
Another interesting question could be about the Newspapers where it was most common for advertisments of runaway slaves to be published. What does this mean about their ideology regarding slavery? Who was the owner of these newspapers? For this questions there is a need to look for other sources too.



##
