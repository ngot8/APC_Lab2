```mermaid
gantt
dateFormat  YYYY-MM-DD
title Incremental Model
excludes  weekends

section Version Timeline
Initial Version               :         des1, 2022-05-10, 20d
Intermediate Version          :         des2, after des1, 20d
Final Version                 :         des3, after des2, 25d
Specification                 :         des4, 2022-05-10, 65d
Development                   :         des5, 2022-05-10, 65d
Validation                    :         des6, 2022-05-10, 65d
```

Initial Version:
  - Base "User" class; and "Student", "Instructor", "Admin" derived classes.
  - No functions yet, only base attributes.

Intermedate Version:
  - Add fucntions to each derived class.
  - Add database of courses and students.

Final Version:
  - Refine code, bug fixes, and user interface complete.
