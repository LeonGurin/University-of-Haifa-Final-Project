# Final-Project
**_By:_ Leon Gurin & Almog Ben Chen**

___
# Monthly schedule
Each month we will catalouge our progress on the project as a journal.

## October 2022

This was the first month of the project in which we needed to find our footing and think what our project wanted to be.

We knew we needed to approach an instructor to create a unique project and so we starting our journey seeking different mentors, some did not do mentoring jobs, some ignored us and a few had topics we were not equipped to work on.

___

## November 2022

After rigorous searching we approached Dr. Roi Poranne and he shared with us his different project ideas.

Although pretty much every project was interesting we had to pick only one to dedicate ourselves to and so we made decition table:

| Charactaristics | % | Project Zippables | Architectural room identification | Text to building | VR - Architecture modeling | VR - Controlling robots | Redirected walking |
 | ------ | :------: | :------: | :------: | :------: | :------: | :------: | :------: | 
 | 1. Cool final product | **15%**  | 90➡13.5 | 80➡12   | 90➡13.5 | 75➡11.25 | 65➡9.75 | 50➡7.5 |  
 | 2. Practical knowledge| **25%**  | 65➡16.25| 85➡21.25| 95➡24   | 70➡22.5  | 70➡17.5 | 70➡17.5|  
 | 3. Project complexity | **20%**  | 85➡17   | 70➡14   | 70➡14   | 75➡15    | 80➡16   | 75➡15  |  
 | 4. Personal interest  | **40%**  | 90➡36   | 85➡34   | 85➡34   | 75➡30    | 80➡32   | 70➡28  |  
 |  Final Score          | **100%** | `82.75`  | 81.25    | `85.5`   | 78.75     | 75.25    | 68      |

___

## December 2022

After much consideration we decided against the `Text to building` project and we decided to pursue the `Zippables` project.

With our goals set we made a powerpoint, presented it and got the approval to continue.

We proceeded with our project plans and read our mentors original paper that the project is based on: [https://people.inf.ethz.ch/poranner/papers/zippables/zippables.pdf](https://people.inf.ethz.ch/poranner/papers/zippables/zippables.pdf)

Our mentor got access to the project repository of a newly published work about singularity prescribed parametrization by Yuta Noma which was published in the newest `SIGGRAPH Asia 2022`.

After reading their paper: [https://drive.google.com/file/d/1UFDIff7Xa6qmWm69r03iYrnmCY7ztpdp/view?usp=sharing](https://drive.google.com/file/d/1UFDIff7Xa6qmWm69r03iYrnmCY7ztpdp/view?usp=sharing) we spend some time compiling and running their Github project on our respective machines (although we somehow could not run the project on a laptop... still remains to be solved).

We started playing around and attempting to apply spiral parametrization algorithm as shown in paper, partially succeeding in setting vector field constraints, however we were not successful in creating a spiral.

### 1. Vector field perpendicular to intervals set by user, computed using Yuta Noma's application

<p align="center">
  <img src="https://github.com/LeonGurin/University-of-Haifa-Final-Project/blob/main/Progress%20Pictures/pic1.png"/>
</p>

### 2. Parametrization of said field, with bifurcations (which we wish to remove)

<p align="center">
  <img src="https://github.com/LeonGurin/University-of-Haifa-Final-Project/blob/main/Progress%20Pictures/pic2.png"/>
</p>

___

## January 2023

After a meeting with our mentor we realized we were working on the wrong branch, and promptly switched to the correct version.

We studied the algorithm used by the codebase up close, and now better understand its steps and how to utilize and change it.

With the correct version, we managed to achieve several spiral patterns and developable meshes using both changes to the code and the interactive GUI of the application.


The following are our results.

### Default parameterization of the bunny model

<p align="center">
  <img src="https://github.com/LeonGurin/University-of-Haifa-Final-Project/blob/main/Progress%20Pictures/parametrized_bunny1.png"/>
</p>
  
### Developabizing it

<p align="center">
  <img src="https://github.com/LeonGurin/University-of-Haifa-Final-Project/blob/main/Progress%20Pictures/developabized_bunny1.png"/>
</p>

<p align="center">
  <img src="https://github.com/LeonGurin/University-of-Haifa-Final-Project/blob/main/Progress%20Pictures/developabized_bunny2.png"/>
</p>
  
### Hard coded flow positions parameterization

<p align="center">
  <img src="https://github.com/LeonGurin/University-of-Haifa-Final-Project/blob/main/Progress%20Pictures/parametrized_armadillo1.png"/>
</p>

### Default parameterization of the armadillo model

<p align="center">
  <img src="https://github.com/LeonGurin/University-of-Haifa-Final-Project/blob/main/Progress%20Pictures/parametrized_armadillo2.png"/>
</p>

### Developabizing it

<p align="center">
  <img src="https://github.com/LeonGurin/University-of-Haifa-Final-Project/blob/main/Progress%20Pictures/developabized_armadillo1.png"/>
</p>

___

## February 2023

ongoing...

