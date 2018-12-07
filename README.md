# Database-Management-Project
Consists of a database to manage inventions, implemented using postgres.

The project has been implemented as a part of Semester 6 course project. </br>


Invention Management System consists of a database, keeping a record and managing
inventions and details associated with it. We keep a track of the invention, the inventor
associated with the invention, details associated with the invention like the awards it
received or if it has patents, which field it belongs to etc. The following are the entities
incorporated in the project:</br>
</br>
● Invention: The details about the invention consist of a unique id for each invention, name of
the invention, the name of the inventor(s), field to which the invention belongs,
awards it was nominated for or it received and date of invention. An invention can
belong to multiple categories. There could be multiple inventors for one particular
invention.</br>
</br>
● Inventor: The details of the inventor will consist of inventor id, inventor’s name,
country, date of birth, the invention(s) he/she was a part of. There could be
multiple inventions by one particular inventor.</br>
</br>
● Awards: Contains details about the awards received by the inventions, number
of members in the jury and year of receiving the award.</br>
● Field: Contains the category under which the invention falls like the field name
and its code.</br>
</br>
● Patents: Store details about patents of the inventions like patent number, patent
name and patent id.</br>
There is an aggregation between invention, inventor and awards with two relations
receive and nominated.</br>
