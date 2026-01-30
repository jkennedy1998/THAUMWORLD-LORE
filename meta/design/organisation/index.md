# organization
> a one line summary of the file ( EX : "how files are organized" )

> > scale : design

> > age : meta

> > ages : meta

> > facets : 
      facet_example : https://www.thaumworld.world/meta/design/organisation/facet_example


---

## nutshell
this is the second section of every index.md file. 
files are organized by scale of content for all in universe writing.
This repository is for in-universe canonical writing only.
Out-of-universe material (notes, TODOs, design discussions) should be minimized and placed only in /meta when necessary.

content that does not fall into a facet type will have a subsection under the nutshell

---

## organizational_scales
> file hierarchy represents scale

the format represents the following
each folder has an index.md file   in it that is the "page" for the folder's general content
> the_name_of_the_folder : examples of subfolders ideas that can be inside of the folder

this repos file hiearchy : 

> meta : out of universe material

> > design : notes about how im designing things because it helps to write it all out

> > migration : files id like to be reformatted to fit this scructured system

> > todo : things id like to write about next


> universe : information on a universal level. physics, magic, ect.

> > galaxy : information on a galaxy level. groups of planets, space history, space culture

> > solar_system : information on a solar system level. groups of planet

> > > celestial_body : information of the level of suns, planets, moons, asteroids, spaceships far outside the atmospheres.

> > > > map : information of the level of a partitioned celestial_body piece, with specified regions

> > > > > region : information of sections of the map to the approximate scale of an ~2500 foot long cube


---

## file_header
> The first section of every index.md file

the file_header section is everything between 
line 1 ( EX : "##title_of_folder_that_contains_this_file" )
and the first separator ( EX : " --- " )

between those lines are tags that give context.
those tag types are as follows.

> > scale : the level of hierarchy in the folder structure. ( EX : galaxy )

> > age : when in time a note exists ( EX : name_of_age )

> > ages : the different types of age the child contents can reference ( EX : name_of_age_1 , name_of_age_2 )

 
---

## age_and_ages
> when notes are from with relative and scaling time documentation

age is when that note exists. 
ages are relative to the parent documents.
this is defined in the file_header section of any index.md file

ages are what the child folders will use. 
this is defined in the file_header section of any index.md file

---

## facets
> links to subfiles within an index.md file

Within any spatial scale folder (galaxy, solar_system, celestial_body, map, region), 
content types are represented as sibling Markdown files that live in the same folder as the folder’s index.md.
> geography.md, life.md

this file type is called a facet.
each facet should be linked within the index.md file it belongs to within the file_header

content should fall into these facet files or be put into a section within the index.md file.

> geography.md

> life.md

> civilisation.md

> dieties.md

> technology.md

> history.md

> anecdotes.md

---

## sub_section
bound contents marked with a "##"
> EX : organizational_scales, file_header, age_and_ages, facets, sub_section, ect

each sub_section is separated from other sub_sections by the following 3 lines :

"
a new line,
a line containing "---" ,
a new line 
"