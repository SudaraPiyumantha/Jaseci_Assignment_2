# Jaseci_Assignment_2
Our task is to add a new feature to the ancestry example that is discussed during the tutorial.

## Our Team
- M.H.S. Piyumantha     - 180480T (Leader)
- D.H.N.R. Weerasekara  - 180688M
- W.M.R.N. Wijethunga   - 180716B
- T.H.P. Silva          - 180605J
- P.A.H.K. Wijesena     - 180705P

## Updates in Family Tree
- Add a new member to the irugalbandara family - "harsha Irugalbandara"  (by T.H.P.Silva)
- Add a new family root called "Rathnayaka" and two persons (0x7 & 0x8) the familytree.json. Add a new field called date_of_death to each person. (by P.A.H.K. Wijesena)


## Added Walkers
### Walker: find_minors
####  - Created by M.H.S. Piyumantha
This walker determines the age of the each person and check whether the person, a minor (age: 18-) or not. 
Then, display "true" or "false" under each person node.
Also, it reports the minors in all family roots as an array of the format, [name, family_id, id, age]

### Walker: add_minors_to_family_tree & show_minors
####  - Created by D.H.N.R.Weerasekara
This walker find minors belonging to each family root and display it under the corresponding family_root.

### Walker: find_unemployed_members
####  - Created by T.H.P.Silva
This walker identified the unemployed memebrs in the family and display their names, age and geneder.

### Edited Walker- "find-coming-birthday"
####  - Created by W.M.R.N Wijethunga
If any of the members has deceased, it displays the life span of the deceased member by using the difference between the date of birth and the date of death.

## Walkers in Action

https://user-images.githubusercontent.com/61855651/233439540-18317f97-ef5e-4ac2-891b-44c67967b91b.mp4


