```mermaid
gantt
dateFormat  YYYY-MM-DD
title Waterfall Model
excludes  weekends

section Software Process Model
Requirements Definition               :         des1, 2022-05-20, 2022-05-31
System and Software Design            :         des2, 2022-05-31, 3w
Implementation and Unit Testing       :         des3, after des2, 3w
Integration and System Testing        :         des4, after des3, 3w
Operation and Maintenance             :         des5, 2022-05-20, 10w
```
Requirements Definition:
  - Goals: Create a database of users and courses; different users with different roles perform different tasks unique to their roles.
  - Constraints: 
    + Create a system with users types: student, instructor, and admin.
    + Users should be able to do what their names suggest.
    + System should include multiple semesters, print-out of schedule, and scheduling preferences.
System and Software Design:
  - 
